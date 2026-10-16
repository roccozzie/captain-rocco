# Captain Rocco

a first-person jet cockpit flight simulator for a 3-year-old captain. you sit INSIDE a realistic jet cockpit on an iphone in landscape: press START ENGINES, the turbine spools up, the panel lights - and you fly. it cannot crash.

- **Live:** https://captain-rocco.vercel.app
- **Fly:** drag on the windshield to climb, dive, and bank - the horizon, the stick, and every gauge move together. let go and the jet levels itself. too low and it beeps and gently lifts on its own
- **Working cockpit:** draggable throttle with an afterburner detent, gear switch (three lights, clunk, rumble), lights switch (night-panel glow), radio (tower squelch and beeps), autopilot that flies level until you grab it, and a big red BARREL ROLL button
- **Live instruments:** artificial horizon, airspeed, altimeter, vertical speed, heading tape, moving-map MFD, sweeping radar - all reading the same flight model
- **Extras:** optional tilt steering (tap the gyro toggle and grant motion permission), portrait still plays with a rotate hint, grownup mute top-right
- **Tech:** one self-contained `index.html` - cockpit, world, and every sound (turbine, wind, clicks, radio) drawn and synthesized in code, no assets
- no fail states, no timers, no scores, no words to read

Third in the series: [Rocco's Garage](https://github.com/roccozzie/roccos-garage) (tire swapping) and [Wee Woo](https://github.com/roccozzie/wee-woo) (Ozzie's ambulances).
