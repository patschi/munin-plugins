munin-plugins
=============

Here you can find my own written programs for the monitoring service munin.

## Installation
=============

To install any plugin, you need to put it in your default munin-plugins directory. For default it is /etc/munin/plugins. As next step (different on some plugins) you need to configure the plugin in the munin-node configuration located under /etc/munin/plugin-conf.d/munin-node. More details you can read inside the plugins at the beginning.

## Plugins
=============

# wordpress
Monitors your wordpress installation with: users, posts, comments and pingbacks.
!("Screenshot")[https://munin.pkern.at/pkern.at/s1.pkern.at/wordpress_pkern_at-day.png "Screenshot")