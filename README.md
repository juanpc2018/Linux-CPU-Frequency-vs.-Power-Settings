### Linux CPU Frequency vs. Power Settings </p>

Sadly in Linux / K/Ubuntu </br>
Gnome System Monitor is very Basic "incomplete",</br>
Needs other softwares to see the whole information, </br>
CPU Freq, Powermode, Disk i/o. </p>

plasma-systemmonitor is similar to Gnome System Monitor, </br>
but more like Kubuntu Widgets.</br>
its pretty, colorful, configurable like GKrellM,</br>
but has a strange way of doing things.</br>
configuration has nested sub menus.</br>
To edit each panel needs to select the border of the panel,</br> 
Up Border: Add, Delete, Height.</br> 
Down Border: opens "Edit Mode" then click the actual panel to Edit. </br>
instead of vibrating icons like Mobiles.</br> 
Needs tweaking, </br>
Line Chart, No Stacked, No Grid, 0%-25% Opacity is Similar to Gnome System Monitor.</br>
Problem is the Show Sensor Legend Font size. </br>
needs a good Global Font configuration outside System Monitor.</br>
has presets. </br>
very configurable, eye candy but does Not have all information.</p>

GKrellM System Monitor: </br>
also Not all information, looks similar to OSX,</br>
OSX allows to resize the CPU Windows with the Mouse,</br>
GKrellM is fixed, only Font size can resize the Window,</br>
but Font size is inside the GKrellM System Monitor, better than Plasma SystemMonitor Global font outside.</br>
OSX only shows CPU floating window, and Dock Icon can show other info like Network,</br>
GKrellM can show more info in the Floating window, No Dock icon, feels more primitive in some ways.</p>

Xosview floating window can be resized very nice, much better than GKrellM in that,</br>
has more information, like CPU freq.</br>
but small Fonts & Theme are Horrible.</br>
does Not have individual Cores, plastama meters are much more eye candy. </br>
and Network auto-ranges seem far off in Xosview, in plasma Auto Ranges are much better.</p>

Kubuntu Widgets has very pretty individual CPU core meters, </br>
or nice circular single Total CPU Meter.</br>
very pretty, minimalistic but lacks information.</p>

CPU-X is a Nice way to see CPU Frequency. </br>
Has "Dark" Theme, but Not as good as GKrellM custom Themes.</p>

CPU-X = CPU-Z = $ sudo cpupower monitor </p>

cpupower-gui is a nice way to change power settings.</br>
$ cpupower is a nice Terminal way to monitor settings, like Htop </p>

---------
GKrellM System Monitor - CoplandOS Theme</br>![image](https://user-images.githubusercontent.com/33388902/187737177-d21d7b4f-2026-470c-a14b-23d873631f83.png)
-------
Plasma System Monitor</br>![image](https://user-images.githubusercontent.com/33388902/187737262-db104873-b1b1-49e5-9847-009c80037cbf.png)
-------
Gnome System Monitor</br>![image](https://user-images.githubusercontent.com/33388902/187737339-1565c40d-9835-4465-84f5-c462923cce02.png)
--------
CPU-X</br>![image](https://user-images.githubusercontent.com/33388902/187737390-33f18207-f56f-43ac-8e1d-1c80f4c8fb5f.png)
---------
cpupower-gui</br>![image](https://user-images.githubusercontent.com/33388902/187737448-f2b68833-c105-4467-833c-53a49adf3539.png)
--------
Xosview</br>![image](https://user-images.githubusercontent.com/33388902/187741089-58d6c5c4-e454-4449-981e-74debeb2dce2.png)
------
$ sudo apt install cpupower-gui </p>

$ sudo apt install cpupower </br>
$ sudo apt install linux-tools-common </br>
$ sudo apt install linux-nvidia-tools-common </br>
$ sudo apt install linux-intel-iotg-tools-common </br>
$ sudo apt install linux-tools-5.15.0-47-generic </br>
$ sudo cpupower monitor </br>
$ sudo cpupower frequency-info </p>

Gnome shell optional, does Not work in Kubuntu: </br>
$ sudo add-apt-repository ppa:fin1ger/cpupower </br>
$ sudo apt-get update </br>
$ sudo apt-get install gnome-shell-extension-cpupower </br>
$ gnome-extensions enable cpupower@mko-sl.de </p>

CPU Power Options: </br>
$ cat /sys/devices/system/cpu/cpu0/cpufreq/scaling_available_governors </br> 
conservative ondemand userspace powersave performance schedutil <p>

$ sudo apt install cpufrequtils </br>
