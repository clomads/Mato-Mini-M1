[![Support me on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dclomads%26type%3Dpatrons&style=flat-square)](https://patreon.com/clomads)

# Mato Mini M1
A low wattage/highly capable home server project using a M1 Mac Mini - Software, External Hardware, 3D Printed Enclosure

Mato is my server's name and is a reference to and shortening of [Negro Matapacos](https://www.google.com/search?q=Negro+Matapacos) - RIP little dude

## Overview

### Wants/Needs
If you follow me at all, you may know that I live in a converted school bus powered by solar and lithium batteries. Here are my requirements for 24/7 running home server after having several poor experiences with other options including a Synology NAS, and two NAS builds using UNRAID:


- Low Power (under 30 watts - preferrably under 15/20 watts at idle)
- High potential for performance - should be able to handle decently complex tasks when asked to
  - Transcoding/Encoding of video projects
- Enough external or internal connections for spinny boi storage
  - Currently using 3x 2.5" 5tb USB-C HDDs & 1x 2tb NVME USB-C SSD
- Minimum Gigabit connection - potential to upgrade
- Allow me to remove cloud storage solutions and subscriptions and host locally
  - Full 3,2,1 Backup solution


### Specs

The M1 Mac Mini is a great balance of power and efficiency for use in an off-grid situation where one still has powerful computing needs. 

- M1 Mac Mini 16GB 
  - 1 GbE
  - USB-C to 4x USB 3.0 (unpowered but Thunderbolt ports provide up to 15w)
    - 3x 2.5" 5TB (USB-C via USB-A 3.0)
    - SD Card Reader
  - USB Google Coral TPU
 
### Storage Layout

  
  
## Software

Unfortunately, MacOS hasn't been used as a server platorm for a long time, so using it as such presents certain problems you won't run into on purpose built systems. On the flip side wsing a full operating system over a NAS solution like UNRAID or FreeNAS actually presents interesting opportunities, but finding the right software or setting it up in the right way for this situation can be difficult. Here is a list of software I currently have found to be the best solutions for my needs

#TODO

### Enclosure & DC Bypass

#TODO

I intend to create an enclosure that will hold the Mac Mini logic board and 3 or more of the 5tb portable hard drives I use for storage. There is also plenty of information on implementing a 12v DC buck converter so I'm not running it on my inverter to improve efficiency.


