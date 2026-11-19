# Edge General Position Numbers of Lucas Cubes

Research No.76, v1.0 — Ryutaro Yonezu, Independent Researcher.

For every integer n >= 3, the edge general position number of the Lucas cube is `gp_e(Lambda_n) = F_n + F_{n-2}` (`F_0=0`, `F_1=1`). This is a computer-assisted proof based on the frozen v0.1-v0.3 mathematical lineage and the v0.4 proof-dependency clarification. Maximum-set uniqueness is not claimed. The theorem does not rely on Research No.75.

The paper PDF, source Markdown and TeX, and reproducibility ZIP are provided here. Run `python -B -I verify_public.py` inside the extracted ZIP. The source verifiers and mathematical notes are unchanged from the frozen lineage; the public runner is a wrapper. Exact whole-graph bases required by the proof are n=3,4,6. The 9,908 capacity checks (including overlaps) remain required. The n=6 negative relaxation margin is handled by the exact optimum 11. Independent n=8,9 whole-graph CP-SAT optimum proofs were unfinished and are not premises of the all-dimension theorem.

Independent AI mathematical audit: PACKAGE / DELTA / REQUIRED BASES / INDUCTION PASS, CAPACITY BASES PASS within the prior independent scope, THEOREM **conditional PASS**. The auditor's historical PUBLICATION HOLD recommendation was not changed; publication is by the author's separate explicit acceptance of the conditional status. NOVELTY INCONCLUSIVE. REFERENCES PARTIAL. NOT HUMAN PEER REVIEWED.

Klavžar and Tan (2023), *Edge General Position Sets in Fibonacci and Lucas Cubes*, Bull. Malays. Math. Sci. Soc. 46:120, DOI: 10.1007/s40840-023-01517-y, established the Lucas-cube lower bound `2F_{n-1}` and exact n=5 value 7. That paper did not explicitly conjecture the Lucas-cube all-dimension formula. Historical novelty is not established by the present search.

Copyright (c) 2026 Ryutaro Yonezu. All rights reserved. No Creative Commons or open-source license is granted.
