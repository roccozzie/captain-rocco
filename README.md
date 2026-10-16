# Captain Rocco

a first-person COMMERCIAL airliner cockpit for a 3-year-old captain. you sit inside a 737-style flight deck on an iphone in landscape: press START ENGINES and the jet wakes up on the runway. take off, fly, land - it cannot crash.

- **Live:** https://captain-rocco.vercel.app
- **Airport cycle:** TAKE OFF rolls down the runway and the jet rotates and lifts off by itself around 140 kt (gear tidies itself up if you forget). in flight, the big LAND button lines the jet up, flies the approach past the red/white PAPI lights, touches down, rolls out, and celebrates with the arrival ding and confetti. then TAKE OFF is ready again
- **Fly:** drag on the windshield - but this is a heavy jet now: deep smoothing, bank capped near 22 degrees, gentle pitch, and it settles back to level when you let go. mashing produces a calm, wandering airliner
- **Working cockpit:** twin thrust levers (no afterburner - it's an airliner), twin yokes, gear lever with three honest lights, DING button (seatbelt chime + SEAT BELT sign), lights, radio (tower squelch), autopilot
- **View:** clean cruise - sky, one horizon, a sea of soft cloud tops below. the busy ground only shows near the airport, soft and simple
- **Live instruments:** PFD with attitude and speed/altitude tapes, ND nav display - all reading the same flight model (250 kt idle thrust to 480 kt full, cruise from 32,000 ft)
- **Sound:** rebalanced quiet - smooth fan hum, soft wind, runway rumble on the roll, mellow chime
- **Tech:** one self-contained `index.html` - cockpit, world, and every sound drawn and synthesized in code, no assets
- no fail states, no timers, no scores, no words to read

Third in the series: [Rocco's Garage](https://github.com/roccozzie/roccos-garage) (tire swapping) and [Wee Woo](https://github.com/roccozzie/wee-woo) (Ozzie's ambulances).
