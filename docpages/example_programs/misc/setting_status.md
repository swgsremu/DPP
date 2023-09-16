\page setting_status Setting the bot's status

A bot status is pretty cool, and it'd be cooler if you knew how to do it! This tutorial will cover how to set the bot status to say `Playing games!`, as well as covering how to set the status to the amount of guilds every two minutes.

First, we'll cover setting the bot status to `Playing games!`.

\include{cpp} setting_status1.cpp

If all went well, your bot should now be online and say this on members list!

\image html botonlinestatus.png

Now, let's cover setting the bot status to say `Playing with x guilds!` every two minutes.

\include{cpp} setting_status2.cpp

If you followed that well, your bot should now say this on members list!

\image html botonlinestatus2.png

If we then add our bot to another server and wait a bit, we'll see it updates like so:

\image html botonlinestatus3.png