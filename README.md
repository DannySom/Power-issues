<h1>Troubleshooting Power Issues</h1>
<p align="center">
<img width="750" alt="image" src="https://github.com/user-attachments/assets/88ff82b5-c98e-4a5e-94c5-ab62b1a910e5" />

</p>

This repository serves as a collection of knowledge base articles focused on identifying, troubleshooting, and resolving power-related hardware and system issues for Windows-based desktops and laptops.

<h2>🔥 Burning Smell 🔥</h2>

**Possible Causes or Root Issues:**
A burning smell usually indicates a serious hardware or electrical issue. Most commonly, the problem is a failing power supply, but it can also be caused by overheating components, damaged cables, or burned motherboard parts.

<ins>Fixes:</ins>

1.) Shut down the computer immediately and unplug the power cable from the wall outlet.
   - Do not attempt to continue using the system.

2.) Allow the computer to cool down, then carefully open the case. Try to identify where the smell is coming from by cautiously smelling near (but not touching):
   - The power supply unit
   - Power cables and connectors
   - The motherboard (look for burned spots, discoloration, or melted components)

3.) Inspect the inside of the case for visible damage such as:
   - Burn marks or scorch spots
   - Melted plastic connectors
   - Swollen or leaking capacitors
   - Excessive dust buildup blocking airflow

4.) Replace the necessary hardware components, starting with the power supply if it is suspected to be the source.
Do not reuse any components that show burn damage.

5.) Before powering the system back on, ensure all connections are secure and airflow is unobstructed.


<h2>💻 Blue Screen of Death (BSOD)</h2>

**Possible Causes or Root Issues:**
Faulty or incompatible device drivers, failing hardware (RAM, storage), corrupted system files, recent software or driver updates, or overheating components.

<ins>Fixes:</ins>

**1.)** Note the error information displayed on the screen. (e.g., MEMORY_MANAGEMENT, IRQL_NOT_LESS_OR_EQUAL).

**2.)** Restart the computer and check for recent changes. Determine if new hardware, drivers, or software were installed prior to the BSOD occurring.

**3.)** Boot into Safe Mode (if the issue persists).
   - Safe Mode loads minimal drivers and can help determine whether the issue is driver- or software-related.

**4.)** Check device drivers.
   - Update, roll back, or reinstall recently added or problematic drivers using Device Manager.

**5.)** Run system diagnostics and built-in repair tools:
   - Run Windows Memory Diagnostic to check for RAM issues
   - sfc /scannow to scan and repair corrupted system files
   - Run chkdsk to check the hard drive for errors

**6.)** Check for overheating or hardware failures.
   - Ensure fans are functioning and airflow is unobstructed
   - Reseat RAM and internal cables if safe to do so

**7.)** Apply Windows updates or uninstall problematic updates.
  - Install pending updates or remove recent updates if the BSOD began afterward.

**8.)** If the issue continues, as a last resort, use System Restore to revert to a known working state.


<h2>Computer Randomly Shuts Down</h2>

**Symptoms:**
Computer suddenly powers off without warning. This may happen during use, under heavy load, or shortly after startup. In some cases, the system may restart automatically.

**Possible Causes or Root Issues:**
Commonly caused by overheating, a failing power supply, unstable power delivery, or battery failure on laptops. In rare cases, motherboard or firmware issues may also be involved.

<ins>Fixes:</ins>

**1.)** Check if the computer feels excessively hot.
   - Listen for loud fans and inspect air vents to see if airflow is blocked by dust or placement.

**2.)** Verify that all fans are spinning properly (CPU fan, case fans, and power supply fan).
   - Clean dust from fans and vents using compressed air if necessary.

**3.)** Check the power source.
   - Ensure the power cable is firmly connected, test a different wall outlet or power strip, and avoid overloaded surge protectors.

**4.)** If this is a desktop, consider the possibility of a failing power supply.
   - Unstable or insufficient power can cause sudden shutdowns, especially under load.

**5.)** If this is a laptop, test whether the shutdowns occur only when unplugged. If so, the battery may be failing and may need to be replaced.

**6.)** Monitor system temperatures using BIOS tools or hardware monitoring software to confirm whether overheating is the cause.
   - BIOS may show the fan status and temperatures.

<h2>Overheating</h2>

**Symptoms:**
Computer becomes excessively hot, fans run loudly, and the system may slow down, shut down, or reboot unexpectedly.

**Possible Causes or Root Issues:**
Overheating is usually caused by poor ventilation, dust buildup, failing fans, dried or improperly applied thermal paste, or blocked airflow inside the case.

<ins>Fixes:</ins>

1.) Check if all fans are working properly (CPU fan, case fans, and power supply fan).
   - Ensure that dust is not blocking fan blades or air vents.

2.) Use a can of compressed air to blow dust out of the fans, vents, and heat sinks.
   - You may also use an electronics-safe vacuum. Do NOT use a normal household vacuum, as it can generate static electricity and damage components.

3.) Verify that airflow inside the case is unobstructed. Ensure cables are not blocking fans and that the computer is not placed in an enclosed or poorly ventilated area.

4.) If fans are working correctly and overheating continues, the issue may be related to the CPU heat sink or thermal paste.
   - Remove the CPU heat sink, carefully clean off the old thermal paste, apply a new, thin layer of thermal paste, and securely reinstall the heat sink.

5.) Monitor system temperatures after repairs using BIOS tools or hardware monitoring software to confirm the issue is resolved.


<h2>Unusual Noises </h2>

**Symptoms:**
Computer becomes excessively hot, fans run loudly, and the system may slow down, shut down, or reboot unexpectedly.

**Possible Causes or Root Issues:**
Overheating is usually caused by poor ventilation, dust buildup, failing fans, dried or improperly applied thermal paste, or blocked airflow inside the case.

<ins>Fixes:</ins>

1.) Check if all fans are working properly (CPU fan, case fans, and power supply fan).
   - Ensure that dust is not blocking fan blades or air vents.

2.) Use a can of compressed air to blow dust out of the fans, vents, and heat sinks.
   - You may also use an electronics-safe vacuum. Do NOT use a normal household vacuum, as it can generate static electricity and damage components.

3.) Verify that airflow inside the case is unobstructed. Ensure cables are not blocking fans and that the computer is not placed in an enclosed or poorly ventilated area.

4.) If fans are working correctly and overheating continues, the issue may be related to the CPU heat sink or thermal paste.
   - Remove the CPU heat sink, carefully clean off the old thermal paste, apply a new, thin layer of thermal paste, and securely reinstall the heat sink.

5.) Monitor system temperatures after repairs using BIOS tools or hardware monitoring software to confirm the issue is resolved.


<h2>🛑 Application Crashing / Not Responding</h2>

**Possible Causes or Root Issues:**
Application crashes are commonly caused by corrupted application files, incompatible or outdated software versions, insufficient system resources, conflicts with other applications, missing dependencies, or recent system or application updates.

<ins>Fixes:</ins>

1.) Confirm the issue with the user.
   - Identify which application is crashing and when it occurs.
   - Note any error messages.

2.) Close and restart the application.
   - Use Task Manager if the application is unresponsive.

3.) Restart the computer.

4.) Check for application and Windows updates.

5.) Verify system requirements and compatibility.

6.) Repair or reinstall the application if necessary.

7.) Check Reliability Monitor for crash details.
   - Open Reliability Monitor (View reliability history).
   - Review recent critical events related to the application.
   - Note faulting modules, timestamps, and related updates or installs.

8.) Review Event Viewer if additional details are required.
   - Check Application logs for error codes or related system events.

