# MDSPlus

## Magnetic measurements and currents
- 39334 funziona
- setup: config spari
- rc sui device, setup device. quadratini 
- actions + diag inutili
- mhd: tutto su mhd del plasma, incl misure magnetice
- eda misure coorente fluss
- BR camp radiale
- MHD-> AC -> vme (i pc che gestivano il sistema di controllo) -> MARTE (software di controlo) -> signals -> User (tutti i segnali in input e output del sistema di controllo)
- script python per vedere tutti i figli e ottenere i dati
- dequ corrente di plasma
- eda1, eda1 
- i 192 sensori sono prima poloidal (cerchio piccolo) e poi toroidal a gruppi di 4
- python script:
```python
from MDSplus import *
t = Tree('rfx', 39334)
n = t.getNode("\RFX::TOP.RFX.EDA.EDA1.EDA1.VME:MARTE.SIGNALS.USER") # segnali toroidali / poloidali
n = t.getNode("\RFX::TOP.RFX.MHD.MHD_AC:VME:MARTE.SIGNALS.USER") # roba MHD 1
n = t.getNode("\RFX::TOP.RFX.MHD.MHD_BR:VME:MARTE.SIGNALS.USER") # roba MHD 2
n = t.getNode("\A::EMRA_IT") # corrente di plasma

for desc in n.getDescendants():
 try:
   print(desc.NAME.getData())
 except:
   pass
# myData = t.getNode("\RFX::TOP.RFX.MHD.MHD_BR:VME:MARTE.SIGNALS.USER.USER_035")
# myData.DATA.getData().data()            # queste sono le y
# myData.DATA.getData().getDimensionAt()  # queste sono le x
```
## Note interne
portal > diskr> note interne > note interne.
wiki > oldversion > techinal wiki
diskr> experi> diag> layout


