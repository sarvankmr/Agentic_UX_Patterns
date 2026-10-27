# Agentic UX Patterns

IT Key Experts Hour · 27 October 2026 · Saravana Kumar S

A single-file HTML deck (`index.html`, Siemens Sans Pro embedded, no build step).

- Arrow keys / click right or left half of a slide to navigate · `D` flips Do / Don't in the demo · `N` opens speaker notes · `F` fullscreen
- Deploy on Vercel as a static site: framework "Other", no build command, output directory empty.

## Version 3

`v3.html` (served at `/v3`, assets in `v3-assets/`) is the 68-slide v3 deck, rebuilt from the v2 PowerPoint on the Siemens type and motion spec. Same controls as above. `index.html` (v1) is unchanged.

## Interactive pattern demo

`agentic-ux-demo.html` (served at `/agentic-ux-demo`) is a standalone Travel Copilot built on the Siemens Design Language AI UX components, demonstrating 16 Agentic UX patterns with the Agent Configuration Center and snappable pattern guide, activity trace and agent details panels. Open a pattern directly with `/agentic-ux-demo#3.2` (pattern number as the hash).

## Travel Copilot demo (guidelines and patterns)

`travel-copilot.html` (served at `/travel-copilot`) is the business-trip Travel Copilot demo: the eight Human-Agent Interaction guidelines grouped See, Steer and Protect, each with a GSAP guided spotlight tour, plus a Test tab that opens a short tour for each Agentic UX pattern. Built on the Siemens Design Language AI UX components.
