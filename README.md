# Structure-Theoretic Resolution of the Congruent Number Problem

This project presents a new classification-based resolution to the classical congruent number problem, introducing algebraic structures of the form:

```
ab - cd = n
```

with rational numbers `a, b, c, d > 0`, and classifying all such structure congruent numbers into:

- **PLBN (Pure Linear Balanced Number)**: ab − cd = a + b + c + d
- **EPLBN (Extended Linear Balanced Number)**: ab − cd = λ(a + b + c + d), λ in {1/2, 1/3, 2, 3}
- **MGNBN (Multiplicative Generator Non-Balanced Number)**: ab − cd = n only, no linear balance

## Highlights

- Full LaTeX manuscript (`.tex`) with defined theorems, proofs, and geometric interpretation
- Includes classification results for all congruent numbers up to n = 500
- Structure-to-elliptic curve correspondence demonstrated
- Supported by a pie chart of classification ratios

## Usage

To build the PDF:

```bash
pdflatex congruent_number_structure_final.tex
```

Ensure `structure_pie.png` is in the same directory as the `.tex` file.

## Author

Mizuho Watanabe.
im not professional.i truly believe to hope that this message is sent to hearted man.
なかきよの とおのねふりの みなめさめ なみのりふねの おとのよきかな

## License

See [LICENSE](./LICENSE)
