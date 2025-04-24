# 🔄 API Workflow

An API workflow describes how a client application interacts with a server through an API.

```mermaid
flowchart LR
  A[Client] -->|1. Request (GET/POST/PUT/DELETE)| B[API]
  B -->|2. Validate & Process| C[Server]
  C -->|3. Response (JSON/XML)| B
  B -->|4. Return Response| A
```

---

## Step-by-Step Explanation

1. **Client Sends Request**  
   - HTTP methods: `GET`, `POST`, `PUT`, `DELETE`  
   - Includes endpoint URL, headers, query parameters, and optional body.

2. **API Validates & Processes**  
   - Authenticates and authorizes the request.  
   - Validates input data and parameters.  
   - Executes business logic and orchestrates services.

3. **Server Generates Response**  
   - Processes the request (e.g., database queries, computations).  
   - Constructs a response payload (commonly JSON or XML).

4. **API Returns Response**  
   - Forwards the payload back to the client.  
   - Client consumes the data (e.g., updates UI, triggers workflows).

---

## Summary

The workflow can be summarized as:
```
Client → API → Server → API → Client
```

