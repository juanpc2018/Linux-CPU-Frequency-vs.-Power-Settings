### Linux CPU Frequency vs. Power Settings </p>

Sadly in Linux / K/Ubuntu </br>
Gnome System Monitor is very Basic "incomplete",</br>
Needs other softwares to see the whole information, </br>
CPU Freq, Powermode, Disk i/o. </p>

plasma-systemmonitor is similar to Gnome System Monitor, </br>
but more like Kubuntu Widgets.</br>
its ok, but... too much nested sub menu configs.
Show Y Axis Labels "Fonts" is annoyiong.</br>
Show Sensor Legend "Fonts" is annoyiong.</br> 
Needs tweaking, and still does Not have all information available,</br>
Fonts looks weird, needs better Global Font configuration.</p>


GKrellM System Monitor, </br>
is also incomplete, but looks similar to OSX,</br>
OSX allows to resize the Windows with the Mouse,</br>
GKrellM is fixed, only Font size can resize the Window.</p>

Xosview can be resized, is more informative,</br>
but Theme and Fonts are horrible.</br>
does Not have individual Cores, </br>
and Network ranges seem far off.</p>

Kubuntu Widgets has very pretty individual CPU core meters, 
or nice circular single Total CPU Meter.
very pretty, minimalistic but lacks more information.</p>

CPU-X is a Nice way to see CPU Frequency.
Has "Dark" Theme, but Not as good as GKrellM custom Themes.</p>

CPU-X = CPU-Z = $ sudo cpupower monitor
cpupower-gui

$ sudo apt install cpupower-gui


$ sudo apt install linux-tools-common
$ sudo apt install linux-nvidia-tools-common
$ sudo apt install linux-intel-iotg-tools-common

$ sudo apt install linux-tools-5.15.0-47-generic

$ sudo cpupower monitor
$ sudo cpupower frequency-info


gnome shell optional:

$ sudo add-apt-repository ppa:fin1ger/cpupower

$ sudo apt-get update
$ sudo apt-get install gnome-shell-extension-cpupower

$ gnome-extensions enable cpupower@mko-sl.de


power options:
$ cat /sys/devices/system/cpu/cpu0/cpufreq/scaling_available_governors 
conservative ondemand userspace powersave performance schedutil 

$ sudo apt install cpufrequtils


$ cat /etc/mbpfan.conf
