
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fjk3587%2Fhbc_flow_chart%2Fmain%2FREADME.md)
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4"
    q1 [shape=box label="does it have goat cheese and figs?"]
    yes [label="hbc approved" fontcolor=green] 
    q1 -> yes [weight=8 label="yes"]
    q1 -> q2 [weight=8 label="no"]
    q2 [shape=box label="is it from 1618?"]
    q2 -> yes [weight=8 label="yes"]
    q2 -> q3 [weight=8 label="no"]
    q3 [shape=box label="is it that indian place from San Marcos"]
    q3 -> yes [weight=8 label="yes"]
    q3 -> no [weight=8 label="no"]
    no [shape=box label="further questions required"]
  }
custom_mark10
</details>

