# TECL

End-to-end Temporal Causal Learning (TECL) using Machine Learning.

# usage

```
from model import TemporalCausalLearning

tcl = TemporalCausalLearning()
rel = tcl.discover()
g = tcl.generate_graph()
est = cl.estimate(g)
cl.refute()
```