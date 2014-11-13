# Docker in organizations

-

# Considerations
## Whole process
## Scope of the use case

---

## Developer + Docker
<img src="pres/enthusiasm-dev.jpg" width="75%" style="margin-top: 50px;"/>
Note: Developer + Ops + Test: happy about Docker
-
<img src="pres/enthusiasm-manager.jpg" width="75%" style="margin-top: 50px;" />
Note: so we might assume everyone is, right?
-
## ...
<img src="pres/enthusiasm-manager-not.jpg" width="75%" style="margin-top: 50px;" />
Note: they know something we sometimes forget: the bigger picture

---

# Always keep the whole process in mind

---

## Time to market
## Value stream
<br/>
### <img style="height: 100px; border: none; box-shadow: none; vertical-align: middle;" src="pres/lamp.jpg"/> &#8594; PO &#8594; Dev &#8594; Test &#8594; Ops &#8594; <img style="height: 100px; border: none; box-shadow: none; vertical-align: middle;" src="pres/user.png"/>
### Will Docker help?  <!-- .element: class="fragment" data-fragment-index="2" -->
Note:
- Nothing new here, this is all old Toyota stuff.
- Question is, will Docker help you with that? So, this brings us from "Is Docker for me?" to "Is Docker for us?"

---

## Find the constraints
<br/>
### PO (5) &#8594; Dev (2) &#8594; Test (4) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="1" -->
### PO (5) &#8594; Dev (4) &#8594; Test (4) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="2" -->
<br/>
### PO (5) &#8594; DevOps (8) <!-- .element: class="fragment" data-fragment-index="3" -->
<br/>
### PO (7) &#8594; DevOps (8) <!-- .element: class="fragment" data-fragment-index="4" -->
Note:
* Map your process.
* Solve the bottleneck.
* Dont use Docker if it doesnt help, no matter how many other problems it might solve.
- handover => TDD, DevOps
- Docker helps for DevOps! Dev. delivers deployable which they maintain, abstraction layers such as Mesos
- It has agile advantages. RollBackability, A/B testing

---

# Scope
<br/>

|           | Environment      | Testing              | Operations |
| --------- | ---------------- | -------------------- | ----- |
| Personal  | Wrap software    | Try out stuff        | |
| Team      | Dev. environment | Autom. tests         | Replace Puppet scripts with Docker, Resource optimization |
| Company   | Comp. wide repos | Monkey, Gorilla, A/B | Elastic scaling, Self-healing |

Note: keep in mind the SCOPE of what you want to do and who you need to INVOLVE

---

# Conclusion
* Map the delivery pipeline to find Docker uses
* Involve who you need to make stuff work

