# Full Stack Developer Technical Interview (Intermediate Level)

**Focus Areas**: Node.js, React, Databases, APIs, DevOps, FinTech  
**Duration**: 60-90 minutes  
**Format**: Live coding, system design, debugging  
**Difficulty**: Intermediate (Progresses to advanced)

---

## 🛠️ Core JavaScript & Node.js (12)
1. **Flatten Nested Object**  
   Implement a function to convert `{a: {b: 1}}` → `{'a.b': 1}`.

2. **Memory Leak Fix**  
   Debug and fix memory leaks in a closure-heavy code snippet.

3. **Express Middleware**  
   Write middleware to log request/response times in Express.js.

4. **Callback to Promise**  
   Convert a callback-based function to use async/await.

5. **API Retry Mechanism**  
   Implement retry logic for failed API calls (max 3 attempts).

6. **Event Loop**  
   Compare `setImmediate()`, `process.nextTick()`, and `setTimeout()`.

7. **Merge Sorted Arrays**  
   Optimally merge two sorted arrays into one.

8. **Event Emitter Leak**  
   Debug an EventEmitter memory leak.

9. **Singleton Pattern**  
   Implement a singleton in Node.js.

10. **Stream Processing**  
    Read a large file line-by-line using streams.

11. **Promise Swallowing**  
    Explain and fix silent Promise rejection.

12. **Rate Limiter**  
    Build a limiter allowing 100 requests/hour per IP.

---

## ⚛️ React & Frontend (10)
13. **Controlled Form**  
    Build a payment form with validation.

14. **Re-render Optimization**  
    Optimize a component re-rendering unnecessarily.

15. **Theme Toggle**  
    Implement dark/light mode with Context API.

16. **Pagination**  
    Fetch and display paginated API data with "Load More".

17. **Modal Component**  
    Create a reusable modal using React Portals.

18. **Custom Hook**  
    Track window scroll position with a hook.

19. **useEffect Debugging**  
    Explain why `useEffect` runs twice in StrictMode.

20. **Debounced Search**  
    Implement search with 300ms debounce.

21. **Error Boundaries**  
    Add error boundaries to a component tree.

22. **Class to Hooks**  
    Convert a class component to functional with hooks.

---

## 🗃️ Databases & Caching (8)
23. **Duplicate Transactions**  
    Write SQL to find duplicate payments.

24. **Query Optimization**  
    Optimize a slow MySQL query using `EXPLAIN`.

25. **Redis Cache-Aside**  
    Implement cache-aside pattern for payment lookup.

26. **Multi-Currency Ledger**  
    Design a schema for a transaction ledger.

27. **ACID Transaction**  
    Write a funds transfer transaction.

28. **MongoDB vs SQL**  
    Compare aggregations vs joins for reporting.

29. **Race Condition**  
    Debug a high-concurrency balance update.

30. **Indexing Strategy**  
    Set up indexes for `transactions` table.

---

## 🌐 APIs & Microservices (8)
31. **RESTful Design**  
    Design payment processing API endpoints.

32. **JWT Auth**  
    Implement signup/login flow in Express.js.

33. **OpenAPI Docs**  
    Document a funds transfer API with Swagger.

34. **CORS Debugging**  
    Fix CORS issues in a Node.js + React app.

35. **Request Validation**  
    Validate ISO 20022 payloads.

36. **gRPC vs REST**  
    Compare for microservice communication.

37. **Idempotency**  
    Prevent duplicate payment requests.

38. **API Security**  
    Secure against SQLi/XSS.

---

## ☁️ DevOps & Tools (6)
39. **Dockerfile**  
    Write for Node.js + React app.

40. **K8s Probes**  
    Configure liveness/readiness for payment service.

41. **CI/CD Pipeline**  
    Pseudo-YAML for Git-triggered tests.

42. **Docker Debugging**  
    Diagnose container crash from logs.

43. **Memory Monitoring**  
    Track Node.js microservice memory.

44. **NGINX Load Balancer**  
    Set up as reverse proxy.

---

## 💰 Banking/Payments (6)
45. **IBAN Validation**  
    Verify International Bank Account Numbers.

46. **Currency Conversion**  
    Implement with proper rounding rules.

47. **Transfer Retries**  
    Exponential backoff for failed transfers.

48. **SWIFT/BIC Regex**  
    Validate bank identifier codes.

49. **Idempotency Keys**  
    Explain with code example.

50. **Fee Calculation**  
    Compute fees based on amount/currency.

---

## 📊 Evaluation Criteria
| Category        | Weight |
|-----------------|--------|
| Correctness     | 50%    |
| Best Practices  | 30%    |
| Efficiency      | 20%    |

**Pro Tip**: Use platforms like CoderPad (live coding) and Excalidraw (system design).

> 🔜 **Next Level**: [Advanced Questions](#) (Distributed systems, Kafka, etc.)
