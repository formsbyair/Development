---
title: Login IP Address Whitelist
type: platform
---

To further enhance security, FormsByAir now supports IP Address Whitelisting for login to the portal and private forms.

This is particularly useful for large clients that operate on a corporate network and wish to restrict access to FormsByAir from that network only.

To enable, log in to the FormsByAir portal, go to Settings &gt; Profile and enter one or more IP addresses for **Login IP Address Whitelist**, then Save Changes.

All login attempts from that point forward will be checked against the whitelist. If a user's IP address doesn't match they won't be able to log in.

This feature can be used in conjunction with **Two Factor Authentication** for strict access control over form data that we (temporarily) hold.

Login IP Address Whitelisting does not apply to API Key access.

Users that are already logged in and subsequently switch to a different network will remain logged in.