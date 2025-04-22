## ⚖️ **Severity vs Priority**

| **Aspect**       | **Severity**                                      | **Priority**                                      |
|------------------|---------------------------------------------------|---------------------------------------------------|
| **Definition**   | Measures **how serious** a defect is              | Measures **how soon** a defect should be fixed    |
| **Focus**        | Impact on **functionality/system performance**    | Impact on **business goals/user needs**           |
| **Set By**       | **Tester / QA Team**                              | **Project Manager / Business Analyst / Developer**|
| **Represents**   | **Technical** importance                          | **Business** urgency                              |
| **Fixing Order** | Depends on **how badly** it breaks the system     | Depends on **how fast** it needs resolution       |
| **Example 1**    | App crashes on login → **High Severity**          | Fix immediately → **High Priority**               |
| **Example 2**    | Typo in homepage → **Low Severity**               | Branding issue → **High Priority**                |
| **Example 3**    | Non-functioning FAQ button → **Medium Severity**  | Less used → **Low Priority**                      |

---

### 💡 A Defect can be:

- **High Severity, High Priority**  
  A critical defect in a core feature with no workaround—must be fixed immediately.  
  *Example:* Production checkout flow crashes, blocking all orders.  

- **High Severity, Low Priority**  
  A show‑stopper in a seldom‑used or non‑critical area—can defer until the next cycle.  
  *Example:* Reporting dashboard in the admin portal fails, but customers aren’t affected.  

- **Low Severity, High Priority**  
  A minor/UI glitch in a high‑visibility spot—business demands a quick fix.  
  *Example:* Typo in the homepage headline or broken link in a marketing email.  

- **Low Severity, Low Priority**  
  A trivial defect with no real impact—can be scheduled into a future backlog.  
  *Example:* Slight misalignment of an icon on the user settings page.

---