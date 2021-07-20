# TECL

End-to-end Temporal Causal Learning (TECL) using Machine Learning.

# usage

```
import TECL

cl = TECL()
rel = cl.discover()
g = cl.generate_graph()
est = cl.estimate(g)
cl.refute()
```