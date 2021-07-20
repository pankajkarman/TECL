# TECL

End-to-end Temporal Causal Learning (TECL) using Machine Learning.



# usage

```python
from tecl import TemporalCausalDiscovery, TemporalCausalEffect

tcl = TemporalCausalLearning(data)
rel = tcl.discover(method='TCDF)
g = tcl.generate_graph()

model = TemporalCausalEffect(g, treatment, outcome)
model.identify()

ce = model.estimate(data, method='gAIPW')
model.refute()
```