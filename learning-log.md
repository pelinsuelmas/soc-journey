# 📓 Learning Log — My SOC Journey

A short log of the rooms I complete and what I learn along the way.
Goal: track my progress and show consistency over time.

---

### Nov 9, 2026 — TryHackMe: Intro to Defensive Security
Completed my first defensive security room. On a security dashboard (Security Hub) I spotted a critical alert,
investigated the pages the attacker tried to reach (admin / login / backup), and found the most recent attempt was `/admin`.
I then responded: blocked the attacker's IP address and deployed protective controls.
The threat was stopped before it reached anything sensitive.

**What I learned:** the detect → investigate → respond workflow, and the idea of layered defense
(block first, then harden the system).
