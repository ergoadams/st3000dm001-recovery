# st3000dm001-recovery  
Data recovery attempts on a Seagate st3000dm001 HDD.  
  
**DISCLAIMER**: This is just a learning process and documentation for myself. I'll probably never recover any data from the drive but I'm using the drive to experiment with different methods and to learn more about hard drives.  
  
## Backstory  
I have an old st3000dm001 HDD laying around that I got from a family member. The HDD apparently stopped randomly working years ago. Proffesional data recovery costs way too much and the data on there is not worth it, so I've been messing around with the drive on-off for years now.  
The drive does not make any noise and doesn't spin up when powered on.  
  
## Logic controller swap  
The first idea was to swap out the logic controller for a new one. Seems like some of my old links where I bought it from have stopped working since. It's a Rev B logic controller.  
The ebay post where I bought the logic controller from mentioned that I needed to swap the BIOS chip on the logic controller. This was done and the logic controller was swapped. Powering the driver resulted in the same outcome: no noises, no spinup.  

## Platter swap to a donor drive  
This might not have been the smartest step to do. I bought a new drive from Amazon. Didn't really pay attention to the serial number, firmware number etc. but definitely should have done that. I opened up the donor drive, carefully took out the heads and stored them in a plastic container. Took out the platter by hand without being too careful to see the build of the drive. Then took out the heads from the data recovery drive, but did not try to seperate the heads and store them nicely. Probably should have done that, as I did not see any damage on the heads when taking them out. Could have head swapped the donor drive later if needed. I put as much transparent tape on the sides of the platter as possible to secure them. Lifting the platter was quite a pain, cause the tapes were not symmetrical and I had to lift them more on one side than the other. This made the platters lock up in the case. I think I did a decent enough job lifting them and they did not move out of sync. Once the platters were put in the donor disk I reinstalled the heads that I carefully stored and assembled the drive again. However, for the first attempt I replaced the donor disk's logic board with the one from the data recovery drive. Powering the drive resulted once again in the same outcome of no noises nor spinup. Swapping the donor drive back to it's own logic board made the disk spin up.  
The drive then processeeded to move the heads back and forth, making some clicking noises. These noises are not the way you hear in videos showing the clicking heads problem. There were a couple of clicks and then the drive powered down. The position of the drive seemed to affect the number of clicks and the time between clicks. I opened the drive up a couple of times again, but managed to bend one of the heads. Hopefully the heads did not come in contact with the platters.  
  
## Future ideas  
If I can find a donor drive with a similar make and model I might try to swap the heads again. I also have some ideas to connect to the terminal of the drive and mess around there with some commands to see, if any data even exists on the drive. I also have ideas on eliminating one of the heads and trying to read data with the other ones. As of now I have no idea, if the head health checks and stuff can be disabled in the terminal of the HDD to allow something like that.  
All of this is such a janky and hacky solution, but I'm just experimenting and learning. The data is not valuable enough to take it seriously. This is just a learning process.  
