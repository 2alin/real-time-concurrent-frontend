# Real Time and Concurrent Alarm Control Frontend System

This project contains my proposed frontend architecture and analysis for a security control system that:

- Shows alarms in three different categories or stacks (Emergency, Non-Emergency, History).
- Although Emergency category is shown by default, user (or agent) can switch between categories.
- Emergency stack must reflect new alarms in < 1s delay.
- The stack is priority-ordered.
- Alarms can be processed by multiple agents.
- No polling. The solution must scale and avoid periodic backend queries.


## Proposed architecture

The proposed arhitecture can be found in the [design-memo.md](./design-memo.md) file.