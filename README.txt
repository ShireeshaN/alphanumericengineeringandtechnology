ANET — Cinematic Banner Update

OPEN
Extract the ZIP and open ANET-Cinematic.html in Chrome or Edge.
This is the complete updated single-page HTML, based on your supplied file.
Three.js, reference images, styles and application scripts are embedded.
No npm install, server or CDN is required to view the page.

CHANGES
• Home, commercial, industrial and façade lighting: distinct modelled 3D scenes.
• Sequential light fade-ins, slow camera movement and a façade LED colour wave.
• Four lighting selectors in the hero; full lighting preview with brightness,
  replay and pause controls in the Lighting section.
• Automation: connected sensor / BLE mesh / gateway / Wi-Fi / edge control /
  actuator network with travelling data packets. No house in this scene.
• BMS + IoT: transparent multi-floor building, illuminated service routes,
  moving packets, scan layer and floating monitoring concept panels.
• Hero transitions and section previews, responsive layouts, reduced-motion
  support, offscreen animation suspension and WebGL context recovery.
• Fallback imagery/network diagrams when WebGL is unavailable.
• Existing navigation and other page sections are retained.

CONTROLS
The Lighting hero cycles through four scenes before the next banner.
Hovering/focusing the hero suspends automatic banner changes.
Select a hero banner or a lighting category manually at any time.
Each section has independent replay and motion pause controls.
The Lighting slider controls the model's illumination.
Reduced-motion system preferences keep the scenes static and illuminated.

SCOPE
These are procedural 3D interpretations of the reference images, not exact
photorealistic reconstructions. The BMS panels are illustrative, not connected
to live equipment. The automation graph represents configured integrations;
actual protocol compatibility depends on selected devices and gateways.

VALIDATION
Run: node scene-tests.cjs
Passed: script syntax, all six model constructors, finite geometry/transforms
at five animation times, illumination sequencing, brightness response and
façade colour animation. Structural checks cover embedded dependencies,
transition guards, context recovery hooks and lighting controls.

Browser/WebGL visual QA was NOT completed: no browser was preinstalled and
the Chromium download timed out. Mobile layout, GPU appearance and frame rate
still require checking in a real browser. No visual or performance pass is claimed.
