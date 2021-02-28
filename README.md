# tuned-udev-rules
A couple udev rules to control tuned configuration based on presence or absence of an AC adapter. Depends on tuned.

99-tuned.rules belongs in /etc/udev.d/rules
The scripts should go in /opt
You will quite likely need to tweak this to find the right events for your hardware
