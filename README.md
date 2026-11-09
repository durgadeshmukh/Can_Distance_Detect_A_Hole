# Can Distance Detect a Hole?
A visual and theoretical investigation of **Cauchy sequences, completeness, and metric structure** in metric spaces.

## Overview
Can two different metrics on the same set induce the same topology but disagree about completeness?
This project explores this question using the open interval (0,1).
Under the usual metric d(x,y) = |x − y|, the sequence xₙ = 1/n is Cauchy but does not converge within (0,1), making the space incomplete.
I then consider the transformed metric ρ(x,y) = |h(x) − h(y)|, where h(x) = ln(x/(1 − x))
Although this metric induces the same topology on (0,1), it makes the space complete. The map h is a bijective isometry from ((0,1),ρ) onto R.
This provides a concrete example of how **topological equivalence does not imply the same completeness behaviour**.

## Key Ideas
- Cauchy sequences and completeness
- Metrics and induced topology
- The usual metric on (0,1)
- A transformed metric on (0,1)
- Isometries and pullback metrics
- Uniform continuity and Lipschitz equivalence
- Completions of metric spaces
- The relationship between metric structure and topology

## Computational Work
Python, NumPy, and Matplotlib were used to visualise:
- the transformation h(x)
- the behaviour of distances under the two metrics
- the sequence xₙ = 1/n
- the limiting behaviour of ρ(1/n, 1/(2n))
- the stretching of distances near the endpoints

## Project Files
- `Field_Project_Report.pdf` — Complete project report with proofs and mathematical development
- `FP_Slides.pdf` — Presentation slides
- `visualizations/` — Computational visualisations and related files

## Conclusion
The project shows that **completeness is a metric property rather than a purely topological one**.
Changing the metric can change which sequences are Cauchy and whether the space is complete, even when the underlying topology remains unchanged.

## Author
**Durga Deshmukh**  
T.Y. B.Sc. Mathematics  
S.P. College, Pune  
Academic Year 2026–2027
