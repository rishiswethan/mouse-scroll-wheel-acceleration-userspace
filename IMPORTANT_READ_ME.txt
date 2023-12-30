Do not run the install-daemon.py file. This causes the trackpad to malfunction, and makes it so a python program get's started at boot every single time. This seems to be the cause of the issue.

Simply installing the necessary packages and running the below command works
python3.10 /home/rishi/mouse-scroll-wheel-acceleration-userspace/main.py --exp 1.0 --multiplier 1.6
