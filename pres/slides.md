# Prerequisites to Docker 
## Docker in organizations
Note:
- Sharing experience of my last months of work: delta soft skills > delta technical skills
- Share considerations
- How many people are here to get an answer to the question "is Docker a tool for me?", or do you already know the answer to that?

-
## "Is Docker for me?"
### ... for us?
Note:
- still, that is the question I would like to discuss.
- or more importantly, when we change "me" into an org. or project

---

## Developer
### & Docker
<img src="pres/enthusiasm-dev.jpg" width="75%" style="margin-top: 50px;"/>
Note:
My experience up to Container Solutions has mostly been with developers, at this meetup etc. And developers usually are pretty enthusiatic about Docker!
-
<img src="pres/enthusiasm-manager.jpg" width="75%" style="margin-top: 50px;" />
Note: Developers van have a bit of a tunnel vision. It is easy to assume that all parts in the organisation will be as enthusiatic as the dev, however...
-
## ...
<img src="pres/enthusiasm-manager-not.jpg" width="75%" style="margin-top: 50px;" />
Note: Docker just might not be a perfect fit for an organisation in a certain state, leaving managers with a headache.

---

## IT in a company
- Supportive use of software <!-- .element: class="fragment" data-fragment-index="1" -->
- Software as key 'value'<!-- .element: class="fragment" data-fragment-index="2" --> 
Note: interest in companies or projects that have software a key value. Developing it and delivering/selling it.

---

## Time to market
<img src="pres/enthusiasm-manager.jpg" width="45%" style="margin-top: 50px;" /> <!-- .element: class="fragment" data-fragment-index="1" -->
### Will Docker help?  <!-- .element: class="fragment" data-fragment-index="2" -->

Note:
- TTM is a key concept. Reducing TTM will result in value. Happy sales, happy scrum masters, happy CEOs, etc. 
- Question is, will Docker help you with that? So, this brings us from "Is Docker for me?" to "Is Docker for us?"

---

## Value stream
<br/>
### <img style="height: 100px; border: none; box-shadow: none; vertical-align: middle;" src="pres/lamp.jpg"/> &#8594; PO &#8594; Dev &#8594; Test &#8594; Ops &#8594; <img style="height: 100px; border: none; box-shadow: none; vertical-align: middle;" src="pres/user.png"/>
Note:
Nothing new here, this is all old Toyota stuff.

---

## Theory of constraints
<br/>
### PO (5) &#8594; Dev (2) &#8594; Test (4) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="1" -->
### PO (5) &#8594; Dev (4) &#8594; Test (4) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="2" -->
### PO (5) &#8594; Dev (4) &#8594; Test (4) &#8594; Ops (3) <!-- .element: class="fragment" data-fragment-index="3" -->
### PO (5) &#8594; Dev (9) &#8594; Test (4) &#8594; Ops (3) <!-- .element: class="fragment" data-fragment-index="4" style="color: red" -->
Note:
- The idea is simple. Improve the bottleneck speed. Even when this reduces capacity of another step
- If you can use Docker to do this, do!
- Actually bad to increase non-bottlenecks. Seen lots of finished dev-work that could not be deployed, value reduces over time.

---

## Theory of constraints
## Hand-offs
<br/>
### (5) &#8594; Dev (3) &#8594; (2) &#8594; Test (3) &#8594; (5) <!-- .element: class="fragment" data-fragment-index="1" -->
### PO (5) &#8594; TDD (5) &#8594; Ops (5) <!-- .element: class="fragment" data-fragment-index="2" -->
### PO (5) &#8594; DevOps (8) <!-- .element: class="fragment" data-fragment-index="3" -->
Note:
- Getting information from one "pillar" to the next can take its own toll. That is why we have concepts such as TDD and DevOps
- Docker can definitely help us to get "real" DevOps, "Deployable becomes deliverable", due to the new abstraction layers such as Mesos

---

## Agile advantages
<br/>
### PO (5) &#8594; Test Driv Dev (5) &#8594; Ops (5)
### PO (?) &#8594; DevOps (8)
### PO (7) &#8594; DevOps (8) <!-- .element: class="fragment" data-fragment-index="1" -->
Note: 
- Is the DevOps step a win here?
- It has agile advantages.
-- Less risk due to RollBackability
-- Possibilities like A/B testing

---

## Observation 1
# Always keep the larger process in mind
Note: I have seen companies where technological enthusiasm holds back the whole process
