# Nimby Rails Multiplayer Identity service

This is the authentication component for the Nimby Rails Multiplayer Companion app.
It provides an OAuth2-compliant authentication layer over Steam's Open ID 2.0 protocol, and handles authentication concerns for the Web APIs.

In particular, this component makes it possible for the desktop app to implement OAuth 2.0 authentication and receive an access token containing information about the logged in steam user, which the web APIs can use for authorization purposes.
