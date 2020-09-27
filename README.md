# WinOS
A very simple operating system, based on MikeOS. 

## How To

(For Linux)
To compile the project, go in root, and do
./build-linux.sh

To test the project, go in root, and do
./test-linux.sh

To install the operating system on a USB stick, go to root, and do 
./imgfile.sh 

WARNING: I am not responsible if you accidentally format your USB stick or any other portable devices. 
You downloaded this project for your own risk. 

imgfile.sh content
```
cd disk_images
dd if=mikeos.flp of=/dev/<your-device>
```
Change "<your-device>" to your own device name like dev/sdb
Again, use it at your own risk. 
  
# Credits
- MikeOS: http://mikeos.sourceforge.net/
- MikeOS Mirror: https://github.com/mig-hub/mikeOS
