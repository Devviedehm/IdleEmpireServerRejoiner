# IdleEmpireServerRejoiner
Auto rejoiner in HTML/Javascript that attempts to join Idle Empire's TF2 Servers.

A simple HTML page that lets you automatically rejoin one of Idle-Empire.com's TF2 servers.

<hr/>

Version one has no interface, only a blank page which works as long as you keep it open. It immediately tries to connect to Server 19, and then retries every 30 minutes.

You can use it here: https://devviedehm.github.io/IdleEmpireServerRejoiner/rejoin.html

<hr/>

Version two has a prettier interface and is more configurable. You can set an interval in hours, minutes and seconds, and then start the interval.

Once active, it will only connect after that amount of time has passed, not immediately. To connect immediately, you can press the "Connect now" button.

It stores your settings (time interval and server selected) in localStorage.

You can use it here: https://devviedehm.github.io/IdleEmpireServerRejoiner/rejoin_v2.html

<hr/>

Currently both versions' rejoin function will force the game to rejoin, even if you're still connected. This may mean the loss of one or two points during the rejoin.

However, it also gives you peace of mind that you won't lose too many points (depending on what interval you set) if you lose connection overnight.

The source code is also fully readable (though not commented), if you want to take a look at how I coded everything.

I hope this has been helpful, and please let me know if you have any problems with it. :)
