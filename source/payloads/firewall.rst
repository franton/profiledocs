.. _payloadtype-com.apple.security.firewall:

Firewall
========

Available in macOS 10.12 and later. A Firewall payload manages the Application Firewall settings accessible in the Security Preferences pane. Note these restrictions:

- The payload must exist in a system-scoped profile.
- If more than one profile contains this payload, the most restrictive union of settings will be used.
- The "Automatically allow signed downloaded software" and "Automatically allow built-in software" options are not supported, but both will be forced **ON** when this payload is present.

Summary
-------

.. pfmheader:: manifests/manual/com.apple.security.firewall manifest.plist
.. pfm:: manifests/manual/com.apple.security.firewall manifest.plist

Keys
----

Links
-----

- `Official Documentation <https://developer.apple.com/library/content/featuredarticles/iPhoneConfigurationProfileRef/Introduction/Introduction.html#//apple_ref/doc/uid/TP40010206-CH1-SW443>`_.
