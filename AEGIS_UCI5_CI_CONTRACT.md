# AEGIS UCI-5 CI-contract RED witness

Candidate: `Aegis-Omega/AEGIS-OMEGA@418a8464e1aa4ccbf6d5e052b949c8637999e71c`

Expected parent: `9702004a6230d6a84cc322edb48b55c14e90fe15`

Required result: exact lineage passes; the 20 existing UCI-5 runtime tests remain green; the two newly preregistered static CI-contract tests fail specifically because the workflow does not yet bind the literal frozen parent and does not yet enforce `99 passed` proofline cardinality.
