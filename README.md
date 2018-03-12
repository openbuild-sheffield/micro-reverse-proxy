# Reverse proxy for dev

[traefik](https://traefik.io) file based config for local development.

This proxies create react app, serverside rendered react and symfony API through a single endpoint http://dev.local

Can be used as is or as a starting point to add other micro services.

Make sure you have the traefik binary in your path then run launch-dev.sh any changes to the dev directory will cause the proxy to reload.
