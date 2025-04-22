### ✅ What is Unit Testing?

**Unit Testing** is a type of software testing where **individual units or components** of a software are tested in **isolation** to ensure they work as intended.

---

### 🔍 Key Points:
- A **unit** refers to the smallest testable part of software, such as a function, method, or class.
- The goal is to **validate each unit’s correctness** independently before integrating it with other units.
- Typically performed by **developers** during the **development phase**.
- Uses **mock objects** to simulate interactions with external dependencies.

---

### 🛠 Common Tools:
- **Java:** JUnit, TestNG  
- **Python:** PyTest, unittest  
- **JavaScript:** Jest, Mocha  
- **C#:** NUnit, MSTest  

---

### 🧪 Example (JavaScript):
```javascript
function add(a, b) {
  return a + b;
}

test('adds 2 + 3 to equal 5', () => {
  expect(add(2, 3)).toBe(5);
});
```

---

### ✅ Benefits of Unit Testing:
- Catches bugs **early** in development
- Simplifies **debugging** and **refactoring**
- Enhances **code reliability**
- Encourages **modular design**

---

### 🚫 Limitations:
- Does not test **integration** or **system behavior**
- Requires writing **additional code** (test scripts)
- Maintenance overhead when the application logic changes frequently

---

> **Conclusion:** Unit testing is the foundation of quality software development. It ensures that each building block of your software functions correctly, making the entire system more stable and maintainable.