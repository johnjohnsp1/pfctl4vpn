# pf configuration for a VPN connection
This is a simple BSD [pf](http://www.openbsd.org/faq/pf/) configuration that I have created to ensure that all outbound traffic will always go over a VPN connection. If the VPN connection drops, pf will ensure that all outbound traffic is blocked, preventing VPN leaks.
IMO this is the most effective way to prevent VPN leaks on OS X. Much better than configureing routing tables or AppleScripts. 

Replace the localhost placeholder in the config with IP addresses. [This guide](http://blog.scottlowe.org/2013/05/15/using-pf-on-os-x-mountain-lion/) explains how to configure pf's LaunchDaemon. If there is need for a more detailed guide, I can also put one up here.

See the conf file for more info. Feel free to do with this config w/e you like.

Stay safe!  :smile: