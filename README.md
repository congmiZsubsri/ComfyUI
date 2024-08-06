# Codemeter Dongle Firmware Update
  
Licenses don't disappear from CM sticks. Please contact me by email. When you do so, please run CmDUST first (Start... All Programs... CodeMeter... Tools), and attach the resulting CmDustResult.log file to your mail. My address is my forum name here @ my avatar image .com
 
I'm trying to install my copy of SB but I can't get the CodeMeter software to install. Everything works fine until CM stick install gets stuck at a point where installation program says "Starting Services... Service: Codemeter Runtime Service" It stays in that point for a while and then interrupts the install saying that installation ended prematurely because of an error.
 
**DOWNLOAD … [https://onsowinmu.blogspot.com/?um=2A0TcD](https://onsowinmu.blogspot.com/?um=2A0TcD)**


 
EDIT: I managed to get it working by downloading the CodeMeter software straight from the CM's website. Apparently there's something between the version I have on the disk 4.0b and my OS or some other software on computer.
 
To do so, open your CM Control Center (while your dongle is plugged in), select the "License" tab and click on your dongle to select/highlight it. Next, check your firmware version on the righthand side, and in case it is below 2.02, click the "circular arrow" button to the right of it to perform a firmware update:
 
When I try to use the update to 2.0 firmware, it does a quick check and says I have the most current version, 1.18 and no need to update. Yes, I have installed the version 5.0 Codemeter updated firmware.
 
If it is a server message, it indicates that the web server has a problem - not your computer. I'll contact WIbu Support about it, but they are gone for the weekend. If the server doesn't "heal itself" help will have to wait until Monday.
 
WHY? WHY ME? LOL! Figures. Never had an issue with this process and now that 3.0 is out and it's the weekend, something happens. Though I'm curious why i'm the only one it happened too? Just saying....
 
- Make sure you have top level system admin access to the computer. If on a domain, and in a domain admin group, make sure the particular system is granting system admin status to domain admin group.

- Remove the CodeMeter runtime through the operating system control panel. If you find more than one installation of the CodeMeter runtime, remove them too. There should never be more than one installation of the CodeMeter runtime on any system or they will compete for the hardware.
 
Yesterday I removed my CM stick from my rig (where's it's plugged in 24/7) to use it on my laptop. Later when I plugged it back into my rig, the stick became hot to the touch. Now I cannot run SB and get the following:
 
Ouch, that sounds like the dongle got fried. The CodeMeter software is just showing the virtual container for the time limited licenses. Email Ssnake, and don't toss the faulty dongle as you'll probably have to mail it back to them.
 
I updated firmware to 2.02 and even uninstalled and reinstalled both CodeMeter and SB3.02. The Codemeter Webadmin shows that the CmContainer for ESIMGAMES is disabled. CodeMeter Control Center does list the CmStick and ESIMGAMES but do I need to activate it and create a license request or import one?
 
You received a replacement stick? Then it's empty, and you need a license ticket to re-apply the licenses that you bought in the past. Please contact me by email, if I haven't sent you the ticket already.
 
A firmware upgrade to the CodeMeter dongle might be necessary: try connecting the M2GO to a PC (in USB mode) and if that PC has the CodeMeter runtime installed (because it has ONYX installed, for example), open the CodeMeter Control Center and trigger the update:

 
Sprecher Automation has been notified of a vulnerability in the Wibu Systems CodeMeter User Runtime Software that allows code execution via a buffer overflow, which is potentially exploitable over the network depending on the installation. The vulnerability has a CVSS 3.1 score of 9.0.
 
The CodeMeter User Runtime software is used by SPRECON-V460 for software license protection. The issue has been fixed by Wibu Systems and a new version 7.60c of the CodeMeter User Runtime Software is available which fixes the vulnerability. On existing SPRECON-V460 installations, this runtime can be replaced/updated without having to update/reinstall the V460 system.
 
**Update 8 September 2023**
 In addition, the CodeMeter User Runtime is also used for licensing with SPRECON-Tools (SPRECON-E Service Program, SPRECON-E Designer, SPRECON-E PLC Designer, SPRECON-E Display Editor), but only if licensing is done via Wibu CodeMeter USB dongle and the SPRECON Licensing Driver Package is installed for this purpose.
 
An attacker who successfully exploits the CVE-2023-3321 vulnerability may cause the Data Hub to load and execute arbitrary code in an elevated context. This assumes that an attacker has access to a Windows machine where the Service Grid components are installed, and no application whitelisting or similar technologies are used to prevent execution of untrusted code. An attacker can place a tailored file containing the code to be executed onto the machine and modify a configuration file for the file of the attacker to be loaded.
 
An attacker who successfully exploits the CVE-2023-3323 vulnerability may cause the Service Engine to execute code that was not intended to be executed by the project engineer. This assumes an attacker has access to a system with the Engineering Studio, where the Service Engine is started, where the Engineering Studio does not compile or overwrite the Service Engine files and the Service Engine files are created in the default directory.
 
An attacker who successfully exploits the CVE-2023-3324 vulnerability may cause the Service Engine to deserialize file content using a method that is recognized as insecure, potentially leading to the Service Engine entering an unknown state or potentially causing the Service Engine to execute code.
 
A vulnerable firmware verification in the firmware of the SPRECON-E product range has been identified. Through physical access and hardware manipulation, an attacker might be able to bypass hardware-based code verification and thus inject arbitrary code.
 **Affected Product:**
 
The access vector is bound to physical device access. Hence, it is recommended to emphasize physical security controls. See general recommendations. Besides this, it needs to be taken into account that necessary hardware manipulation to fully exploit this vulnerability requires to put the device out of operation for several time; i.e. device status monitoring as usually applied in substation automation is an important measure to also detect potential attacks.
 
Sprecher Automation strongly recommends to emphasize security best practices in critical infrastructures such as e.g. measures according to ISO/IEC 27019. Hence, both network as well as physical access to OT devices need to be restricted to a minimum, while protecting and monitoring all access means. Also, engineering / remote maintenance infrastructure needs to be protected with high security in mind, as potentially sensitive configuration data or maintenance access credentials could be stored there.
 
In a coming firmware release, device owners will additionally have the ability to gain more control over these user accounts by not only being able to disable them, but also by setting individual credentials in case their usage is necessary. The maintenance user accounts are equipped with limited privileges and e.g. do not have access to stored keys in the device.
 
The software "SPRECON-E IEC 61850 Mapper" contains a reference to "log4j-core-2.11.0.jar" which might be detected by securiy scans due to CVE-2021-44228, causing respective alarms. The used implementation in our software does not allow exploitation of CVE-2021-44228 remotely or locally, as according to the actual knowledge about CVE-2021-44228 there is no possibility to inject individual/manipulated strings. That's why we still declare our products as not-affected. However, as we noted through numerous customer requests that respective security scans alarmed our software, and also we see that the risk-situation as well as exploit details about CVE-2021-4428 grow rapidly, we recommend the following:
 
Please also be aware: the "SPRECON-E IEC 61850 Mapper" software is only necessary for configuring IEC 61850 feature on SPRECON devices. It is not necessary for device operation as well as maintenance. Only during engineering, when creating the device's configuration files for IEC 61850, the software is in use.
 
With reference to the article published on April 3, 2020, with the title: "Risk assessment of saved SPRECON-E configuration data", security improvements were announced for the SPRECON-E control firmware version 8.64b. Sprecher Automation would like to announce this advisory and declare the missing security improvement in the previous versions as a vulnerability with CVE-2020-11496. Thanks to Gregor Bonney, employee of CyberRange-e at Innogy for the responsible communication and coordination of the publication after the available firmware update 8.64b.
 

 **Countermeasures:**
 From firmware 8.64b, an extended input validation is carried out (safe listing), which prevents maliciously injected commands. In addition, a cryptographic signature process was implemented for configuration files, which enables secure special solutions for customers. Sprecher Automation offers an updated version of the firmware, currently 8.64d, for customers through their customer advisors.
 a2f82b0cb4
 
