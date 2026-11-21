# Polybrutus D45 — Exact constructive proof

**Parent scientific source:** [D44 v0.1.0](https://github.com/Topbrutus/polybrutus-d44/tree/v0.1.0), commit `d5831cffec4330b6593c2242051d6e920c757080`, DOI [10.5281/zenodo.24415463](https://doi.org/10.5281/zenodo.24415463). Parent deterministic certificate SHA-256 `8c833b8907689ccc4e5519bd6d3c57eadba14876336dcc8d0fe63b672555b9e9`.

**1. Lineage integrity.** Full original D44 frozen scientific source including all older archives is tracked in `prior/d44/frozen_scientific_tag_v0.1.0.zip`, SHA-256 `e74794dbfa9c6eb4bb3307dc95d57462dc4176516260c7855f1eb31acde231ec`, 28 entries and CRC PASS. The extracted certificate at `prior/d44/results/certificate_d44.json` is byte-identical to the archive entry and original SHA-256. Both independent verifiers check complete archive and certificate.

**2. Every old pair label preserved.** Zero extend all 49 prior norm-one Euclidean vectors and append one perpendicular unit vector. All 1,176 original pair labels preserve exactly their former squared values; every new squared distance equals `2R²`. Thus **1,225=C(50,2)=1,176+49** unordered labelled squared distances.

**3. Exact PSD and minimal affine rank.** Seven canonical vectors form a rank-three rational Gram; five centered simplex vectors independently contribute rank four; 38 perpendicular norm-one coordinate axes contribute rank 38. The full exact rational Gram is PSD and rank `45`, unit diagonal. The unique centered Gram `B=-(1/2)HDH=HGH` has rank 45. Original canonical antipodal points place origin in affine hull; thus minimal affine dimension for this labelled metric is precisely **45**.

**4. Exhaustive rational arithmetic.** Histogram of `k=4d²/R²`: `{4:6,7:2,8:1194,9:3,10:10,12:6,13:2,16:2}`, sum 1225. All squared distances at R=1 sum exactly **9847/4**.

**5. Distinct ideal complete weighted graph.** With scalar unit masses and stipulated `w_ij=1/d_ij²`, exact rational Laplacian ranks verify **eigenvalue 25 with multiplicity 39**, **eigenvalue 49/2 with multiplicity 4**. These are dimensionless mathematical modes, not hertz.

**6. Independent verification and adversarial controls.** `src/verify_d45.py` builds exact Gram and labelled squared pairs, verifies 1,176 old labels, rank and selected graph nullities. Four main negative controls detect wrong distance, duplicate vertex, nonorthogonal tilt, and label swap that preserves histogram. `tests/independent_d45.py` separately constructs all pair values via Python `fractions.Fraction` without importing the primary Gram, checks all 1,225 labels, same 1,176 predecessor labels, ranks and full lineage. Both output the same deterministic SHA of `results/certificate_d45.json`.

**7. Publication reference controls.** The verified [D44 DOI](https://doi.org/10.5281/zenodo.24415463) must appear consistently in the source specification, manuscript, `CITATION.cff` context and Zenodo `related_identifiers`. Source keywords must derive from D45 (forty-five) and its **39-fold** chosen ideal graph eigenspace (thirty-ninefold), **not copied from 31D**. The separate Zenodo text `references` must contain verified scholarly bibliographic entries including D44, with public readback after publication. See [REFERENCES.md](REFERENCES.md).

No claim is made of new universal physics, measured physical dimensions or experimentally observed frequencies. The construction uses established exact Euclidean and ideal weighted-graph techniques.
