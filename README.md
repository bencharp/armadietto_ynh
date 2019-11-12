# Armadietto package for Yunohost

[![Install Armadietto with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=Armadietto)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Armadietto quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Armadietto overview

[Armadietto](https://github.com/remotestorage/armadietto) is a [remoteStorage](https://remotestorage.io) server written for Node.js.
It is a complete rewrite of [reStore](https://github.com/jcoglan/restore).

Armadietto is maintained by remoteStorage Team [IRC](https://kiwiirc.com/client/irc.freenode.net/#remotestorage)

> ### :warning: WARNING
> Please do not consider `armadietto` production ready, this project is still
> considered experimental.  As with any alpha-stage storage technology, you
> MUST expect that it will eat your data and take precautions against this. You
> SHOULD expect that its APIs and storage schemas will change before it is
> labelled stable.

**Shipped version:** 0.1.5


### Important Notes
RemoteStorage requires a dedicated domain, so obtain one and add it using the YunoHost admin panel. **Domains -> Add domain**. As RemoteStorage uses the full domain and is installed on the root, you can create a subdomain such as remote.domain.tld. Don't forget to update your DNS if you manage them manually.

RemoteStorage requires browser-approved SSL certificates. If you have certificates not issued by [Let's Encrypt](https://letsencrypt.org/), install them manually as usual.


### Application for remoteStorage
[Click here](https://wiki.remotestorage.io/Apps) to see the list of applications that can be used with RemoteStorage.


## Yunohost app License
Licensed under the GNU Affero General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option) any
later version.

    https://www.gnu.org/licenses/agpl.html

This roughly means that if you use this software in your service you need to
make the source code available to the users of your service (if you modify
it). Refer to the license for the exact details.

## Armadietto License

(The MIT License)

Copyright (c) 2012-2015 James Coglan
Copyright (c) 2018 remoteStorage contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the 'Software'), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Screenshots [=> TODO]

![](Link to an screenshot for this app)

## Demo [=> TODO]

* [Official demo](Link to a demo site for this app)

## Configuration [=> TODO]

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation [=> TODO]

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features [=> TODO]

#### Multi-users support [=> TODO]

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures [=> TODO]

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/REPLACEBYYOURAPP/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/REPLACEBYYOURAPP/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/REPLACEBYYOURAPP/)

## Limitations [=> TODO]

* Any known limitations.

## Additional information [=> TODO]

* Other information you would add about this application

**More information on the documentation page:**
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/bencharp/armadietto_ynh/issues
 * App website: Link to the official website of this app
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/bencharp/armadietto_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/bencharp/armadietto_ynh/tree/testing --debug
or
sudo yunohost app upgrade armadietto_ynh -u https://github.com/bencharp/armadietto_ynh/tree/testing --debug
```
