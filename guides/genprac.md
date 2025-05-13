Maintence is not something that should be obsessed over, but kept in mind. Overdoing things can screw up your PC just as much as doing nothing (mainly with drivers). 

### General Maintence (Windows)
  - OS Maintence (CHKDSK/SFC/DISM)
    - `chkdisk c: /f /r /x` Note: this may take several hours depending on hardware, storage capacity of the C drive, storage type, and storage speed
    - Run CMD as admin, copy and paste `DISM /Online /Cleanup-Image /RestoreHealth` let it finish, and then `sfc /scannow`
    - This should be run after major updates, and *maybe* once a month or so
  - Temp Files
    - Windows has its own "Disk Cleanup" utility, allowing you to delete among other things, temp files
    - Similarly, check monthly or so. If you are running out of disk space (this can be harmful to SSDs) then you should probably upgrade the drive or move programs off it onto a secondary drive. External (USB) media is not reccomended, however will suffice if nothing else can be done.
  - Malware
    - Windows Defender is shockingly capable in its current state as an effective anti-virus for the average user. You dont really need a dedicated anti-virus, and you especially should not be paying for an antivirus, much less using active scanning.
    - Like social engineering and hacking, once again humans are the weak point in the security. Education is far cheaper, and better for PC performance than active scanning.
    - It is important to note that recently Microsoft has been (to some extent) poisoning Defenders results by marking harmless programs as harmful. This makes it exceptionally difficult for someone who doesnt know any better. The only thing that can be done is running the program against another Anti-Virus program like Malwarebytes, or uploading the programs main executable to a website like VirusTotal with the latter being ideal for cracked games. 
  
  - Drivers
    - For the love of god, do not use driver boosters, you dont need them
    - If there is nothing wrong with the computer, you do not need to update drivers (except the GPU driver). 
    - GPU drivers are the only driver that needs to be updated, how often you update is up to you. Newer GPUs should be updated more often, older cards are less likely to get beneficial updates and should only be updated if a new game release requires it.

### Things you should probably have. 
  - A spare USB drive

      Extremely helpful for troubleshooting and repairing/reinstalling the OS. Ventoy reccomended, MediCat optional - [Link](https://pc-gaming-wiki.github.io/#usb-booting--imaging)
      If you just want a windows recovery drive, 16GB is enough. For medicat, 32GB is likely the bare minimum. If you are buying a new flash drive, 64GB+ are likely within a couple dollars of smaller drives, and are generally more worth it. 
  - Compressed Air (Or an electric duster/air compressor if available)

      Generally a good idea to have for cleaning the PC and keyboard. Can be bought in store.
  - A backup target

      Anything or anywhere that isnt your computer. Google Drive, Mega, or an external hard drive are all good backups.
      Flash drives and sd cards should not be used as they are made of poor quality flash. All local media will suffer from "bit rot" if they go unsed for several months.
      Bit rot happens in SSDs that go unpowered as the voltage in the cells degrades due to internal resistance. With hard drives, a similar thing but with magnetism.
      A Network Attached Storage (NAS) can also store large amounts of data in a dedicated unit that uses a filesystem capable of mitigating bitrot. 
