<h1>Power Issues</h1>
<p align="center">
<img width="750" alt="image" src="https://github.com/user-attachments/assets/88ff82b5-c98e-4a5e-94c5-ab62b1a910e5" />

</p>

This repository serves as a quick reference point to resolve common Windows errors and performance issues. Each section will outline key symptoms, possible causes, and troubleshooting steps used by IT professionals to resolve them.

<h2>🔥Burning Smell🔥</h2>  


***Possible Causes or Root Issues:*** Something in the case is melting/caught on fire. More than likely, it's the power supply


<ins>Fixes:</ins> 

**1.)** Shut down the computer immediately.

**2.)** Try to smell inside the case where it's coming from. Smell the power supply.

Look at the motherboard and look for burned spots.

**3.)** Replace neccessary hardware components


<h2>🟦Blue Screen of Death (BSOD)🟦</h2>  

***Symptoms:*** Blue Screen errors with codes such as `MEMORY_MANAGEMENT`, `SYSTEM_SERVICE_EXCEPTION`, or `CRITICAL_PROCESS_DIED`.

***Possible Causes or Root Issues:*** Faulty drivers, hardware failure, or corrupted memory.  

<ins>Fixes:</ins> 

**1.)** Boot into **Safe Mode**.  

**2.)** Run the **Windows Diagnostic Tool**. `Windows+R` and type `mdsched.exe`->**Restart now** and check for problems, and run the test.

**3.)** Update or rollback the drivers in **Device Manager**

**4.)** Check for more malware or run the command in **Command Prompt** 
```bash
chkdsk /r chkdsk /f
```


**5.)** Also, try to run the command to repair corrupted Windows system files.
```bash
sfc /scannow
```

<h2>📉Sluggish Performance📉</h2>  

***Symptoms:*** System running extremely slow, taking a long time to boot, fans running loudly, disk usage stays at 100% in **Task Manager** 

***Possible Causes or Root Issues:*** Can happen due to a large number of reasons: Too many apps and programs up at once, background services, Not enough memory, Slow hard drive, Slow processor, Corrupt application, Not using the correct drivers


<ins>Fixes:</ins> 

**1.)** Restart the system and check **Task Manager**. `Ctrl+Shift+Esc`->select the **Processes** tab-> single out which apps are using high disk, CPU, or memory and end the tasks. 

**2.)** Disable Unecessary **Startup Apps**. Press `Ctrl+Shift+Esc` -> select the **Startup** tab->right-click and disable apps that are eating up too many resources and don't need to be automatically running. 

**3.)** Check the **Disk Health** by running the commands in **Command Prompt**
```bash
chkdsk /f
chkdsk /r
```
This scans for and repairs bad sectors on the drive that can cause performance slowdowns.

**4.)** If you're running on **HDD**, upgrade to **SSD** to boost and improve performance. 

 <h2>Overheating</h2>

 ***Symptoms:*** Computer gets too hot, may also shut down or reboot

***Possible Causes or Root Issues:*** Generally happens due to poor ventilation


<ins>Fixes:</ins> 

**1.)** Check is all fans are working. Sometimes dust may get into the fan. 

**2.)** Get a can of compressed air, point it at the fan and blow it out. You can also use an electronic vacuum, NOT a normal vacuum.

**3.)** If the fan and everything else is working fine, it's probably the heat sink on the processor not working. Take off the processor, scrape off the thermal paste, apply new thermal paste and put it back on.



