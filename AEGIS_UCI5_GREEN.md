# AEGIS UCI-5 persisted-control reopen RED trigger

Candidate: `Aegis-Omega/AEGIS-OMEGA@fd1d5d01e168ef0bfdf566b32d93b57633fc35d5`

Expected parent: `9702004a6230d6a84cc322edb48b55c14e90fe15`

This candidate adds only reopen regression tests over the existing UCI-5 implementation. Expected RED: conflicting persisted policy, authority epoch, and fence are not yet rejected when reopening a sequence>0 store.
