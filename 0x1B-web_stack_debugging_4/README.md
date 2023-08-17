# Web stack debugging #4

![skyislimitLOLalx](https://github.com/Obony/alx-system_engineering-devops/assets/117737538/3cb61e7d-3e02-4717-95f1-7dda19f1a525)

Dealing with broken/bugged webstacks in isolated containers,
and tasked with fixing the web stack to a working state.

## Tasks :page_with_curl:

* **0. Sky is the limit, let's bring that limit higher**
  * [0-the_sky_is_the_limit_not.pp](./0-the_sky_is_the_limit_not.pp): Puppet manifest
  that increases the amount of traffic an Apache web server can effectively handle.

* **1. User limit**
  * [1-user_limit.pp](./1-user_limit.pp): Puppet manifest that changes the operating system
  configuration so that it is possible to login with the user `holberton` and open a file
  without error.
