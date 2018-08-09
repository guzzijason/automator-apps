# automator-apps
Some handy Automator apps for MacOS

- ChromeLauncher.app  
    Makes sure chrome always starts up in UTC timezone.  
    Can be used to set other command-line args as well.

- PulseLauncher.app  
    Use to manually start the Pulse VPN client, which isn't loaded  
    becase we use the PulseUnstarter. Which brings us to...

- PulseUnstarter.app  
    If you use the Pulse VPN client, then you realize it's a little  
    bastard that persistently tries to start your VPN connection  
    EVERY... SINGLE... TIME... you reboot. And the developers seem  
    to believe that there's NO WAY anyone would not want this horrible  
    default behavior, so they give you no way to disable it. Lovely.  
    So, this disable it. Just add this as a Login Item in your user  
    preferences to make Pulse go away until you need it.  

