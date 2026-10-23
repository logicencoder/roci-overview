# Rocinante Explorer

![Rocinante Explorer prototype preview with simulated ship systems](assets/overview-2026-10-24.png)

*Prototype preview; ship systems are simulated.*

A command-deck interface can make space information more inviting to explore than a collection of unrelated numbers. Rocinante Explorer is a browser prototype that combines a fictional spacecraft dashboard with satellite, launch, crew and space-weather context when the connected feeds are available. It is an interactive visual experience, with a clear distinction between external observations and simulated ship systems.

## Tech stack

| Layer | Technologies |
|---|---|
| Interface | React; JavaScript; HTML; CSS |
| Charts and visuals | Recharts; SVG; Lucide |
| Orbital context | satellite.js |
| Project tooling | Vite; Tailwind CSS |

## Explore the bridge

The Bridge view brings a sensor grid, contact list and solar-system navigation display together. Selecting a contact opens its available details, making it easier to move from the overall display to a single object. Velocity charts and navigation readouts add context to the moving presentation.

## Bring space observations into the deck

When its supporting feeds are available, the prototype can show satellite observations, an ISS-based navigation position, a crew roster, space-weather information, upcoming launches and near-Earth-object context. These areas offer real-world material to explore within the fictional setting. Their availability depends on the connected feeds; animated displays alone do not establish that fresh observations have arrived.

## Inspect fictional ship systems

The Systems view groups propulsion, life support, weapons, shield condition and crew-vital displays. An integrity map, spectrum-style animation and sensor charts give the interface a consistent command-deck character. These ship readings and fictional contacts are simulated and are intended for exploration and entertainment.

## Follow the changing context

The operations feed can present available space-weather and launch information, while a simulated system log supports the fictional experience when that context is absent. This lets the prototype remain explorable without presenting every animated number as a real measurement.

## Understand this edition

This edition is an exploratory prototype, separate from [Rocinante Command Center](https://github.com/logicencoder/roci-command-center-overview), which has its own presentation. It demonstrates a particular visual and interaction direction; it is not a spacecraft control system or a claim of continuously verified live telemetry.

---

Private implementation: [roci](https://github.com/logicencoder/roci)

See [REPOS.md](REPOS.md) for related project links.

**[Logic Encoder](https://logicencoder.com)** · [GitHub](https://github.com/logicencoder) · [Contact](https://logicencoder.com/contact/)
