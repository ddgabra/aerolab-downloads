# AeroLab RC + FPV — Windows v0.5.0

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

Select an aircraft and map, then choose **ENTER FLIGHT**. Arm at zero throttle.

| Action | PS4 controller | Keyboard |
| --- | --- | --- |
| Throttle | R2 | W / S, X to cut |
| Roll / pitch | Right stick | Arrow keys |
| Rudder / yaw | Left stick left / right | A / D |
| Arm / disarm | × | Space |
| Reset | ○ | R |
| Camera | △ | C |
| Hand launch | R1 | H |
| Flaps / brakes | □ / L2 | F / B |
| Menu | OPTIONS | Escape |

Ten RC airplanes and two FPV drones are included. Aircraft setup changes are stored
per aircraft. The ground operator, onboard and chase cameras remain available.

Browser edition: https://aerolab-rc-fpv.vercel.app/
Downloads and updates: https://github.com/ddgabra/aerolab-downloads/releases

The desktop game works offline after extraction. Settings are saved under
`%APPDATA%\Godot\app_userdata\AeroLab FPV`.

Aircraft coefficients are generic RC estimates. Visual likeness and higher-quality
rendering do not establish measured real-world flight fidelity. See the included
asset notices and licenses for the Cessna by osmosikum, CC0 aircraft and scenery,
Poly Haven scans, and Godot Engine.


See **RELEASE v0.5.md** for the new aircraft builder, graphics/realism sliders, two 3D helicopters, USB radio setup, and opt-in wing breakage and distance limits.
