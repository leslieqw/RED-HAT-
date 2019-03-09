# RED-HAT-
STEPS TO CONFIGURE RED HAT NETWORK 
 cd /etc/sysconfig/network-scripts 
 vi <interface name>
press I to be in insert mode 
 change ONBOOT to YES 
If you would want to connect to a static network change BOOTPROTO to static 
press esc to exit out of insert mode
press shift colon wq!  ---*save & exit*
  run the command- systemctl restart network 
  ping any DNS server you want to test for network connectivity. eg. ping 8.8.8.8
