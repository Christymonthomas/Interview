# Full Stack Developer Interview (300 Questions)

**Focused Areas**:  
🔥 **Node.js (100)** | ⚛️ **React (80)** | 🗃️ **Databases (70)** | ☁️ **DevOps (50)**

---

## 🔥 Node.js (100 Questions)

### **Core Node.js (25)**
1. Implement a custom EventEmitter class  
2. Fix memory leaks in Express middleware chains  
3. Write a performance benchmark for HTTP servers  
4. Handle uncaught exceptions in async code  
5. Implement file watcher with fs.watch()  

### **Async Programming (20)**
6. Convert callback-based legacy code to async/await  
7. Implement Promise.any() polyfill  
8. Write a rate-limited API client  
9. Handle backpressure in streams  
10. Debug event loop starvation  

### **Express.js (15)**
11. Design RESTful routes for a banking API  
12. Implement JWT auth with refresh tokens  
13. Write CSRF protection middleware  
14. Handle file uploads with multipart/form-data  
15. Optimize Express app startup time  

### **Performance (20)**
16. Profile CPU bottlenecks with Clinic.js  
17. Implement clustering for multi-core utilization  
18. Optimize JSON serialization/parsing  
19. Reduce GC pressure in high-throughput apps  
20. Cache computed results with memoization  

### **Security (20)**
21. Sanitize user input against NoSQL injection  
22. Implement rate limiting by IP/user  
23. Secure HTTP headers with Helmet  
24. Validate JWT signatures with multiple keys  
25. Encrypt sensitive config values  

---

## ⚛️ React (80 Questions)

### **Core React (25)**
26. Optimize large lists with windowing  
27. Implement compound form components  
28. Debug useEffect dependency arrays  
29. Create a custom hook for WebSocket connections  
30. Lazy load routes with Suspense  

### **State Management (20)**
31. Normalize Redux store for API responses  
32. Implement undo/redo with Immer  
33. Share state between micro-frontends  
34. Persist state to IndexedDB  
35. Handle API error states globally  

### **Performance (20)**
36. Fix unnecessary re-renders with React.memo  
37. Analyze bundle with Webpack Stats  
38. Implement code splitting for routes  
39. Optimize images with lazy loading  
40. Reduce JavaScript main-thread work  

### **Testing (15)**
41. Mock API calls in Jest tests  
42. Test component interactions  
43. Generate coverage reports  
44. Visual regression testing  
45. E2E test auth flows  

---

## 🗃️ Databases (70 Questions)

### **SQL (25)**
46. Design schema for a payment ledger  
47. Optimize slow JOIN queries  
48. Implement row-level security  
49. Handle database migrations  
50. Set up read replicas  

### **NoSQL (20)**
51. Model 1:N relationships in MongoDB  
52. Implement transactions in CosmosDB  
53. Tune Cassandra for time-series data  
54. Design DynamoDB GSIs  
55. Set up Redis as LRU cache  

### **Performance (15)**
56. Diagnose N+1 query issues  
57. Optimize bulk inserts  
58. Partition tables by date ranges  
59. Analyze query execution plans  
60. Tune connection pooling  

### **Security (10)**
61. Encrypt PII at rest  
62. Audit sensitive data access  
63. Rotate credentials automatically  
64. Prevent SQL injection  
65. Mask data in logs  

---

## ☁️ DevOps (50 Questions)

### **Docker (15)**
66. Optimize multi-stage builds  
67. Secure container images  
68. Debug OOMKilled containers  
69. Manage secrets with Docker  
70. Set up health checks  

### **Kubernetes (20)**
71. Configure HPA for Node.js apps  
72. Set up network policies  
73. Implement blue-green deployments  
74. Manage cluster upgrades  
75. Monitor resource quotas  

### **CI/CD (15)**
76. Parallelize test execution  
77. Implement canary releases  
78. Secure pipeline credentials  
79. Generate SBOMs  
80. Rollback failed deployments  

---

## 🎯 Evaluation Criteria

| Category       | Weight | Focus Areas                          |
|---------------|--------|--------------------------------------|
| **Node.js**   | 35%    | Performance, Security, Async Patterns|
| **React**     | 25%    | State Mgmt, Performance Optimization |
| **Databases** | 25%    | Query Optimization, Data Modeling    |
| **DevOps**    | 15%    | Cloud-Native Patterns, SRE Practices |

**Pro Tip**: Use these platforms:  
- **CoderPad** (Live coding)  
- **Katelog** (Take-home assignments)  
- **LocalStack** (AWS emulation)  

> 🔜 **Next Level**: [Production-Grade Scenarios](#)
