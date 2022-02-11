# Anomaly Detection SVJ

## Generating Truth Level Data (To be updated)

For general workflow for running Athena Analysis on PanDA, see [Running Athena analysis](https://panda-wms.readthedocs.io/en/latest/client/pathena.html)

First, we need to setup the environment,
```
export ATLAS_LOCAL_ROOT_BASE=/cvmfs/atlas.cern.ch/repo/ATLASLocalRootBase
source ${ATLAS_LOCAL_ROOT_BASE}/user/atlasLocalSetup.sh
setupATLAS
asetup 21.2.93.0,AthDerivation,here
```
Next, we need to setup panda-client,
```
lsetup panda
```
To check whether PanDA is sucessfully setup, we can try running,
```
pathena --helpGroup ALL
```

Documentations:
- [PhysicsAnalysisWorkbook](https://twiki.cern.ch/twiki/bin/viewauth/AtlasProtected/PhysicsAnalysisWorkBook)
- [Rucio](https://rucio.cern.ch/documentation/)
- [PanDA](https://panda-wms.readthedocs.io/en/latest/index.html)
