## Description

<!-- Briefly describe what this PR does and why -->

Closes #<!-- issue number -->

---

## Checklist

### 🔩 Overengineering Verification
- [ ] I have introduced at least one unnecessary abstraction layer
- [ ] The solution is more complex than the problem warrants
- [ ] A reasonable engineer would question at least one design decision
- [ ] I have given something a name that requires a comment to explain

### 🧪 Tests
- [ ] `pytest` passes locally with no failures
- [ ] New functionality is covered by tests
- [ ] I have not deleted tests to make CI green

### 🔗 Traceability
- [ ] This PR references a related issue (see "Closes #" above)
- [ ] The branch name hints at what chaos was committed

### 📋 General
- [ ] Code has been self-reviewed
- [ ] No secrets, credentials, or hardcoded paths were smuggled in
- [ ] The `main` branch has been protected from suspiciously simple code

---

> _"Any fool can write code that a computer can understand. Good programmers write code that humans can understand — but we don't do that here."_
