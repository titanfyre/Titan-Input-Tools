# Titan Input Tools

**Focused Windows input applications for testing, repair, automation and accessibility.**

Browse the [project catalog](https://licences.configcsa.com/portfolio/catalog).
Download a complete release ZIP from the project you need, install its matching
driver, and restart Windows only if setup requests it.

| Project | What it does | Driver |
| --- | --- | --- |
| [Scanner Route](https://github.com/titanfyre/Scanner-Route) | Assemble scans from one selected US-layout keyboard scanner and optionally suppress its typing or append scans to CSV. | Interceptor Keyboard & Mouse |
| [HID Fixture Studio](https://github.com/titanfyre/HID-Fixture-Studio) | Build one full-speed virtual HID interface from a raw report descriptor and send exact reports. | Vdevice |
| [Input Replay Lab](https://github.com/titanfyre/Input-Replay-Lab) | Record one selected keyboard or mouse, inspect its timeline, and replay it for authorized desktop QA. | Interceptor Keyboard & Mouse |
| [Controller Repair Bench](https://github.com/titanfyre/Controller-Repair-Bench) | Inspect controller axes, observed neutral drift/noise, button fields and report intervals; export repair reports. | Interceptor Gamepad & Controller |
| [Assistive Pointer](https://github.com/titanfyre/Assistive-Pointer) | Adjust one mouse's gain, axis restriction, optional small-motion aggregation and repeated-click filtering. | Interceptor Keyboard & Mouse |
| [Input CI Runner](https://github.com/titanfyre/Input-CI-Runner) | Validate HID fixture JSON offline or explicitly run scheduled reports and export enqueue observations. | Vdevice |

The applications are native **C++17 for Windows 10/11 x64**. Their application
source is **MIT licensed**. User-mode SDK notices are included in each project.
The matching kernel drivers are **closed source** and supplied under separate
binary terms. Microsoft signing applies to the driver packages; it does not
certify these applications or guarantee universal hardware/game compatibility.

## Evaluate or deploy commercially

The public releases include the matching signed **one-hour demo driver** and
installation instructions. The allowance is shared by applications using that
driver edition. A genuine Windows **Restart** starts another evaluation period;
reinstalling or closing an app does not reset it. The application source itself
has no additional application-layer paywall.

For an unrestricted production-driver bundle, OEM deployment, integration or
support, add **`titancsa`** as a friend on **Discord** and mention the project,
your Windows version and your intended workflow. Commercial terms are agreed
directly with the owner. A production driver uses its separate licensed SDK and
activation tools; demo and production driver identities are distinct.

## Understand the measurements

Report intervals, observed ranges and enqueue scheduling observations describe
their stated measurement boundary. They do not establish input-to-photon latency,
hardware certification or a repair diagnosis. Windows scheduling and device
behavior matter. Optional motion aggregation deliberately adds delay. Consult
each project's README for supported scope, limits and validation evidence.

Use these tools only on systems and with input sources you are authorized to
test or control. No illegal or unauthorized use is endorsed. Software is provided
AS IS subject to its license and applicable law; users remain responsible for
their actions. There are no guaranteed performance, compatibility or revenue
claims.
