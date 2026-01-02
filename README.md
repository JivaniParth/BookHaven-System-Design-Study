# BookHaven — System Design & Architecture Exploration

BookHaven is an online bookstore implemented using **multiple backend architectures** to explore **system design tradeoffs, data modeling decisions, scalability, and developer experience**.

This repository serves as the **central index and comparison hub** for all implementations.

The intent is not feature duplication — it is **architectural comparison**.

---

## Why Multiple Implementations?

The same problem domain (online bookstore) was implemented using different stacks to study:

- Relational vs NoSQL data modeling
- Backend scalability vs data integrity
- Development speed vs strict schema control
- System complexity vs maintainability

Each implementation emphasizes a **different engineering concern**.

---

## Implementations

### 1️⃣ Node.js + Express + MongoDB (Flagship)
🔗 https://github.com/JivaniParth/online-book-store-mongodb

**Primary focus**
- REST API design
- JWT authentication
- Scalable NoSQL schemas
- Admin + customer workflows

This is the **most complete and demo-ready** system.

---

### 2️⃣ Flask + MySQL
🔗 https://github.com/JivaniParth/online-book-store

**Primary focus**
- Relational schema design
- SQL joins and constraints
- Transactional consistency
- Backend clarity over flexibility

---

### 3️⃣ Recommendation Engine (Experimental)
🔗 https://github.com/JivaniParth/Recommandation-Model-for-online-bookstore

**Primary focus**
- Recommendation logic
- Data flow experimentation
- Service separation
- A/B testing foundations

This is a **supporting system**, not a full product.

---

## Architecture Comparison

| Aspect | Node + MongoDB | Flask + MySQL | Recommendation Engine |
|------|---------------|---------------|----------------------|
| Core Goal | Scalability & UX | Data Integrity | Personalization |
| Data Model | NoSQL | Relational | Hybrid |
| Flexibility | High | Low | Medium |
| Complexity | Medium | Medium | High |
| Production Readiness | High | High | Partial |

---

## Key Takeaways

- No architecture is universally correct
- Tradeoffs must be explicit
- Documentation is part of engineering
- Clear intent matters more than tool count

---

## Future Work
- Integrate recommendation engine into flagship app
- Add performance benchmarks
- Introduce caching and async processing

---

**Author:** Parth Jivani
