### Rafael Pupio Vieira

I spent ten years inside finance and operations — FP&A, budgeting, and management reporting
for a multi-sector group — and kept automating the parts that shouldn't have been manual.
The one I'm proudest of cut administrative processing time **35%**: I mapped the chain,
found the real bottleneck (cross-department reconciliation, not data entry), rebuilt it as
refreshable Power Query ETL pipelines auditable back to source, and trained the 8 people who
had to trust the output.

Now I build that kind of thing on purpose.

---

**[service-watchdog](https://github.com/RafaelPupio/service-watchdog)** · Python, stdlib only

A watchdog for services that have to stay up when nobody is watching. Repairs only what's
actually down, stays silent when everything is healthy, and reports outward so that a *dead
machine* still raises an alarm.

I wrote it after one of my own systems went down for **nine days** and told me nothing —
because every alert I had was running on the machine that was down.

**[purged-walkforward](https://github.com/RafaelPupio/purged-walkforward)** · Python, NumPy

Purged, embargoed walk-forward cross-validation for time series with overlapping labels.

The test suite demonstrates the problem rather than asserting it: on a random walk — data
with no signal in it by construction — shuffled K-fold scores **0.861** while honest
validation scores **0.646**. The README also documents where the method *doesn't* save you,
which is the part most implementations leave out.

**[ChurchChatBox](https://github.com/RafaelPupio/ChurchChatBox)** · Next.js, TypeScript, PostgreSQL

Full-stack application with session-based authentication, Neon serverless Postgres via
Drizzle ORM, and Vercel Blob storage.

---

**Python · TypeScript · SQL · Claude Code · Power Query**

Working languages: English (C2) and Portuguese (native).
US, EU (Italian) and Brazilian citizen — no sponsorship required in the US, EU/EEA or Brazil.

[LinkedIn](https://linkedin.com/in/rafaelpupiovieira) · rafaelpupio@gmail.com
