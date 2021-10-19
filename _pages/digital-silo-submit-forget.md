---
permalink: /digital-silo-submit-forget/
title: Submit and forget pattern
---

The client applications would usually open a dedicated two-way WebSocket channel to start listening to the incoming events from Digital Silo before submitting grains' payloads. This real-time channel plays a crucial role in shaping the "submit & forget" pattern as the processing results may arrive promptly or significantly later.

Each client application subscribed to Digital Silo events identifies itself by a unique identifier across the board. Digital Silo utilizes this identifier to route the results back to the client application that originates the grain's payload.