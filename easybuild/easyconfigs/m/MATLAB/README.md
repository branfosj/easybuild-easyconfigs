# License

* Your Matlab license should have a "`File Installation Key`" under "`Advanced Options`" in the "`Install and Activate`" tab of your "`License Center`".
  This will only install the products associated with this license.
* If you need to install all of the toolboxes to support multiple licenses Mathworks can enable a "`All Product File Installation Key`".
  This will install all of the client products but will not install server products like MDCS.
  A second manual installation on top of the first will be required.
* If you have a server product key, like MDCS, the "`File Installation Key`" may not install client products like Matlab Compilers.
  A second manual installation on top of the first will be required.

To use the license information for an installation, either
* specify the environment variables
  ```
  export EB_MATLAB_KEY=XXXXX-XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
  export EB_MATLAB_LICENSE_SERVER=<IP or FQDN>
  export EB_MATLAB_LICENSE_SERVER_PORT=<port>
  ```
* modify the easyconfig directly
  ```
  key = 'XXXXX-XXXXX-XXXXX-XXXXX-XXXXX-XXXXX'
  license_server = '<IP or FQDN>'
  license_server_port = '<port>'
  ```
and then install as normal, e.g. `eb MATLAB-2021a.eb`

