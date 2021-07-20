# TECL

Deep Learning based End-to-end Temporal Causal Learning (TECL)

# usage

```python
from causal import TemporalCausalDiscovery, TemporalCausalEffect

tcl = TemporalCausalLearning(data)
rel = tcl.discover(method='TCDF')
g = tcl.generate_graph()

model = TemporalCausalEffect(g, treatment, outcome)
model.identify()

ce = model.estimate(data, method='gAIPW')
model.refute()
```
