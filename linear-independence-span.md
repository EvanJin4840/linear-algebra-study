# Linear Independence & Span

## 1. Linear Combination
A **linear combination** of vectors \(v_1, ..., v_k\) is:
\[
c_1 v_1 + c_2 v_2 + ... + c_k v_k
\]
where \(c_i\) are scalars.

## 2. Span (Linear Generation)
**Set of ALL linear combinations** of given vectors.

1 vector → line (1D)
2 non-collinear → plane (2D)
3 non-coplanar → space (3D)

**Example**:
Span{(1,0), (0,1)} = ℝ² (entire plane)
Span{(1,0)} = x-axis only

## 3. Linear Independence
c₁v₁ + ... + cₖvₖ = 0 ⟹ ALL cᵢ = 0
**No vector is redundant.**

- Independent: (1,0), (0,1)
- Dependent: (1,0), (2,0)


## 4. Linear Dependence (Opposite)
**Exists non-zero cᵢ where sum = 0.**

2(1,0) - (2,0) = 0 → Dependent

## 5. Key Tests
Matrix [v₁ v₂ ... vₖ]:
- rank = number of vectors → Independent
- det ≠ 0 → Independent (square case)

## 6. Basis = Independence + Span
Standard ℝ³ basis:
(1,0,0), (0,1,0), (0,0,1)
- Spans ℝ³
- Linearly independent

## Examples Table
| Vectors | Span | Independence | Dimension |
|---------|------|--------------|-----------|
| (1,0) | line | Independent | 1 |
| (1,0),(0,1) | ℝ² | Independent | 2 |
| (1,0),(2,0) | line | Dependent | 1 |