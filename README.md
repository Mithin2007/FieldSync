# FieldSync
Offline-first industrial inspection PWA demo.

Run with `npm start`, then open http://localhost:4173.

Added capabilities: bundled English/Tamil/Hindi UI with persisted local selection; technician availability; admin direct assignment or local task publishing; available-inspection cards and detail; atomic local single-claim transaction; OPEN → CLAIMED → IN_PROGRESS → COMPLETED lifecycle; queue, audit, and local notification-ready state. Existing IndexedDB inspection workflow, Sync Center, conflicts, audit trail, and service-worker offline shell remain.

This is an honest browser-local MVP: no backend, production auth, push notification, real-time transport, or server claim arbitration. Offline devices only see previously synchronized tasks.
