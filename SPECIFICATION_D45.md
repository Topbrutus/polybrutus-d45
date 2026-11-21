# Polybrutus D45 — Exact rational labelled Euclidean geometry

## Immutable parent D44 and all ancestors

The parent is exclusively `Topbrutus/polybrutus-d44@v0.1.0`, frozen scientific source commit `d5831cffec4330b6593c2242051d6e920c757080`, DOI `10.5281/zenodo.24415463`. Its deterministic exact certificate has SHA-256 `8c833b8907689ccc4e5519bd6d3c57eadba14876336dcc8d0fe63b672555b9e9` and exactly 49 norm-one vertices, 1,176 labelled pairs.

The complete original frozen scientific tag, **including all ancestral sources** is retained unchanged at `prior/d44/frozen_scientific_tag_v0.1.0.zip`, 2,149,619 bytes, 28 entries, CRC PASS, SHA-256 `e74794dbfa9c6eb4bb3307dc95d57462dc4176516260c7855f1eb31acde231ec`. Its embedded `results/certificate_d44.json` is copied byte-identically to `prior/d44/results/certificate_d44.json`. Both D45 exact verifiers verify ZIP SHA, CRC, original certificate bytes and certificate SHA.

## Conservative Euclidean extension

For norm-one predecessor vertices `p_i`, `i=1,...,49`, append one zero coordinate `q_i=(p_i,0)` and one orthogonal norm-one vertex `q50=e46`. All predecessor pair labels and squared values are **identical**. Each new squared pair distance is `||q50-q_i||²=1+1-2<q50,q_i>=2`. Therefore `C(50,2)=1225=1176+49` unordered labelled squared pairs.

An exact Gram `G` is constructed from an original seven-point rank-three rational block (`3*x_i*x_j+y_i*y_j+z_i*z_j`), an independent centered unit five-point regular simplex Gram block (diagonal one, off-diagonal `-1/4`, rank four), and **38** independent perpendicular unit axes. `rank(G)=3+4+38=45`, it is PSD by explicit vector construction and has unit diagonal. Set `D_ii=0`, `D_ij=2-2G_ij` and centering `H=I-11ᵀ/50`. The unique centered Euclidean Gram is `B=-(1/2)HDH=HGH`, exact rank **45**. One canonical antipodal pair places the origin in the affine hull, proving minimum Euclidean affine embedding dimension **45** for this complete metric; ambient coordinate storage count **46**.

## Exhaustive exact invariants at unit radius

```text
Points, norm one                                  50
Unordered labelled squared-distance pairs      1225
Original D44 labelled pairs conserved           1176/1176
New squared pair distances                      49 × 2
Histogram k=4d²/R²                              4:6 7:2 8:1194 9:3 10:10 12:6 13:2 16:2
Sum of all squared distances (R=1)              9847/4
Exact minimum affine/centered Gram rank          45
Ambient coordinate storage                      46
```

## Separately stipulated ideal weighted graph

Choose an ideal scalar-unit-mass complete graph with edge weights `w_ij=R²/d_ij²`. The new vertex is joined uniformly to all 49 parent vertices at weight 1/2. Exact weighted Laplacian:

```text
L45 = [ L44 + I49/2      -1_49/2 ]
      [ -1_49ᵀ/2             49/2 ].
```

Recurrence: `chi50(z)=z(z-25)chi49(z-1/2)/(z-1/2)`; model-specific closed form `chi50(z)=z(z-25)^39(z-49/2)^4 f6(z-43/2)`, where `f6(z)=chi_P7(z)/z` is the nonzero original seven-point graph factor.

Independent exact matrix nullities establish `nullity(L45-25I)=39`, `nullity(L45-(49/2)I)=4`. These are **dimensionless selected-model graph eigenvalues**, not observed physical frequencies.

**Verified references:** see [REFERENCES.md](REFERENCES.md) and parent [Zenodo 44D](https://doi.org/10.5281/zenodo.24415463).
