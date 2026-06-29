I just built a fully interactive Prior Authorization workflow simulator — entirely with Claude. No frameworks. No external libraries. Just one HTML file.

But the real learning wasn't the code.

It was what I discovered about the US healthcare system while building it:

→ 93% of PA requests are eventually approved — yet providers still wait days or weeks
→ Providers spend an average of 13 hours/week just on PA paperwork
→ The bottleneck isn't medical judgment. It's documentation friction.
→ Peer-to-peer review overturns denials 50–75% of the time — but most providers never use it

The simulator models the entire PA flow: patient intake → medical necessity evaluation → document collection → payer submission → approval, denial, pend, appeal, and peer review — all drag-and-drop, with educational explanations at every step.

What I learned about workflow design:
Complex processes become learnable when you break them into who owns each step. The three-lane model (Patient / Provider / Payer) made a confusing system immediately visual.
