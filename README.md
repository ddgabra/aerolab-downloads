# AeroLab RC + FPV — Windows v0.8.0

1. Extract the whole ZIP into a folder on your computer.
2. Double-click **Open AeroLab.cmd**.
3. Connect your PS4 controller by USB and press a button. Keyboard controls also work.

For the highest graphics quality, use **Maximum Graphics.cmd**. This starts the
Forward+ renderer with Ultra detail, 8× MSAA, 125% render resolution, long-range
shadows, indirect lighting, reflections and volumetric atmosphere. A modern
dedicated gaming GPU is recommended; no particular GPU or frame rate is guaranteed.

Open Settings to choose Low, Balanced, High or Ultra. Aircraft detail, vegetation,
shadows, resolution, sky detail, sunlight and atmosphere can be adjusted separately.
If startup fails or the graphics are too slow, close the app and use
**Safe Graphics.cmd**. The ZIP is portable and the executable is not code-signed.

Select an aircraft and map, then choose **ENTER FLIGHT**. Airplanes and quads arm at zero throttle. A helicopter in **3D mode** arms at **50% collective** (zero blade pitch); let the rotor spool before increasing collective. Keyboard collective starts at 50%. A USB radio with a physical collective stick is preferable for 3D flying.

| Action | PS4 controller | Keyboard |
| --- | --- | --- |
| Throttle / helicopter collective | R2 | W / S |
| Motor cut | × to disarm | X (keeps helicopter collective) |
| Roll / pitch | Right stick | Arrow keys |
| Rudder / yaw | Left stick left / right | A / D |
| Arm / disarm | × | Space |
| Reset | ○ | R |
| Camera | △ | C |
| Hand launch | R1 | H |
| Flaps / brakes | □ / L2 | F / B |
| Menu | OPTIONS | Escape |

Ten RC airplanes, two FPV drones and two 3D helicopters are included. Aircraft setup changes are stored
per aircraft. The ground operator, onboard and chase cameras remain available.

Browser edition: https://aerolab-rc-fpv.vercel.app/
Downloads and updates: https://github.com/ddgabra/aerolab-downloads/releases

The desktop game works offline after extraction. Settings are saved under
`%APPDATA%\Godot\app_userdata\AeroLab FPV`.

Aircraft coefficients are generic RC estimates. Visual likeness and higher-quality
rendering do not establish measured real-world flight fidelity. See the included
asset notices and licenses for the Cessna by osmosikum, CC0 aircraft and scenery,
Poly Haven scans, and Godot Engine.


In **Settings → Flight**, set temperature, pressure, humidity, rain, wind and gusts. In the **Hangar**, construction changes mass, stiffness and strength as well as appearance; custom component masses remain authoritative. Keep flight realism high and lower scenery quality first on a modest computer. See **RELEASE v0.8.md** and **PHYSICS AND TESTING.md** for changes, checks and model limits.

Manual airplane flight returns the servos to their neutral rigging. For approximately level hands-off flight, use the cruise speed and throttle shown on the HUD, then use elevator trim for your loading and conditions. More power can still produce a climb. Assisted mode adds automatic leveling. R repairs crash damage and removes wreckage.
