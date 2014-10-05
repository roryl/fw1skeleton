fw1skeleton
===========

An updated skeleton of a fw/1 application that is setup as a subsystem and does not need a mapping for the core files

Why?
===========
The default skeleton that ships with fw/1 requires that a mapping be configured in the server. This can be an issue if you don't want every application to share the same fw/1 core, also it is inconvenient to setup server mappings. Also the default skeleton is not setup as a subsystem. It is simply easier to create an application as a subsystem from the start so that you can expand to subsystems without converting the app to subsystems. Lastly, the core files are hidden from the web root and found using per application mappings.

