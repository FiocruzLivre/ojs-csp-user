# CSP Users Plugin

Plugin to add custom fields and customizes user edition area in Open Journal System (OJS).

**OJS version: 3.4.0, 3.5.0**


## Installation

**OJS 3.5 (ensp-csp-ojs-3.5 stack):** this repo is bind-mounted into the
`app` container at `/var/www/html/plugins/generic/cspUser` via
`docker-compose.yml` in the `ensp-csp-ojs-3.5` repo, checked out to the
`ojs-3.5` branch. Enable it in _Website > Plugins_ after the container
picks up the mount. The external SSO auto-provisioning feature (LoadHandler)
present in the 3.4 version has been removed in this port.

**Standalone OJS install (3.4 or earlier):**

1) Clone this repo inside the directory ``ojs/plugins/generic/`` :

   ``git clone https://github.com/FiocruzLivre/ojs-csp-user.git cspUser``

    > The plugin must be inside a _cspUser_ named folder
2) In the system, enable the plugin in _Website > Plugins_ area
