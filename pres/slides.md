# Docker in organizations
## "Is Docker for me/us?"
Note:
- Sharing recent experience + share considerations
- How many people are here to get an answer to the question "is Docker a tool for me?", or do you already know the answer to that?
- more importantly, when we change "me" into an org. or project

---

## Developer
### & Docker
<img src="pres/enthusiasm-dev.jpg" width="75%" style="margin-top: 50px;"/>
Note:
- First Point of View. Developer + Ops + Test
- Developers usually are pretty enthusiatic about Docker!
-
<img src="pres/enthusiasm-manager.jpg" width="75%" style="margin-top: 50px;" />
Note: so everyone is, right?
-
## ...
<img src="pres/enthusiasm-manager-not.jpg" width="75%" style="margin-top: 50px;" />

---

# Always keep the larger process in mind

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

## Awareness of organisational aspects
<br/>
#### PO (5) &#8594; Dev (2) &#8594; Test (4) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="1" -->
#### PO (5) &#8594; Dev (4) &#8594; Test (4) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="2" -->
#### PO (5) &#8594; Dev (4) &#8594; Test (4) &#8594; Ops (3) <!-- .element: class="fragment" data-fragment-index="3" -->
#### PO (5) &#8594; Dev (9) &#8594; Test (4) &#8594; Ops (3) <!-- .element: class="fragment" data-fragment-index="3" style="color: red" -->
<br/>
#### (5) &#8594; Dev (3) &#8594; (2) &#8594; Test (3) &#8594; (5) <!-- .element: class="fragment" data-fragment-index="4" -->
#### PO (5) &#8594; TDD (5) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="4" -->
#### PO (5) &#8594; DevOps (8) <!-- .element: class="fragment" data-fragment-index="4" -->
<br/>
#### PO (5) &#8594; Test Driv Dev (5) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="5" -->
#### PO (7) &#8594; DevOps (8) <!-- .element: class="fragment" data-fragment-index="5" -->
Note:
- handover => TDD, DevOps
- Docker helps for DevOps! Dev. delivers deployable which they maintain, abstraction layers such as Mesos
- Is the DevOps step a win here?
- It has agile advantages.
- Less risk due to RollBackability
- Possibilities like A/B testing
- is DevOps possible in your organisation? It is not just Docker!

---

# Quality & Fun
<br/>
## Not everything fits the value stream 

---

## CEO

### Saving costs <!-- .element: class="fragment" data-fragment-index="1" -->
### Faster time to market <!-- .element: class="fragment" data-fragment-index="2" -->
### Hiring perspective: hot <!-- .element: class="fragment" data-fragment-index="3" -->
### Allow growth where technical complexity was a boundary before <!-- .element: class="fragment" data-fragment-index="4" -->
Note:
- cost saving due to less overprovisioning
-- elastic scaling
-- resource optimilisation (Docker vs. VM, no OS)
- Growth in micro-service setup

---

## Project / Middle managers

### Reducing dependencies between teams <!-- .element: class="fragment" data-fragment-index="1" -->
### Attractive for engineers <!-- .element: class="fragment" data-fragment-index="2" -->
### Agile process benefits <!-- .element: class="fragment" data-fragment-index="3" -->
