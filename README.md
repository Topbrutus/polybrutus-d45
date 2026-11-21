# Polybrutus 45D — Exact 50-point Euclidean metric and a thirty-ninefold ideal graph mode

**Responsible scientific author:** Gabriel St-Pierre, independent researcher.  
**Material AI assistance:** OpenAI ChatGPT (Astra) assisted exact computation, two separate verifiers, scientific writing and publication; AI is not an author.

## Verified exact mathematical construction

- **50 labelled norm-one points**, **1,225 unordered labelled squared distances**, **1,176/1,176** parent labels conserved, **49 new squared distances**, all **2R²**.
- **Euclidean centered Gram PSD, exact affine rank 45** for this synthetic labelled metric; coordinates stored in 46 dimensions.
- At R=1, squared-distance histogram `k=4d²/R²`: `{4:6,7:2,8:1194,9:3,10:10,12:6,13:2,16:2}`; squared-distance sum **9847/4**.
- In a **separately stipulated ideal complete graph** with scalar unit masses and symmetric weights `w_ij=R²/d_ij²`, the weighted Laplacian has **eigenvalue 25 of multiplicity 39** and **eigenvalue 49/2 of multiplicity 4**. These are dimensionless model eigenspaces, **not measured hertz**.
- Two separately implemented exact-rational verifiers check all labels, exact Euclidean ranks, selected graph nullities and parent source integrity. Four main adversarial negative controls pass.

## Reproduce

```bash
python -m pip install sympy==1.14.0
python src/verify_d45.py
python tests/independent_d45.py
```

Both scripts report the identical deterministic SHA-256 of `results/certificate_d45.json`.

## Ancestry preserved in full

Scientific source parent **[Polybrutus D44 v0.1.0](https://github.com/Topbrutus/polybrutus-d44/tree/v0.1.0)**, frozen commit `d5831cffec4330b6593c2242051d6e920c757080`, [DOI 10.5281/zenodo.24415463](https://doi.org/10.5281/zenodo.24415463). The **complete original D44 tag and all earlier ancestors** are in `prior/d44/frozen_scientific_tag_v0.1.0.zip`, SHA-256 `e74794dbfa9c6eb4bb3307dc95d57462dc4176516260c7855f1eb31acde231ec`, 2,149,619 bytes, 28 entries and CRC PASS. The original `results/certificate_d44.json` is extracted byte-identically to `prior/d44/results/certificate_d44.json`, SHA-256 `8c833b8907689ccc4e5519bd6d3c57eadba14876336dcc8d0fe63b672555b9e9`. Both exact checkers authenticate these sources.

## Scientific writing and bibliographic traceability

- [Mathematical specification](SPECIFICATION_D45.md), [constructive proof](PREUVE_D45.md), [scientific provenance](PROVENANCE.md), [full parent archive](prior/d44/ARCHIVE_PROVENANCE.md).
- [Complete bibliography with verified DOI](REFERENCES.md); [scientific preprint (PDF)](publication/POLYBRUTUS_45D_NOTE.pdf) and [editable source](publication/POLYBRUTUS_45D_NOTE.md); [complete exact certificate](results/certificate_d45.json).
- **Zenodo metadata QA gate:** keywords `affine Euclidean dimension forty-five` and `thirty-ninefold ideal eigenvalue` must be generated from the present certificate. The Zenodo record must include **`related_identifiers`** `isDerivedFrom` -> DOI **10.5281/zenodo.24415463**, plus the separate textual **`references`** field, both checked publicly after publication. No copied 31D keywords.

**Scientific limits:** This is one reproducible synthetic Euclidean metric and a separately selected ideal graph constructed with established perpendicular extensions and weighted-graph joining. It does **not** establish physical extra spacetime dimensions, measured frequencies, particles, a universal new theorem or independent human peer review.

**Licenses:** MIT code; CC BY 4.0 manuscript.
