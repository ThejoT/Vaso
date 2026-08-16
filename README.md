# Vaso

A sickle cell disease crisis companion app for Maya Johnson (HbSS genotype). Dark medical UI,
mobile-first, no backend — all data is mocked in React state.

## Tabs

- **Monitor** — simulated wearable feed (SpO2, heart rate, skin temp, HRV) with a "Simulate Crisis"
  button that ramps vitals into a vaso-occlusive crisis and triggers a full-screen alert.
- **Crisis** — quick-call actions, ACS risk banner, pain scale + location logger.
- **Card** — ER handoff card with live vitals, analgesia protocol, and a fullscreen mode for staff.
- **Care** — covered facilities, care team, and insurance details.
- **Log** — chronological crisis history with summary stats and a report export.

## Development

```bash
npm install
npm run dev      # start dev server
npm run build    # production build
```

Built with React, Vite, Tailwind CSS, and lucide-react icons.
