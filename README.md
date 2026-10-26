### Rodrigo Barreto

Java and Oracle PL/SQL developer from Brazil, working on enterprise systems since 2020. I build AI tools for legacy modernization where deterministic code extracts the facts, and every AI step has to show its evidence before it counts.

[Portfolio](https://rodrigo1408.github.io) · [LinkedIn](https://www.linkedin.com/in/rodrigo-barreto-2b1ba6129/) · [Email](mailto:rodrigomendesbarreto@hotmail.com)

---

#### Featured projects

**LIMIAR** · Python, LangGraph, Claude · *private repository: walkthrough available on request*
A multi-agent platform that migrates Oracle Forms/Reports (exported as XML) to Java/Spring Boot. Eight specialist agents rebuild the business rules, design the target architecture and generate code. Anything the XML does not support is reported as missing, never guessed.
- Deterministic extraction before every AI step; eight validation layers with zero LLM calls
- **LIMIAR Maintenance:** agents investigate and fix queued bugs, but a PR opens only when 10 deterministic gates pass, and merge is always human
- Evidence: 3,057 tests passing on `master`, CI on every push, and a reproducible gate demo (9/9 scenarios: 1 legitimate fix passes, 8 unauthorized changes blocked)

**[llm-do-zero](https://github.com/rodrigo1408/llm-do-zero)** · Python, NumPy
A character-level language model built from scratch, with hand-written backpropagation, no autograd and no pretrained weights. Every gradient is checked against finite differences, and the five experiments are reproducible. Validation loss is 1.84 nats/token, against 2.39 for a bigram baseline. A Transformer is the next step.

#### What I work with

- **Backend:** Java, Spring Boot, REST APIs, JPA, Angular
- **Oracle and data:** PL/SQL, Oracle Forms and Reports, SQL tuning, PostgreSQL
- **AI engineering:** multi-agent systems (LangGraph, Claude), Claude Code agents, deterministic validation of AI output, neural networks in NumPy
- **Quality and delivery:** pytest, GitHub Actions, Git, Docker

#### Earlier Spring Boot practice projects

[api_ev](https://github.com/rodrigo1408/api_ev) · [api_atendimento](https://github.com/rodrigo1408/api_atendimento) · [gate-unlock](https://github.com/rodrigo1408/gate-unlock) · [api_semaforo](https://github.com/rodrigo1408/api_semaforo)
