# Titan Windows Drivers and SDKs

**Native Windows tools and C++ SDKs for virtual devices, input control, networking, media and system diagnostics.**

Browse the [product catalog](https://licences.configcsa.com/portfolio/catalog),
then open a project's README for its supported scope, installation instructions
and validation. Public application/SDK source is available; driver source stays
private. Windows x64 is the target. Signing does not imply WHQL certification,
Microsoft endorsement or universal compatibility.

| Project | API or workflow | Availability |
| --- | --- | --- |
| [Virtual Network Adapter SDK](https://github.com/titanfyre/Virtual-Network-Adapter-SDK) | Exchange Ethernet frames between a native application and an independent virtual network adapter. | App/SDK preview; Microsoft signature pending |
| [Virtual Camera SDK](https://github.com/titanfyre/Virtual-Camera-SDK) | Supply raw BGR24 frames to an AVStream camera capture interface. | App/SDK preview; Microsoft signature pending |
| [HID Fixture Studio](https://github.com/titanfyre/HID-Fixture-Studio) | Build full-speed virtual HID fixtures from raw report descriptors. | Signed Vdevice demo bundle |
| [Scanner Route](https://github.com/titanfyre/Scanner-Route) | Route one selected keyboard scanner to a scan view or CSV. | Signed input demo bundle |
| [Input Replay Lab](https://github.com/titanfyre/Input-Replay-Lab) | Record and replay one selected keyboard or mouse for authorized QA. | Signed input demo bundle |
| [Input CI Runner](https://github.com/titanfyre/Input-CI-Runner) | Validate HID fixture JSON or run explicitly scheduled reports. | Signed Vdevice demo bundle |
| [Controller Repair Bench](https://github.com/titanfyre/Controller-Repair-Bench) | Inspect controller state, neutral noise and observed report intervals. | Signed input demo bundle |
| [Assistive Pointer](https://github.com/titanfyre/Assistive-Pointer) | Adjust one mouse's gain, axes and optional motion aggregation. | Signed input demo bundle |
| [Virtual Display Studio](https://github.com/titanfyre/Virtual-Display-Studio) | Connect an explicitly owned 1080p60 virtual monitor through an IddCx SDK. | Microsoft-signed evaluation bundle |
| [Titan Audio Link](https://github.com/titanfyre/Titan-Audio-Link) | Pair virtual playback/capture endpoints and transport known PCM fixtures. | Microsoft-signed evaluation bundle |
| [Titan Network Filter](https://github.com/titanfyre/Titan-Network-Filter) | Apply bounded IPv4/IPv6 connection rules with attributed decisions. | Microsoft-signed evaluation bundle |
| [ProcessGuard SDK](https://github.com/titanfyre/ProcessGuard-SDK) | Scope process-launch audit/deny rules to the SDK-owning application. | Microsoft-signed evaluation bundle |
| [Connection Trace Studio](https://github.com/titanfyre/Connection-Trace-Studio) | Observe WFP connection lifecycle metadata without packet content. | Microsoft-signed evaluation bundle |
| [Process Trace Studio](https://github.com/titanfyre/Process-Trace-Studio) | Receive bounded process/image lifecycle notifications. | Microsoft-signed evaluation bundle |
| [Storage I/O Flight Recorder](https://github.com/titanfyre/Storage-IO-Flight-Recorder) | Record disk read/write completion timing and status on the synthetic lab disk. | App/SDK preview; signature pending |
| [Virtual Storage Fault Lab](https://github.com/titanfyre/Virtual-Storage-Fault-Lab) | Exercise storage software against deterministic errors on a RAM-only lab disk. | App/SDK preview; signature pending |
| [Driver Readiness Inspector](https://github.com/titanfyre/Driver-Readiness-Inspector) | Export read-only PnP, service and signing evidence for support. | Ready utility; no added driver |
| [Titan File Filter](https://github.com/titanfyre/Titan-File-Filter) | Prototype scoped file access policies and audit events. | Preview; Microsoft altitude and live qualification pending |
| [File Trace Studio](https://github.com/titanfyre/File-Trace-Studio) | Inspect selected-process file-operation results and callback intervals. | Preview; Microsoft altitude and live qualification pending |
| [RegistryGuard](https://github.com/titanfyre/RegistryGuard) | Prototype scoped application registry write audit/deny rules. | Preview; Microsoft altitude and live qualification pending |
| [Virtual COM Workbench](https://github.com/titanfyre/Virtual-COM-Workbench) | Prototype a virtual USB CDC serial cable and loopback. | Source preview; live COM transport not validated |
| [Serial Device Simulator](https://github.com/titanfyre/Serial-Device-Simulator) | Test serial software with Modbus RTU and limited SCPI scenarios. | Source preview; live COM transport not validated |

## Try a product

Download a project's complete release ZIP, extract it and follow its README.
Install a driver only when that release actually includes a verified signed
setup. Restart Windows only if the installer requests it. Engineering previews
include user-mode tools and clear pending work; they contain no unsigned driver
or lab certificate. A labelled offline UI preview is not a live device test.

The six original input tools use separate signed one-hour evaluation drivers.
Virtual Display, Audio Link and the diagnostic/control evaluations have their
own documented terms and limits. Do not assume one driver's activation key or
evaluation behavior applies to another project.

Virtual Network Adapter SDK and Virtual Camera SDK use product-specific keys
and signed per-session permissions. These permissions last at most one hour
after acceptance and can be renewed while the key is enabled. Disabling a key
refuses new grants; already-issued permissions remain usable until expiry,
including their short challenge window. Keys are not bound to one machine.
Their installable packages remain pending until Microsoft signing returns.

## OEM integration and support

Add **`titancsa` on Discord** and name the project, Windows versions, intended
workflow and deployment scope. Evaluation access, a scoped integration pilot,
production/OEM redistribution rights and maintenance are agreed directly with
the owner. The single-login administration manages customers, orders,
product-specific keys and authorization statistics. There is no integrated
payment collection or guarantee of revenue, compatibility or zero defects.

Free alternatives exist in these categories. The commercial offer is a defined
integration API, targeted qualification, deployment assistance and support.
Read each project's technical limits and license before choosing it.

## License and measurements

Public applications and SDKs are MIT licensed except where retained third-party
notices say otherwise. Private driver binaries have separate terms. Microsoft
sample portions retain their notices and license rights.

Report intervals, software link speeds and callback timing describe their stated
boundary; they do not establish physical latency or throughput. Use only on
systems you own or administer with permission and comply with applicable law.
No unlawful or unauthorized use is endorsed. Software is supplied without
warranty; mandatory statutory rights and non-excludable liability remain
unaffected.
