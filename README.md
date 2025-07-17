# Summer-69-does-not-add-elements-present-between-6-and-9-
Given a list of integers, return the sum of the numbers, excluding any section that starts with a 6 and ends with the next 9 (inclusive).
# 🌞 Summer 69 — Python Problem

## 🧠 Description

This is a classic Python coding exercise that focuses on **flag-based logic** and **conditional control flow**.

> 🔒 Given a list of integers, return the **sum of the numbers**, but **exclude** any section of numbers that starts with a `6` and ends with the next `9` (both inclusive).

- Every `6` is guaranteed to be followed by at least one `9`.
- There may be multiple such 6-to-9 blocks in the list.
- Only numbers **outside** these blocks should be considered in the final sum.

---

## ✅ Examples

| Input                            | Output | Reasoning                                         |
|----------------------------------|--------|---------------------------------------------------|
| `[1, 2, 3]`                      | `6`    | Nothing to ignore                                 |
| `[4, 5, 6, 7, 8, 9]`            | `9`    | Ignore 6–9 block: sum of 4 + 5                    |
| `[1, 2, 6, 99, 99, 9, 3]`        | `6`    | Ignore 6 to 9: only 1 + 2 + 3                     |
| `[2, 6, 2, 6, 9, 9, 3]`          | `14`   | One block ignored: add 2 + 9 + 3                 |

---

## 🧩 Concepts Used

- ✅ Boolean flags
- ✅ Looping and control statements
- ✅ Filtering ranges in lists

---

## 📂 File Structure

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/@Rahul2006MILLION/summer69.git
   cd summer69

