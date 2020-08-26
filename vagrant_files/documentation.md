# Documentation générale - Vagrant

Documentation pour le contenu des fichiers `Vagrantfile`.

## Objectifs

Pour faciliter la prise en main des logiciels nous uniformisons le maximum de paramètres de configuration.

## Réseau

La redirection de port est configurée pour utiliser l'adresse IP `127.0.0.1`.

Si un seul port est nécessaire, il serait opportun de rediriger vers le port 80.

Exemple : `config.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1", id: "apache2"`

## Mémoire vive

Pour s'assurer d'avoir assez de mémoire vive, nous accordons 4 Go de RAM à la VM : `vb.memory = "4096"`

## Sources des VM

* Accesstomemory
  * Documentation pour une installation avec Vagrant : [https://www.accesstomemory.org/fr/docs/2.6/dev-manual/env/vagrant/#dev-env-vagrant](https://www.accesstomemory.org/fr/docs/2.6/dev-manual/env/vagrant/#dev-env-vagrant) (en)
* Alfresco
* Alfresco-RM
* Archivematica
  * Documentation pour une installation avec Vagrant : [https://www.archivematica.org/fr/docs/archivematica-1.11/getting-started/quick-start/quick-start/#installing-on-vm](https://www.archivematica.org/fr/docs/archivematica-1.11/getting-started/quick-start/quick-start/#installing-on-vm) (en)
* ArchiveSpace
  * Documentation pour une installation avec Vagrant : [https://github.com/seanlw/archivesspace-vagrant](https://github.com/seanlw/archivesspace-vagrant) (en)
  * Démo officielle : [https://archivesspace.org/application/demo](https://archivesspace.org/application/demo) (en)
* CollectiveAccess
  * Documentation pour installation : [https://collectiveaccess.org/getting-started](https://collectiveaccess.org/getting-started) (en)
  * Démo officielle : [https://demo.collectiveaccess.org/index.php/system/auth/login](https://demo.collectiveaccess.org/index.php/system/auth/login) (en)
* Constellio
* [Dokuwiki](https://www.dokuwiki.org/dokuwiki) (en)
* Elasticsearch
* [Koha](https://koha-community.org/) (en)
  * Documentation d'installation : [https://wiki.koha-community.org/wiki/Debian](https://wiki.koha-community.org/wiki/Debian) (en)
* Nuxeo
  * Fichiers à télécharger : [https://nuxeo.github.io/downloads.html](https://nuxeo.github.io/downloads.html) (en)
  * Documentation d'intallation : [https://doc.nuxeo.com/nxdoc/installing-the-nuxeo-platform-on-linux/](https://doc.nuxeo.com/nxdoc/installing-the-nuxeo-platform-on-linux/) (en)
* [Odoo](https://www.odoo.com/fr_FR/)
  * Documentation pout l'installation : [https://www.odoo.com/documentation/13.0/setup/install.html#prepare](https://www.odoo.com/documentation/13.0/setup/install.html#prepare) (en)
* [OpenKM](https://www.openkm.com/) (en)
  * Documentation : [https://docs.openkm.com/kcenter/view/okm-6.3-com/installation.html](https://docs.openkm.com/kcenter/view/okm-6.3-com/installation.html) (en)
* Rocket.chat
  * Documentation pour une installation avec Vagrant : [https://docs.rocket.chat/installation/automation-tools/vagrant](https://docs.rocket.chat/installation/automation-tools/vagrant) (en)
* [SubjectPlus](http://www.subjectsplus.com/) (en)
* [Tematres](https://www.vocabularyserver.com/) (en)
  * Documentation d'installation
  * Démo officielle : [https://r020.com.ar/tematres/demo/index.php?setLang=en](https://r020.com.ar/tematres/demo/index.php?setLang=en) (en)
* Wikipedia
  * Documentation pour une installation avec Vagrant : [https://www.mediawiki.org/wiki/MediaWiki-Vagrant](https://www.mediawiki.org/wiki/MediaWiki-Vagrant) (en)

## Documentation pour Virtualbox

* Importation d'un fichier OVA [https://www.informatiweb.net/tutoriels/informatique/virtualisation/virtualbox-export-et-import-de-vm-en-ovf-ova.html](https://www.informatiweb.net/tutoriels/informatique/virtualisation/virtualbox-export-et-import-de-vm-en-ovf-ova.html) (fr)

## Documentation pour Vagrant

* Utilisation en ligne de commande : [https://www.vagrantup.com/docs/cli/up](https://www.vagrantup.com/docs/cli/up) (en)
