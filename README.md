<div align="center">

# SOHAIL ISLAM

### AI ENGINEER · AGENTIC SYSTEMS · LLMs

Building reliable AI systems that solve real-world problems.

**Agents · RAG · Evaluation · Guardrails · Optimization · Production**

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/heysohail22"><strong>LinkedIn</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="YOUR_RESUME_URL"><strong>Resume</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:sohelsilamblg01@gmail.com"><strong>Email</strong></a>
</p>

<br/>
<br/>

</div>

---

# 01 · HOW I BUILD AI SYSTEMS

> **Building an agentic system isn't just about connecting an LLM to a tool.**
>
> The real engineering challenge is making the system **reliable, measurable, safe, efficient, and production-ready.**

<br/>

<table>
<tr>

<td width="50%" valign="top">

## 01 · DESIGN

### Build the right system

I design AI workflows around the problem rather than around a specific model or framework.

- Stateful agent workflows
- Multi-agent orchestration
- Tool calling
- Context engineering
- Deterministic control flow
- Human-in-the-loop workflows

</td>

<td width="50%" valign="top">

## 02 · RETRIEVE

### Give the model the right context

Good generation starts with reliable information.

- RAG
- Corrective RAG
- Query routing
- Retrieval pipelines
- Vector search
- Grounded generation
- Retrieval evaluation

</td>

</tr>

<tr>

<td width="50%" valign="top">

## 03 · CONTROL

### Keep probabilistic systems predictable

Production AI needs boundaries around what the model is allowed to do.

- AI guardrails
- Prompt-injection protection
- PII protection
- Structured outputs
- Input / output validation
- Human approval gates
- Deterministic security checks

</td>

<td width="50%" valign="top">

## 04 · MEASURE

### Know whether the system actually works

I treat evaluation as part of the system, not an afterthought.

- LLM-as-a-Judge
- Faithfulness
- Answer relevance
- Route accuracy
- Automated evaluations
- Safety evaluation
- Regression testing

</td>

</tr>

<tr>

<td width="50%" valign="top">

## 05 · OPTIMIZE

### Make AI systems cheaper and faster

A working system is only the beginning.

- Token reduction
- Context optimization
- Model routing
- Prompt caching
- Latency optimization
- Model selection
- Inference optimization

</td>

<td width="50%" valign="top">

## 06 · DEPLOY

### Turn the system into a real product

AI systems need reliable infrastructure around them.

- FastAPI
- PostgreSQL
- Docker
- AWS
- REST / SSE APIs
- CI/CD
- Production monitoring

</td>

</tr>
</table>

---

# 02 · WHAT I OPTIMIZE FOR

<div align="center">

<table>
<tr>

<td align="center" width="20%">

### RELIABILITY

Correct  
Grounded  
Consistent

</td>

<td align="center" width="20%">

### SAFETY

Guardrails  
Validation  
Human Control

</td>

<td align="center" width="20%">

### COST

Less Context  
Less Tokens  
Better Routing

</td>

<td align="center" width="20%">

### LATENCY

Fast Retrieval  
Fast Tools  
Efficient Models

</td>

<td align="center" width="20%">

### EVALUATION

Measure  
Test  
Improve

</td>

</tr>
</table>

</div>

<br/>

<div align="center">

**Problem → Architecture → Evaluation → Optimization → Production**

</div>

---

# 03 · ENGINEERING OUTCOMES

<div align="center">

<table>
<tr>

<td align="center" width="16%">

## 85%

**TOKEN  
REDUCTION**

</td>

<td align="center" width="16%">

## 99.6%

**DATA  
FAITHFULNESS**

</td>

<td align="center" width="16%">

## 100%

**ROUTE  
ACCURACY**

</td>

<td align="center" width="16%">

## 74%

**INFERENCE COST  
REDUCTION**

</td>

<td align="center" width="16%">

## 95%+

**BOOKING  
SUCCESS**

</td>

<td align="center" width="16%">

## <200ms

**TOOL  
LATENCY**

</td>

</tr>
</table>

</div>

<br/>

> These numbers represent outcomes from the systems and evaluation benchmarks documented in my projects.

---

# 04 · PROBLEM → SOLUTION → RESULT

## Reducing AI Cost

### Problem

Large context windows and unnecessary model calls can dramatically increase inference cost.

### Approach

I reduced the amount of information sent to the model through:

- Relational schema pruning
- Dynamic context sizing
- Model routing
- Prompt caching
- Deterministic logic where an LLM wasn't necessary

### Result

**85% lower end-to-end query token consumption**

and

**74% lower inference token cost**

---

## Improving RAG Reliability

### Problem

Retrieval alone does not guarantee that an answer will be grounded in the retrieved information.

### Approach

I built a corrective retrieval architecture that can route queries between:

**Vector Search → Web Search → Direct LLM**

and evaluate the resulting response for groundedness and relevance.

### Result

**100% route accuracy across 27 evaluation benchmarks**

**87.0% groundedness**

**88.9% answer relevance**

---

## Controlling LLM Behavior

### Problem

LLMs are probabilistic, while production systems often require predictable safety boundaries.

### Approach

I added multiple layers of control:

- Prompt-injection protection
- Guardrails
- PII redaction
- Structured validation
- Deterministic security checks
- Human-in-the-loop approval

### Result

**100% safety / prompt-injection blocking in the reported evaluation**

---

## Making Voice Agents Fast

### Problem

Slow tool execution can break the flow of a real-time voice conversation.

### Approach

I built FastAPI webhook tools for real-time availability lookups and optimized the reservation workflow.

### Result

**<200ms tool execution latency**

with

**95%+ successful booking completion**
