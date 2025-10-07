# Sketch

```
index.html
src/
├── state/
│ └── app.js            # Central Store - manages tasks, filters, presets
├── services/
│ ├── bin.js            # Public API Client - JSONBin/Google Sheets GET/POST
│ └── taskStorage.js    # Local Persistence - localStorage wrapper
├── ui/
│ ├── View.js           # Root View Manager - coordinates UI components
│ ├── Tasklist.js       # Task List Component - renders filtered tasks
│ ├── filterList.js     # Filter Component - preset selection UI
│ └── Taskitem.js       # Task Item Component - individual task display
├── routes/
│ └── router.js         # Router - manages URL query state (filter/preset)
├── engine/
│ └── chart.js          # Visuals - progress charts
└── utils/
     └── util.js        # ID generation, formatting helpers
docs/                   # pitch, roadmap, sketches, DoDs
│  ├─ pitch.md
│  ├─ roadmap.md
│  ├─ architecture\_sketch.md
│  ├─ endpoints.md / jsonbin\_schema.md
│  ├─ dod-sprint1.md / dod-sprint2.md / dod-sprint3.md
│  └─ media/
readme.md
