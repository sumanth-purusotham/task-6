# 🔐 Task 6 — Create a Strong Password & Evaluate Strength

## Objective
Test several passwords of varying complexity, evaluate their strength using password-check tools, and summarize best practices.

---

## Tested Passwords (examples provided by user)
1. `sumanth123`  
2. `Sumanth@1234`  
3. `S!um@nth#123`  
4. `!@##@!sum)(&*`

> **Important:** These are test examples only. Never use personal or production credentials when testing online password checkers.

---

## Evaluation Summary

| Password | Verdict | Notes |
|----------|---------|-------|
| `sumanth123` | Terrible | Name + common numeric suffix; cracked instantly by dictionary attacks. |
| `Sumanth@1234` | Bad | Capitalization and `@` help slightly, but still predictable. |
| `S!um@nth#123` | Weak | Symbol substitutions reduce security gains because base string is your name. |
| `!@##@!sum)(&*` | Weak–messy | Symbol repetition and `sum` substring reduces entropy; short overall. |

---

## Testing Tools
- Recommended (free) checkers: PasswordMeter, Kaspersky Password Checker.  
**Do not** paste real, used passwords into any online checker. Use generated examples only.

---

## Screenshots

screenshots/
├─ weak_sumanth123.png
├─ bad_Sumanth@1234.png

├─ weak_S!um@nth#123.png
└─ weak_symbols_sum.png


---

## Key Learnings & Recommendations
- **Never** use names or predictable words.  
- Prefer **length** (12+ characters) and **randomness**.  
- Use a **password manager** to generate and store unique 16+ character passwords.  
- Use **MFA** for all important accounts.  
- Use passphrases (4 random words ± symbol/number) for memorable but strong credentials.

---

## Example Strong Passwords (do not reuse verbatim)
- `paper-hawk-olive-mango!42`  
- `v9QpR4mB2zKf8xL!`  

---

## Submission
- Add this README and the screenshots to a GitHub repo.  
- Submit the GitHub link to the provided Google Form.
