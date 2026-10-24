# Titan Windows Driver Tools

**Windows driver tools and native SDK examples for device testing, network/process/file diagnostics, OEM integration and support.**

Browse the [project catalog](https://licences.configcsa.com/portfolio/catalog).
Choose the project and check its readiness below. Ready releases include their
own installation instructions; source previews clearly identify pending work.
Restart Windows only if a driver installer requests it.

| Project | What it does | Driver |
| --- | --- | --- |
| [Scanner Route](https://github.com/titanfyre/Scanner-Route) | Assemble scans from one selected US-layout keyboard scanner and optionally suppress its typing or append scans to CSV. | Interceptor Keyboard & Mouse |
| [HID Fixture Studio](https://github.com/titanfyre/HID-Fixture-Studio) | Build one full-speed virtual HID interface from a raw report descriptor and send exact reports. | Vdevice |
| [Input Replay Lab](https://github.com/titanfyre/Input-Replay-Lab) | Record one selected keyboard or mouse, inspect its timeline, and replay it for authorized desktop QA. | Interceptor Keyboard & Mouse |
| [Controller Repair Bench](https://github.com/titanfyre/Controller-Repair-Bench) | Inspect controller axes, observed neutral drift/noise, button fields and report intervals; export repair reports. | Interceptor Gamepad & Controller |
| [Assistive Pointer](https://github.com/titanfyre/Assistive-Pointer) | Adjust one mouse's gain, axis restriction, optional small-motion aggregation and repeated-click filtering. | Interceptor Keyboard & Mouse |
| [Input CI Runner](https://github.com/titanfyre/Input-CI-Runner) | Validate HID fixture JSON offline or explicitly run scheduled reports and export enqueue observations. | Vdevice |
| [Driver Readiness Inspector](https://github.com/titanfyre/Driver-Readiness-Inspector) | Read-only Windows device, service and signing evidence; export local HTML/JSON support reports. **Ready utility.** | No additional driver |
| [Virtual Display Studio](https://github.com/titanfyre/Virtual-Display-Studio) | Explicitly owned 1080p60 virtual monitor control SDK. **Configurator/source preview; signing and GPU runtime tests pending.** | Separate private UMDF/IddCx package |
| [Virtual COM Workbench](https://github.com/titanfyre/Virtual-COM-Workbench) | USB CDC serial cable and loopback prototype. **Engineering source preview; live COM startup remains unresolved.** | Vdevice |
| [Serial Device Simulator](https://github.com/titanfyre/Serial-Device-Simulator) | Modbus RTU and limited SCPI protocol simulator. **Engineering source preview; live COM transport is not validated.** | Vdevice |
| [Connection Trace Studio](https://github.com/titanfyre/Connection-Trace-Studio) | Observe IPv4/IPv6 connection lifecycle stages, process/endpoint metadata and bounded local diagnostics without packet capture or traffic modification. **Engineering preview; signing and runtime validation pending.** | Separate private WFP kernel sensor |
| [Process Trace Studio](https://github.com/titanfyre/Process-Trace-Studio) | Observe process creation/exit and optional image loads with process-start identities and a bounded native SDK. **Engineering preview; signing and runtime validation pending.** | Separate private kernel notification sensor |
| [File Trace Studio](https://github.com/titanfyre/File-Trace-Studio) | Inspect one selected process's file-operation counts, completion results and observed pre/post intervals without file paths or contents. **Offline preview; altitude allocation, signing and runtime validation pending.** | Separate private filesystem minifilter |
| [Titan Audio Link](https://github.com/titanfyre/Titan-Audio-Link) | Pair virtual playback/recording endpoints, stream PCM through a small C++ SDK and compare deterministic stereo audio fixtures. **Engineering preview; Microsoft signing and further Windows validation pending.** | Separate private PortCls/WaveRT audio driver |

The applications are native **C++17 for Windows 10/11 x64**. Their application
source is **MIT licensed**. User-mode SDK notices are included in each project.
The matching drivers are **closed source** and supplied under separate
binary terms. Microsoft signing applies to the driver packages; it does not
certify these applications or guarantee universal hardware/game compatibility.

## Evaluate or deploy commercially

The six original input tools include a matching signed **one-hour demo driver**
and installation instructions in their releases. The allowance is shared by applications using that
driver edition. A genuine Windows **Restart** starts another evaluation period;
reinstalling or closing an app does not reset it. The application source itself
has no additional application-layer paywall.

Driver Readiness Inspector needs no additional driver, license activation or
timer. Virtual Display Studio currently provides a configurator preview without
an installable driver. The two serial projects publish source and offline tests;
usable serial binaries are withheld until a real COM roundtrip passes. Their
offline protocol checks do not establish working Windows transport.

Connection Trace Studio, Process Trace Studio and File Trace Studio provide
separate diagnostic driver previews, each inactive until capture is explicitly
started. Their public application source and offline samples can be evaluated
now; live use requires their own signed, validated package. File Trace Studio
also requires a genuine Microsoft minifilter altitude allocation before an
installable package can be generated. These previews have no enforced demo
timer, online activation or integrated payment system. They are not antivirus,
EDR, traffic-control or durable audit products.

Titan Audio Link provides an audio routing/QA application and SDK preview. Its
private audio driver incorporates Microsoft sample components under MS-PL,
with retained notices. An installable signed driver is not yet included in its
public ZIP. Paid integration, branding and audio QA/support are separately
scoped engagements; no online activation or timed trial is implemented.

For an unrestricted production-driver bundle, OEM deployment, integration or
support, add **`titancsa`** as a friend on **Discord** and mention the project,
your Windows version and your intended workflow. Commercial terms are agreed
directly with the owner. A production driver uses its separate licensed SDK and
activation tools; demo and production driver identities are distinct.

For the three diagnostic previews, paid OEM redistribution or support is a
separately agreed engagement after the required technical validation; an
existing input-driver activation key does not activate these new drivers.

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
