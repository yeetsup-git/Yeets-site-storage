# Sudo in crosh


First, get [chromebrew](https://github.com/chromebrew/chromebrew)  
*Use vt2 (`ctrl` + `alt` + `f2`) to install.*  

Now, use the command `crew install crew_sudo`, which can be used in crosh or vt2.

Then, log out of vt2 and/or crosh, then re-login to vt2 as `chronos`, then the crew_sudo deamon will autostart. Whenever chromeos restarts, login to vt2 to start the deamon.

Now you can use `sudo` in crosh just like before update 117