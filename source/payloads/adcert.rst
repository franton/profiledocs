.. _payloadtype-com.apple.ADCertificate.managed:

Active Directory Certificate
============================
:download:`Template <../_static/examples/com.apple.ADCertificate.managed.mobileconfig>`

You can request a certificate from a Microsoft Certificate Authority (CA) using DCE/RPC and the
Active Directory Certificate profile payload instructions detailed at https://support.apple.com/kb/HT5357.

Summary
-------

.. pfmheader:: manifests/manual/com.apple.ADCertificate.managed manifest.plist

.. pfm:: manifests/manual/com.apple.ADCertificate.managed manifest.plist


Keys
----

.. pfmkey:: Description manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: CertServer manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: CertTemplate manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: CertificateAuthority manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: CertificateAcquisitionMechanism manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: CertificateRenewalTimeInterval manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: Keysize manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: UserName manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: Password manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: PromptForCredentials manifests/manual/com.apple.ADCertificate.managed manifest.plist
.. pfmkey:: AllowAllAppsAccess manifests/manual/com.apple.ADCertificate.managed manifest.plist

Links
-----

- `macmules blog: OSX & AD CERTIFICATE REQUESTS, SOME TIPS <https://macmule.com/2015/09/06/osx-ad-certificate-requests-some-tips/>`_.

