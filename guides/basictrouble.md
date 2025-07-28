# Basic troubleshooting

First, you must establish what exactly is wrong. If this is a prebuilt, and it is still within warranty, try their support first. 
Their support is likely incopetent but you may as well try. 

This is intended to be for computers that were working, but now no longer work.

## My pc is crashing!

Well, crashing how?
The game/program closing? The displays go blank, but the pc stays on? The displays go blank and the PC turns off? Blue screen of death?

### Crashing programs: 

Gather any error codes provided by the program and search the internet. Unless its a brand new game, chances are someone else has had the issue you are having.
Worst case, if there are no error code provided, see if the program has log files. The location of them is somehting likely documented on google as well. 
Generally, verifying the integrity of the files helps. Other times, its the games fault. It just depends.


### The displays go blank, but the pc stays on

This is more often than not a GPU driver crash, especially if your graphics cards fans begin spinning very fast. It can also be overclocking related if that is something youve done, undo or dial back any existing overclocks.
Note: It's a good idea to download the new graphics driver before starting this process, and then once the process is done, disable Wi-Fi/Ethernet, and install the driver yourself. 
Windows will attempt to install a (usually) outdated driver. You may as well just install a clean and up to date version yourself. 
AMD and Nvidia do now have their own form of reinstaller, but DDU is the "tried and true" method. 


To resolve, [Intel](https://www.intel.com/content/www/us/en/support/articles/000091878/graphics.html) provides a neat, and to the point tutorial on how to use DDU/Display Driver Uninstaller. 
For step number 6, click the button for YOUR graphics card, not necessarily Intel. 


### The displays go blank and the PC turns off

This is likely a power issue, and could be a failing power supply. You can test this by running burn tests on the CPU and GPU at the same time, and see if this causes the PC to shut down.

Furmark + Prime95 linked [here](https://pc-gaming-wiki.github.io/#benchmarking--stress-testing). If nothing after 30ish minutes, it is likely still the power supply, but its much more illusive. 
You can try limiting the power of your GPU to see if that helps the power supply. This can be done with MSI afterburner usually. 


### Blue Screen of Death

Blue screens always provide a stop code. Google that. If it is driver related, it will provide a .sys file generally, reinstall that driver.
Blue screens are usually driver related, but sometimes things such as corrupt system files can cause it as well. Use [BlueScreenView](https://www.bleepingcomputer.com/download/bluescreenview/) to see what caused the error. Googling the stop code should bring you to microsofts documentation and should indicate where the issue lies. If you are getting several different errors, try finding a common denominator. A majority of the time, a driver issue is going to be the culprit, though not always. 
