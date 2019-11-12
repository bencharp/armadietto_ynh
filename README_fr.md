# Package Armadietto pour YunoHost

[![Installer Armadietto avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=Armadietto)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Armadietto rapidement et simplement sur un serveur Yunohost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
[Armadietto](https://github.com/remotestorage/armadietto) est un serveur [remoteStorage](https://remotestorage.io) écrit pour Node.js.
Il s'agit d'une réécriture complète de[reStore](https://github.com/jcoglan/restore).

Armadietto est maintenue par la Team remoteStorage [IRC](https://kiwiirc.com/client/irc.freenode.net/#remotestorage)

> ### :warning: ATTENTION
> Ce projet est encore considéré comme expérimental, merci de ne pas considérer `armadietto` comme étant une application prête pour une utilisation en production.
> Comme toute technologie de stockage en cours de développement *(alpha-stage)*, vous DEVEZ vous attendre à d'éventuelles pertes de données et nous vous invitons à prendre toutes les précautions nécessaires pour pouvoir pallier à ces éventualités.
> Et tant qu'elle ne sera pas étiquetté comme stable, vous DEVEZ également vous attendre à ce que ses APIs et ses schémas de stockage changent.

**Version incluse:** 0.1.5


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


## Captures d'écran

![](Lien vers une capture d'écran pour cette application)

## Démo

* [Démo officielle](Lien vers un site de démonstration pour cette application)

## Configuration

Comment configurer cette application: via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle: Lien vers la documentation officielle de cette application
 * Documentation YunoHost: Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge?
L'application peut-elle être utilisée par plusieurs utilisateurs?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/REPLACEBYYOURAPP/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/REPLACEBYYOURAPP/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/REPLACEBYYOURAPP/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

**Plus d'informations sur la page de documentation:**
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/issues
 * Site de l'application: Lien vers le site officiel de cette application
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --debug
ou
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --debug
```
