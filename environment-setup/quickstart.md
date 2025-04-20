# Quickstart
1. If you don't want to develop embedded firmware code, you can use prebuilt simulated vehicle binaries.
2. To do that, run the below code:

```shell
curl -s -L https://raw.githubusercontent.com/mustafa-gokce/ardupilot-software-development/main/environment-setup/quickstart.sh | /usr/bin/bash
```

3. This will install all the required Linux system packages and python modules to follow this course.
4. Run the shell script ```./ardu-sim.sh```
5. Check the screen sessions ```screen -ls```
6. Connect to a vehicle ```mavproxy.py --master=127.0.0.1:14550```
