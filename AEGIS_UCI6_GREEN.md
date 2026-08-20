# AEGIS UCI-6 internal-base RED trigger

Candidate: `Aegis-Omega/AEGIS-OMEGA@46c474309254fc6909071ea4d8e79a0bbce48d47`

Expected parent: `c47e99b8139a280c39ceacc46db738b2617866d5`

Required result: exact lineage passes; prior 24 UCI-6 tests remain green; the new internal-base guard test fails specifically because `_collective_memory_base.LocalSqliteCollectiveMemoryStoreV1` is still directly constructible.
