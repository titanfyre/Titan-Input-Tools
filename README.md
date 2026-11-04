# Titan Windows Drivers and SDKs

**Native Windows tools and C++ SDKs for virtual devices, input control, networking, media and system diagnostics.**

<!-- full-version-contact:start -->
> [!IMPORTANT]
> **Full versions and commercial licensing**
>
> **Discord username: `titancsa`**
>
> Open Discord, choose **Friends > Add Friend**, enter **`titancsa`**, then send a direct message. Name the product you want and ask about its **full version without demo restrictions**, pricing and license / activation instructions.
<!-- full-version-contact:end -->

Browse the [product catalog](https://licences.configcsa.com/portfolio/catalog),
then open a project's README for its supported scope, installation instructions
and validation. Many projects publish application/SDK source; Latency Inspector
publishes downloads and documentation while keeping its application source private.
Check each project's own license, including retained upstream terms. Driver source
stays private. Windows x64 is the target. Signing does not imply WHQL certification,
Microsoft endorsement or universal compatibility.

| Project | API or workflow | Availability |
| --- | --- | --- |
| [Interceptor](https://github.com/TitanCSA/Interceptor) | Capture/remap supported physical keyboard, mouse and controller input through the original C++17 API. | Signed one-hour-per-kernel-boot driver demo |
| [Interceptor Keyboard & Mouse](https://github.com/TitanCSA/Interceptor-Keyboard-Mouse) | Select and remap supported physical keyboard/mouse sources. | Signed one-hour-per-kernel-boot driver demo |
| [Interceptor Gamepad & Controller](https://github.com/TitanCSA/Interceptor-Gamepad-Controller) | Capture/remap compatible physical controller input; protocol and transport support varies. | Signed one-hour-per-kernel-boot driver demo |
| [Vdevice](https://github.com/TitanCSA/Vdevice) | Create virtual USB devices from descriptors/reports, with keyboard, mouse and gamepad examples. | Signed one-hour-per-kernel-boot driver demo |
| [Browser Control SDK](https://github.com/TitanCSA/Browser-Control-SDK) | Control an owned persistent WebView2 browser from Python, JavaScript, C++ or local stdio MCP. | Complete MIT utility; no input driver or demo timer |
| [HID Access Control](https://github.com/titanfyre/HID-Access-Control) | Apply per-device rules to new user-mode opens of compatible controller collections; existing handles keep their access. | Signed demo bundle; see device/transport validation limits |
| [Cloud Files SDK](https://github.com/titanfyre/Cloud-Files-SDK) | Hydrate read-only placeholders from an explicitly selected local or application backend through Windows Cloud Files. | Microsoft-signed evaluation; complete UI/console installers |
| [Remote Workstation SDK](https://github.com/titanfyre/Remote-Workstation-SDK) | Pair a visible desktop host and viewer over pinned TLS with optional explicit control. | Microsoft-signed evaluation; complete UI/console installers |
| [USB-over-IP SDK](https://github.com/titanfyre/USB-over-IP-SDK) | Forward bounded control, bulk and interrupt transfers from a selected vendor WinUSB interface to a virtual USB controller. | Microsoft-signed evaluation; complete UI/console installers |
| [Changed Block Tracking SDK](https://github.com/titanfyre/Changed-Block-Tracking-SDK) | Obtain immutable changed-block bitmaps on the explicitly owned synthetic test disk. | Microsoft-signed evaluation; complete UI/console installers |
| [User-Backed Virtual Disk SDK](https://github.com/titanfyre/User-Backed-Virtual-Disk-SDK) | Serve an explicitly owned virtual disk's bounded block requests from a native application backend. | Microsoft-signed 0.1.1 bundle; UI/console installers |
| [USB Trace SDK](https://github.com/titanfyre/USB-Trace-SDK) | Collect bounded transfer records and payload excerpts at an explicitly selected USB device boundary. | Microsoft-signed 0.1.1 bundle; UI/console installers |
| [Packet Capture SDK](https://github.com/titanfyre/Packet-Capture-SDK) | Capture and transmit bounded Ethernet frames through one explicitly selected adapter. | Microsoft-signed 0.1.1 bundle; UI/console installers |
| [Network Emulation SDK](https://github.com/titanfyre/Network-Emulation-SDK) | Exercise selected application UDP IPv4 traffic with bounded loss and delay. | Microsoft-signed 0.1.1 bundle; UI/console installers |
| [Virtual Network Adapter SDK](https://github.com/titanfyre/Virtual-Network-Adapter-SDK) | Exchange Ethernet frames between a native application and an independent virtual network adapter. | Microsoft-signed evaluation bundle |
| [Virtual Camera SDK](https://github.com/titanfyre/Virtual-Camera-SDK) | Supply raw BGR24 frames to an AVStream camera capture interface. | Microsoft-signed evaluation bundle |
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
| [Storage I/O Flight Recorder](https://github.com/titanfyre/Storage-IO-Flight-Recorder) | Record disk read/write completion timing and status on the synthetic lab disk. | Microsoft-signed evaluation bundle |
| [Virtual Storage Fault Lab](https://github.com/titanfyre/Virtual-Storage-Fault-Lab) | Exercise storage software against deterministic errors on a RAM-only lab disk. | Microsoft-signed evaluation bundle |
| [Driver Readiness Inspector](https://github.com/titanfyre/Driver-Readiness-Inspector) | Export read-only PnP, service and signing evidence for support. | Ready utility; no added driver |
| [Titan File Filter](https://github.com/titanfyre/Titan-File-Filter) | Prototype scoped file access policies and audit events. | Preview; Microsoft altitude and live qualification pending |
| [File Trace Studio](https://github.com/titanfyre/File-Trace-Studio) | Inspect selected-process file-operation results and callback intervals. | Preview; Microsoft altitude and live qualification pending |
| [RegistryGuard](https://github.com/titanfyre/RegistryGuard) | Prototype scoped application registry write audit/deny rules. | Preview; Microsoft altitude and live qualification pending |
| [Virtual COM Workbench](https://github.com/titanfyre/Virtual-COM-Workbench) | Prototype a virtual USB CDC serial cable and loopback. | Source preview; live COM transport not validated |
| [Serial Device Simulator](https://github.com/titanfyre/Serial-Device-Simulator) | Test serial software with Modbus RTU and limited SCPI scenarios. | Source preview; live COM transport not validated |

## Language bindings and application examples

Choose a wrapper for the **matching driver edition**. These applications do not
make different driver APIs interchangeable, and their driver allowances are
shared with other applications using the same edition.

| Project | Use it for | Source and driver terms |
| --- | --- | --- |
| [AutoHotInterceptor](https://github.com/TitanCSA/AutoHotInterceptor) | AutoHotkey v1/v2 per-device keyboard/mouse subscriptions, with a portable launcher and input monitor; adapted from evilC/AutoHotInterception. | MIT wrapper changes and retained upstream notices; bundled stock AutoHotkey is GPL-2.0. Matching Keyboard & Mouse driver: private, one-hour-per-kernel-boot demo. |
| [node-interceptor](https://github.com/TitanCSA/node-interceptor) | Node.js 20+/TypeScript keyboard/mouse wait, receive and send bindings, adapted from Rami-Sabbagh/node-interception. Install the release TGZ from GitHub. | LGPL-3.0-or-later wrapper; MIT SDK/bridge notices. Matching Keyboard & Mouse driver: private, one-hour-per-kernel-boot demo. |
| [Interceptor MultiLang](https://github.com/TitanCSA/Interceptor-MultiLang) | Mixed physical input batches through Python, Node.js/TypeScript, .NET, Java, Go, Rust or a C ABI. | MIT user-mode source. Requires the matching combined Interceptor driver, not the split editions; one-hour-per-kernel-boot demo. |
| [Interception V2](https://github.com/TitanCSA/Interception-V2) | Use the original `interception_*` C SDK with a separate HID keyboard/mouse compatibility driver; validate existing applications individually. PS/2 is outside its documented scope. | Original SDK/sample licenses remain applicable; separately developed private V2 driver has its own one-hour demo terms. |
| [GamePad Remapper](https://github.com/TitanCSA/GamePad-Remapper) | Study a complete native controller remapper with IGC scripts, macros, script settings and live IN/OUT observation. | MIT application; private Gamepad & Controller driver, one-hour-per-kernel-boot demo, including live monitoring. |
| [Keyboard & Mouse Remapper](https://github.com/TitanCSA/Keyboard-Mouse-Remapper) | Build keyboard/mouse remaps and timed macros with editable IGC scripts and visual rules. | MIT application; private Keyboard & Mouse driver, one-hour-per-kernel-boot demo, including live monitoring. |
| [Curve Controller](https://github.com/TitanCSA/Curve-Controller) | Edit radial or separate-X/Y joystick response curves with presets, ten-point custom curves and JSON import/export. | MIT application; private Gamepad & Controller driver, one-hour-per-kernel-boot demo. Physical-controller support needs qualification. |
| [Cronus Interceptor](https://github.com/TitanCSA/Cronus-Interceptor) | Edit and run a documented subset of GPC source scripts in an independent native studio. Compatibility preview; not the official Cronus compiler or hardware. | MIT application; private Gamepad & Controller driver, one-hour-per-kernel-boot demo. Check unsupported language and hardware features. |
| [Virtual Mouse Input](https://github.com/TitanCSA/Virtual-mouse-input) | Learn virtual USB mouse descriptors, relative reports, clicks and wheels from a small complete C++ application. Relative counts are not guaranteed pixels. | MIT application/SDK; private Vdevice driver, one-hour-per-kernel-boot demo. |
| [Remote Device Control](https://github.com/TitanCSA/Remote-Device-Control) | Direct Windows remote desktop using Sunshine/Moonlight H.264 transport and Vdevice keyboard/mouse input. Requires an unlocked console desktop; no relay, audio, clipboard or gamepad forwarding. | GPL-3.0 combined application with retained dependency notices; separate private Vdevice driver, one-hour-per-kernel-boot demo on the host. |
| [Latency Inspector](https://github.com/TitanCSA/Latency-Inspector) | Inspect defined Raw Input, PresentMon and Windows tracing intervals, with an optional passive kernel probe. Software intervals are not physical input-to-photon measurements. | Proprietary application/installer/probe source. Public downloads and documentation; ask about production, commercial and OEM terms. |

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

Virtual Network Adapter SDK, Virtual Camera SDK, Packet Capture SDK, Network
Emulation SDK, User-Backed Virtual Disk SDK and USB Trace SDK use product-specific
keys and signed per-session permissions. These permissions last at most one hour
after acceptance and can be renewed while the key is enabled. Disabling a key
refuses new grants; already-issued permissions remain usable until expiry,
including their short challenge window. Keys are not bound to one machine.
The signed Virtual Network Adapter, Virtual Camera, Packet Capture, Network
Emulation, User-Backed Virtual Disk and USB Trace bundles include self-contained
UI and console setup executables. Each README describes its tested Windows
configuration and remaining compatibility limits.

## OEM integration and support

Cloud Files, Remote Workstation, USB-over-IP and Changed Block Tracking use a
separate per-product one-hour demo that starts with the first real operation in
each Windows boot. A commercial key passed to `Verification(key)` enables that
product until Windows restarts, without replacing its demo driver. Revocation
refuses future activations; it does not terminate an already authorized boot.
These keys do not enforce machine counts. Cloud Files and Remote Workstation use
public Windows APIs: their kernel gate governs the supplied implementation and
cannot prevent independent implementations or modifications to public source.

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

## Which physical-input edition?

| Existing or intended API | Matching project |
| --- | --- |
| `Get_Input_With_Timeout()` / `Send_Input()` for keyboard, mouse and compatible controllers | [Interceptor](https://github.com/TitanCSA/Interceptor) |
| The same API family for keyboard and mouse only | [Interceptor Keyboard & Mouse](https://github.com/TitanCSA/Interceptor-Keyboard-Mouse) |
| Controller-only capture/remapping | [Interceptor Gamepad & Controller](https://github.com/TitanCSA/Interceptor-Gamepad-Controller) |
| `Read()` / `Write()` with a move-only batch | [Windows Input Bridge](https://github.com/StrikeFound/Windows-Input-Bridge) |

Use matching SDK/driver/examples; these editions are not interchangeable just
by changing headers. Compare their validation scope and follow uninstall/restart
instructions before replacing overlapping filters. The separate keyboard/mouse
and controller-only editions can coexist as documented by their installers.

## Community feedback follow-up

[Feedback and changes (French)](USER-FEEDBACK.txt) keeps public source links,
plain explanations and the action taken or still being considered. Questions
and external device issues in this list are not necessarily bugs in these repos.
An unimplemented suggestion is not a release commitment.

## Other API editions

These repositories expose related input/device APIs. Choose the matching driver,
SDK and examples from one edition; consult its README for its own validation and
licensing. The links below do not imply that different editions are interchangeable.

| Repository | Documentation |
| --- | --- |
| Windows-Gamepad-Bridge | [README](https://github.com/StrikeFound/Windows-Gamepad-Bridge) |
| Windows-Gamepad-Filter | [README](https://github.com/titanfyre/Windows-Gamepad-Filter) |
| Windows-Input-Filter | [README](https://github.com/titanfyre/Windows-Input-Filter) |
| Windows-Keyboard-Mouse-Bridge | [README](https://github.com/StrikeFound/Windows-Keyboard-Mouse-Bridge) |
| Windows-Keyboard-Mouse-Filter | [README](https://github.com/titanfyre/Windows-Keyboard-Mouse-Filter) |
| Windows-Virtual-Devices | [README](https://github.com/titanfyre/Windows-Virtual-Devices) |
| Windows-Virtual-USB | [README](https://github.com/StrikeFound/Windows-Virtual-USB) |

## Catalog and community contribution

[Titan Input Tools](https://github.com/titanfyre/Titan-Input-Tools) is this catalog
and its public community-feedback follow-up. Together with the product tables
and API-edition links above, it references every public original project in the
TitanCSA and titanfyre accounts checked on 4 November 2026.

[TitanCSA/awesome-mcp-servers](https://github.com/TitanCSA/awesome-mcp-servers)
is a contribution fork of the community MCP server directory maintained upstream.
The Browser Control SDK directory contribution remains a [draft pull request](https://github.com/punkpeye/awesome-mcp-servers/pull/18469)
pending the relevant Windows setup qualification and maintainer review.
