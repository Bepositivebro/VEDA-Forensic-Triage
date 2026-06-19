
                                        VEDA v3.0 
( Volatile Evidence Decision Assistant  Police Forensic Acquisition Tool )

Problem Statement : - In many crime scene Police found digital device like Laptop in ON condition and there could be chance to get some evidence inside this device but if police call his computer expert there would be chance to erase volatile data after shutdown or battery low. So there should be  a easy system to acquisition of data from these device so that  police can easily use it . So I made a easy tool in pendrive – “ VEDA”. 

WHAT THIS TOOL DOES ?
VEDA is a data acquisition tool that collects volatile and persistent forensic evidence from a live computer and saves a detailed Excel report to this USB drive.

It is easily used by any police officers immediately . 

It collect all important data for investigation according to priority of erase (volatile).

It can collect 35 different categories like :
  - Running processes & network connections
  - Browser history, cookies, saved passwords
  - Shell command history
  - Crypto wallet files
  - Cloud credentials (AWS, GCP, Azure)
  - SSH keys & VPN/Tor artifacts
  - Deleted files (last 30 days)
  - Scheduled tasks & startup persistence
  - USB device history
  - Encryption evidence (LUKS, GPG, VeraCrypt)
  - Installed software (hacking tools flagged)
  - System & network logs
  - Clipboard contents
  - Media files inventory
  + Chain-of-Custody sheet auto-filled
HOW TO USE ON SCENE
STEP 1 — Plug USB into the seized computer
           Do NOT power off the computer first
           (RAM evidence is destroyed on shutdown)










STEP 2 — Double-click:  VEDA_Forensic_Tool
           (or VEDA_Forensic_Tool.exe on Windows)











STEP 3 — Enter Case Number and Officer ID, then click:
           [ START ACQUISITION ]
 
 
The tool runs for 2-5 minutes depending on system size.
           A progress bar shows each evidence category being collected.
           Report saves automatically to this USB drive as:
           VEDA_<CaseNumber>_<Date_Time>.xlsx







AFTER ACQUISITION
1. Eject USB safely
2. Open the .xlsx on your forensic workstation . 















PRIORITY ORDER — VOLATILE EVIDENCE (most urgent first)

  1. RAM memory          — LOST ON POWER-OFF
  2. Swap/hibernate      — destroyed on reformat
  3. Network connections — lost when network changes
  4. Clipboard           — overwritten by any copy action
  5. Browser sessions    — lost when browser closes
  6. Running processes   — lost on reboot
  7. VPN/Tor tunnels     — lost on disconnect

  Some Screenshots of acquisition data :
  
 
 
 
 
 
 
 
 
 


And many more 35 + Categories of data acquisition of data .







Future Scope : 
1 – I will make good GUI of this tools so that police can easily understand digital evidences.
2 – It will acquisition of deep data like deleted files, recover of deleted files etc .
 And many more as suggestion of yours ………………………………………..


--------------------------------------------------------------
LEGAL NOTICE
--------------------------------------------------------------
  For use only under lawful authority. All acquired data must
  be handled under formal chain-of-custody procedures.
  Unauthorised use is strictly prohibited.
==============================================================
