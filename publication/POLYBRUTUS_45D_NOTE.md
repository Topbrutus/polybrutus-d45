# Polybrutus 45D: Exact 50-point Euclidean metric and a thirty-ninefold ideal graph mode

**Gabriel St-Pierre** — Independent researcher  
**21 November 2026**  
**Exact mathematical case study / preprint**  
**Material AI assistance:** OpenAI ChatGPT (Astra) assisted rational calculations, two distinct exact verification implementations, manuscript and controlled publication. AI is not a scientific author.

## Abstract

We construct one exact Euclidean labelled squared-distance metric on 50 norm-one points by adjoining a new perpendicular norm-one point to the immutable Polybrutus 44D source [1]. All 1,176 old labelled squared-distance pairs are conserved, and 49 new squared distances equal 2 at unit radius, resulting in 1,225 labelled unordered pairs. The exact centered Euclidean Gram is positive semidefinite of rank 45, proving minimum Euclidean affine realization dimension 45 for this synthetic metric. For a separately stipulated ideal unit-mass complete weighted graph with edge weights w_ij=1/d_ij², graph Laplacian eigenvalue 25 has multiplicity 39 and 49/2 has multiplicity 4. Two independently implemented exact-rational programs check every pair, original ancestor source integrity and these mathematical invariants. No physical extra dimensions or experimental frequencies are claimed.

## 1. Scientific parent and complete original ancestry

The exact predecessor is Gabriel St-Pierre, Polybrutus 44D [1], DOI 10.5281/zenodo.24415463. Its immutable scientific tag is Topbrutus/polybrutus-d44@v0.1.0, commit d5831cffec4330b6593c2242051d6e920c757080, with 49 norm-one labelled vertices and 1,176 exact unordered pair squared distances. The parent certificate SHA-256 is 8c833b8907689ccc4e5519bd6d3c57eadba14876336dcc8d0fe63b672555b9e9.

The full unchanged source tag and its earlier scientific ancestors are archived in prior/d44/frozen_scientific_tag_v0.1.0.zip, 2,149,619 bytes, 28 entries, CRC PASS and SHA-256 e74794dbfa9c6eb4bb3307dc95d57462dc4176516260c7855f1eb31acde231ec. Both exact verifying programs authenticate the complete archive, its embedded original parent certificate, the extracted byte-identical certificate and its SHA-256. The ZIP packaging avoids Windows MAX_PATH while retaining the entire source lineage intact.

Zero extend every old norm-one vector p_i to q_i=(p_i,0), i=1,...,49, and adjoin new orthogonal unit vertex q50=e46. Every predecessor pair label and squared value is unchanged. The 49 new squared distances are ||q50-q_i||²=1+1-2<q50,q_i>=2. Hence C(50,2)=1225=1176+49 labelled unordered squared pairs.

## 2. Exact rational Gram and minimum Euclidean realization

The canonical seven-unit-point rational Gram block has rank three and inner products 3*x_i*x_j+y_i*y_j+z_i*z_j. Five independent centered regular-simplex unit points form a rank-four Gram block, unit diagonal and off-diagonal products -1/4. Thirty-eight additional independent mutually orthogonal unit axes are perpendicular to both blocks. Thus complete rational Gram G is PSD by explicit construction, with unit diagonal and rank 3+4+38=45.

With squared-distance matrix D_ii=0 and D_ij=2-2G_ij, and H=I-(1/50)11ᵀ, the uniquely centered Euclidean Gram B=-(1/2)HDH=HGH has exact rank 45. The inherited antipodal canonical point pair puts the origin in the affine hull. Consequently the minimum Euclidean affine dimension for this exact labelled metric is 45; the explicit construction attains this bound.

## 3. Exhaustive 1,225 labelled squared-distance invariants

At unit radius, normalized index k=4d²/R² has exactly eight value classes: k=4 on 6 pairs; k=7 on 2; k=8 on 1,194; k=9 on 3; k=10 on 10; k=12 on 6; k=13 on 2; k=16 on 2. These counts sum to 1,225. The exact sum of all squared pair distances at R=1 is 9847/4. All 1,176 inherited pair labels are matched against the original authenticated parent certificate, not merely against a histogram.

## 4. Separately stipulated unit-mass complete weighted graph

Choose, separately from the metric, an ideal complete graph with scalar unit masses and symmetric edge weights w_ij=1/d_ij². The appended perpendicular vertex joins all 49 predecessors with weight 1/2, giving the block Laplacian

L45 = [ L44+(1/2)I49           -(1/2)1_49 ]
      [ -(1/2)1_49ᵀ                   49/2 ].

The uniform-join recurrence is chi50(z)=z(z-25)chi49(z-1/2)/(z-1/2). Writing f6(z)=chi_P7(z)/z for the nonzero original seven-point model graph factor, the exact chosen-model closed form is chi50(z)=z(z-25)^39(z-49/2)^4 f6(z-43/2).

Two separate rational nullity calculations establish nullity(L45-25I)=39 and nullity(L45-(49/2)I)=4. These are dimensionless eigenvalues of one freely stipulated abstract graph, not acoustic hertz, new physical particles or dimensions.

## 5. Reproducibility and negative controls

The primary src/verify_d45.py builds the exact rational Gram, verifies all 1,225 labels, authenticated parent source archive and all 1,176 inherited labelled values, exact Euclidean centered rank and chosen graph eigenspace nullities. Four adversarial controls detect a deliberately corrupted pair, a duplicated point, a nonorthogonal tilt and a label permutation that leaves the histogram unchanged.

The separate tests/independent_d45.py computes each labelled squared distance with Python fractions.Fraction structural rules without importing the primary Gram generator. It checks archive SHA and CRC, byte-identity of original parent certificate, every inherited label, all new labels and the exact rational ranks. Both scripts emit the same deterministic SHA-256 for results/certificate_d45.json and are rerun in GitHub CI. Reproduce with sympy==1.14.0 and execute both scripts.

## 6. Scientific limits and responsible metadata

Orthogonal Euclidean extension and uniform graph joining are established mathematical constructions. These verifiable calculations concern one synthetic metric and one separately stipulated ideal weighted graph, not 45-dimensional physical spacetime, measured resonances, a new universal theorem or independently human peer-reviewed physics. Polybrutus 7D [2] is cited as earlier project context, not as the immediate scientific source.

For traceability, Zenodo metadata must provide a structured isDerivedFrom relation to the **verified immediate parent DOI 10.5281/zenodo.24415463** [1], a separate textual bibliography containing [1] and [2], and keywords generated from the present verified certificate: forty-five and thirty-ninefold. These fields must be checked from the public Zenodo API after publication.

## References

[1] St-Pierre, Gabriel (2026). Polybrutus 44D: Exact 49-Point Euclidean Metric and Thirty-Eightfold Ideal Graph Mode. Zenodo. DOI: 10.5281/zenodo.24415463. https://doi.org/10.5281/zenodo.24415463

[2] St-Pierre, Gabriel (2026). Polybrutus 7D: An Exact Twelve-Point Orthogonal Completion, the 12-35-37 Identity, and an Oscillator Model. Zenodo. DOI: 10.5281/zenodo.24407952. https://doi.org/10.5281/zenodo.24407952

[3] St-Pierre, Gabriel (2026). Polybrutus D44 frozen scientific tag v0.1.0. GitHub source: https://github.com/Topbrutus/polybrutus-d44/tree/v0.1.0, scientific commit d5831cffec4330b6593c2242051d6e920c757080. Immutable source archive included here.
