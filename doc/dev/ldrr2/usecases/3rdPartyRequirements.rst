Lyve Rack must be running on the supported CentOS version 
->No dependency on Motr functionality except build process

All 3rd party applications must be running recent, maintained versions  
-> Libfabric version should be latest

Any failure of any 3rd party SW component must be detected by CORTX and exposed via Alerts and Telemetry system 
-> Netlayer should raise IEM for any Libfabric error
-> Any Galois erasure coding related error ?

CORTX should have no kernel dependencies 
-> Libfabric task 

CORTX should use no 3rd party SW unless it is appropriately permissively licensed 
-> Need mail from Legal regarding libfabric and Galois (Galois is being used in CEPH?)

Legal recommendations must be followed 
-> 1. b-tree rewrite 
-> 2. balloc rewrite
-> 3. Replace Galois is legal does confirmation
