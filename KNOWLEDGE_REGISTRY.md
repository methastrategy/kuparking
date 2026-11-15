# Knowledge Registry & Harness² Post-Flight Reflection

| What | Why | How | Scope |
| :--- | :--- | :--- | :--- |
| **Interactive 3D Perspective Map Mode without WebGL overhead** | Users desire an Apple/Google Maps-like 3D tilt and gyro feeling while retaining ultra-fast, zero-dependency, single-screen mobile responsiveness. | Use CSS 3D Transforms (`perspective: 1200px`, `transform-style: preserve-3d`) combined with subtle mouse/touch parallax (`rotateX`, `rotateZ`) on an SVG/DOM board, bypassing heavy Three.js/MapboxGL libraries. | Web Maps / Event UI |
| **Integrity of Realtime Parking Telemetry** | Displaying fabricated/mock remaining slot numbers confuses drivers and damages trust during live events. | Completely eliminate mock numbers; display verified official structural capacity (~289, ~192, ~150 slots) alongside true live operational status (Open/Warning/Full) controlled directly by field staff. | Telemetry / Event Ops |
