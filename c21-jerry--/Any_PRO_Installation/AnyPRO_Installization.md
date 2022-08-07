<p align="center"><h1>Any PRO Installization</h1></p>
To set up a AnyPRO, we need to :<br>
1. make a system boot disk (ubuntu)<br>
2. power on boot & install ubuntu<br>
3. install moted/sphere/qbixctl
4. auto start setting

<h1> 1.make a system boot disk (ubuntu)</h1>
please refer [https://blog.xuite.net/yh96301/blog/57645340]

<h1> 2.power on boot & install ubunt</h1>
You first connect the 技嘉 computer power supply line to the switch, press "delete" immediatelly and repeatedly (on your keyboard) to get into the BIOS mde
and use the ↑ ↓ ← → with "enter" to operate.<br>
* BIOS->Chipset->restore AC power loss[change "poweroff" to "power on"]<br>
* BIOS->Boot-> boot option 1->[change"UEFI Built-in EFI" to "disabled"]<br>
* BIOS->Save&exit->save changes & reset->yes<br><br>

Now you shut down the power supply (on switch side, not mechine side),and insert your system boot disk(usb),and  turn on the power supply (on switch side) again.<br>your computer should be able turn on automatically(remember press"delete"to get into BIOS again).<br>
* BIOS->Boot-> boot option (you should see the option 1 is your usb  and  other option is disable)<br>
* BIOS->Save&exit->save changes & reset->yes<br>
Then turn on the power supply (switch side) again. <br>
this time your computer should get into a balck background with 4 option( ubuntu is the first) to select. Here we press first option to start a series setting and installation of ubuntu.<br>

Tips:
* at the certain page: click "erase disk" at the certain page
* at the other certain page:<br>
set username as "jujue"<br>
set password as "0277134800"<br>
click "login automatically"<br>

Finally you should have ubuntu gui desktop on your screen, which means that you install ubuntu successfully.



<h1> 3.install moted/sphere/qbixctl</h1>

You now need to open terminal (keyboard shortcut:"ctrl" + "alt" + "t")<br>
or open by hand:<br>
[It should be a square icon( with 9-small-square associated)on the buttom of the fuction bar on left side of your desktop.Press it, find terminal, click icon to open terminal]<br>

Next,key in the following commands lines ( to set up installation tools):<br>
``` sudo apt update```

``` sudo apt upgrade```

Then, install moted/sphere/qbixctl by following steps:

* install motes 

  please refer to [https://github.com/motebus/ultrabook/blob/main/Ultranet%20Apps/moted-install.md]<br>
  or : jujuebrowser->ultrabook->moted install<br>

* install sphere

```sudo snap install sphere```

* install qbixctl

```sudo snap install qbixctl```

In the last, you (may) need to change hostname . Key in the command lines as following:

```sudo snap restart moted ```

```sudo snapt restart sphere```

```sudo moted.cmd --command udid```

now it should show udid of your computer on terminal. Press"ctrl"+"shift"+"c" to copy it. Then key in the command line:

```hostnamectl set-hostname anypro-xxxxx``` (xxxxx = udid you copy just now; use "ctrl"+"shift"+"v" to post it on terminal)<br>

```reboot```

Now check your terminal, hostname should be modified.

<h1> 4.auto start setting </h1>

key in the following command lines to set uo auto start (app) :<br>

``` cd .config ``` <br><br>
``` mkdir folder autostart ```







 



