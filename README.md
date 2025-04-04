# PostgreSQL Mastery Tracker – 20 Week Plan (30 min/day, 5 days/week)

---

## 📦 Stage 1: Foundations (Weeks 1–5)

### Week 1
- [ ] Read Chapters 1–2 of *The Art of PostgreSQL*
- [ ] Install PostgreSQL and explore `psql`
- [ ] Read Chapters 3–4 (joins, window functions)
- [ ] Create schema with related tables
- [ ] Write sample queries using joins and aggregates

### Week 2
- [ ] Read Chapters 5–6 (constraints, data modeling)
- [ ] Add constraints and defaults to schema
- [ ] Read Chapters 7–8 (views, CTEs)
- [ ] Practice writing views and CTEs
- [ ] Create `PL/pgSQL` functions

### Week 3
- [ ] Read Chapters 9–10 (JSONB, indexing)
- [ ] Add JSONB fields and run queries
- [ ] Create GIN, composite, and partial indexes
- [ ] Practice full-text search with `tsvector`
- [ ] Benchmark JSONB queries

### Week 4
- [ ] Read Chapters 11–12 (transactions, security)
- [ ] Practice transactions: BEGIN, COMMIT, ROLLBACK
- [ ] Add roles and permissions
- [ ] Create `SECURITY DEFINER` functions
- [ ] Install and use a Foreign Data Wrapper

### Week 5
- [ ] Skim final chapters for review
- [ ] Solve SQL problem set (e.g., LeetCode DB)
- [ ] Document your schema and design
- [ ] Practice backup & restore (`pg_dump`, `pg_restore`)
- [ ] Reflect on Stage 1 progress

---

## ⚙️ Stage 2: Performance & Tuning (Weeks 6–9)

### Week 6
- [ ] Read Ch. 1 – Install and configure PostgreSQL 16
- [ ] Set up PG16 locally and tune memory settings
- [ ] Read Ch. 2 – Monitoring performance
- [ ] Practice EXPLAIN ANALYZE, JIT, and parallel stats
- [ ] Use `pg_stat_statements`, `pg_stat_io`

### Week 7
- [ ] Read Ch. 3 – Autovacuum tuning
- [ ] Benchmark different vacuum settings
- [ ] Tune autovacuum thresholds
- [ ] Read VACUUM docs for PG16
- [ ] Measure table bloat before/after cleanup

### Week 8
- [ ] Read Ch. 5 – Indexing strategies
- [ ] Create composite, partial, and BRIN indexes
- [ ] Use `pg_stat_user_indexes` to analyze usage
- [ ] Read parallel query and sort docs
- [ ] Benchmark indexed vs non-indexed queries

### Week 9
- [ ] Read Ch. 6 – Performance tuning
- [ ] Simulate workload with `pgbench`
- [ ] Tune parallelism and JIT settings
- [ ] Tune for OLTP vs analytics workloads
- [ ] Log and analyze EXPLAIN plans for real schema

---

## 🧬 Stage 3: Internals & Source Code (Weeks 10–15)

### Week 10
- [ ] Read Ch. 1 of *The Internals of PostgreSQL*
- [ ] Build PostgreSQL from source
- [ ] Read Ch. 2 – SQL execution pipeline
- [ ] Trace a query using logs
- [ ] Read Ch. 3 – Planner internals

### Week 11
- [ ] Explore `src/backend/parser/`
- [ ] Read Ch. 4–5 – MVCC, buffer manager
- [ ] Explore heap storage in source
- [ ] Step through `heap_insert` with debugger
- [ ] Read Ch. 6 – WAL & recovery

### Week 12
- [ ] Explore `src/backend/access/transam/`
- [ ] Trace WAL creation through source
- [ ] Read Ch. 7 – Lock manager internals
- [ ] Trace locking behavior in debugger
- [ ] Study `src/backend/storage/lmgr/`

### Week 13
- [ ] Read Ch. 1–2 of *PostgreSQL Internals & Source Code*
- [ ] Study startup and memory context init
- [ ] Trace memory allocations in source

### Week 14
- [ ] Read Ch. 3–5 – Backend loop and executor
- [ ] Trace query execution path in debugger
- [ ] Print call stack from parse to plan to execute

### Week 15
- [ ] Write a UDF in C
- [ ] Build and register a PostgreSQL extension
- [ ] Create a minimal background worker
- [ ] Test and validate custom code

---

## 🧠 Stage 4: Expert-Level Work (Weeks 16–20)

### Week 16
- [ ] Join `pgsql-hackers` mailing list
- [ ] Track 1–2 open discussions
- [ ] Read and understand patch proposals
- [ ] Set up `cfbot` or build patches locally
- [ ] Pick 1 low-complexity issue to explore

### Week 17
- [ ] Explore existing extensions (e.g. `pg_trgm`, `pg_stat_statements`)
- [ ] Read extension source code
- [ ] Trace how it hooks into planner or executor

### Week 18
- [ ] Build a custom PostgreSQL extension
- [ ] Define a new function/operator or type
- [ ] Register and test the extension
- [ ] Document it like a real package

### Week 19
- [ ] Fork PostgreSQL source
- [ ] Modify planner, executor, or storage subsystem
- [ ] Log your changes and test them with `gdb`
- [ ] Write experimental feature (e.g., logging hook)

### Week 20
- [ ] Write a blog post or README on your work
- [ ] Publish your extension or forked feature
- [ ] Document lessons learned and next goals
- [ ] Reflect on the 5-month journey
