### Linux CPU Frequency vs. Power Settings </p>

Sadly in Linux / K/Ubuntu </br>
Gnome System Monitor is very Basic "incomplete",</br>
Needs other softwares to see the whole information, </br>
CPU Freq, Powermode, Disk i/o. </p>

plasma-systemmonitor is similar to Gnome System Monitor, </br>
but more like Kubuntu Widgets.</br>
its pretty & colorful, </br>
as configurable as GKrellM, but has a strange way of doing things at first.</br>
has nested sub menu configuration.</br>
To edit each panel, needs to select the border of the panel,</br> 
that opens a hidden menu "Edit Mode", then click the actual panel </br>
instead of that should havbe icons vibrating like Mobiles.</br> 
Needs tweaking, </br>
Show Y Axis Labels "Fonts" is annoyiong.</br>
Show Sensor Legend "Fonts" is annoyiong.</br> 
and still does Not have all information available </br>
needs a good Global Font configuration.</p>

GKrellM System Monitor, </br>
is also incomplete, but looks similar to OSX,</br>
OSX allows to resize the CPU Windows with the Mouse,</br>
GKrellM is fixed, only Font size can resize the Window,
Font size is insed the GKrellM System Monitor, better than Plasma SystemMonitor.</p>

Xosview can be resized, much better than GKrellM in that,</br>
has more information, CPU freq.</br>
but Theme & Fonts are Horrible.</br>
does Not have individual Cores, </br>
and Network ranges seem far off.</p>

Kubuntu Widgets has very pretty individual CPU core meters, </br>
or nice circular single Total CPU Meter.</br>
very pretty, minimalistic but lacks information.</p>

CPU-X is a Nice way to see CPU Frequency. </br>
Has "Dark" Theme, but Not as good as GKrellM custom Themes.</p>

CPU-X = CPU-Z = $ sudo cpupower monitor </p>

cpupower-gui is a nice way to change power settings.</br>
$ cpupower is a nice Terminal way to monitor settings, like Htop </p>

$ sudo apt install cpupower-gui </br>
$ sudo apt install linux-tools-common </br>
$ sudo apt install linux-nvidia-tools-common </br>
$ sudo apt install linux-intel-iotg-tools-common </p>
$ sudo apt install linux-tools-5.15.0-47-generic </p>

$ sudo cpupower monitor </br>
$ sudo cpupower frequency-info </p>

Gnome shell optional, does Not work in Kubuntu: </p>

$ sudo add-apt-repository ppa:fin1ger/cpupower </br>
$ sudo apt-get update </br>
$ sudo apt-get install gnome-shell-extension-cpupower </br>
$ gnome-extensions enable cpupower@mko-sl.de </p>

power options: </br>
$ cat /sys/devices/system/cpu/cpu0/cpufreq/scaling_available_governors </br> 
conservative ondemand userspace powersave performance schedutil <p>

$ sudo apt install cpufrequtils </br>
