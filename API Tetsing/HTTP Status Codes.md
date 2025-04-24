# 🚦 HTTP Status Codes (Detailed yet Concise)

HTTP status codes are three-digit numbers returned by a server to indicate the outcome of a client’s request. They’re organized into five categories:

---

## 1xx – Informational  
**Meaning:** Request received; continuing process.  
- **100 Continue** – Client may continue with request body.  
- **101 Switching Protocols** – Server is switching protocols as requested.

---

## 2xx – Success  
**Meaning:** Request was successfully received, understood, and accepted.  
- **200 OK** – Standard success response.  
- **201 Created** – New resource created (e.g., after POST).  
- **204 No Content** – Request succeeded but no body in response.

---

## 3xx – Redirection  
**Meaning:** Further action needed (often to follow a redirect).  
- **301 Moved Permanently** – Resource has a new permanent URL.  
- **302 Found** – Resource temporarily under a different URL.  
- **304 Not Modified** – Cached resource is still valid; no need to retransmit.

---

## 4xx – Client Error  
**Meaning:** Request contains bad syntax or cannot be fulfilled by client’s credentials.  
- **400 Bad Request** – Malformed request syntax or invalid parameters.  
- **401 Unauthorized** – Authentication required or failed.  
- **403 Forbidden** – Server understood request but refuses to authorize.  
- **404 Not Found** – Requested resource does not exist.

---

## 5xx – Server Error  
**Meaning:** Server failed to fulfil an apparently valid request.  
- **500 Internal Server Error** – Generic server-side failure.  
- **502 Bad Gateway** – Invalid response from an upstream server.  
- **503 Service Unavailable** – Server overloaded or down for maintenance.  
- **504 Gateway Timeout** – Upstream server failed to respond in time.

---

**Usage tip:**  
- **2xx codes** mean you’re good to go.  
- **3xx codes** tell your client to look elsewhere.  
- **4xx codes** signal client-side mistakes.  
- **5xx codes** warn of server-side problems.  
