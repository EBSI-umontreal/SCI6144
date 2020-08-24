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
  * Documentation pour une installation avec Vagrant : [https://www.accesstomemory.org/fr/docs/2.6/dev-manual/env/vagrant/#dev-env-vagrant](https://www.accesstomemory.org/fr/docs/2.6/dev-manual/env/vagrant/#dev-env-vagrant)
* Alfresco
* Alfresco-RM
* Archivematica
  * Documentation pour une installation avec Vagrant : [https://www.archivematica.org/fr/docs/archivematica-1.11/getting-started/quick-start/quick-start/#installing-on-vm](https://www.archivematica.org/fr/docs/archivematica-1.11/getting-started/quick-start/quick-start/#installing-on-vm)
* ArchiveSpace
  * Documentation pour une installation avec Vagrant : [https://github.com/seanlw/archivesspace-vagrant](https://github.com/seanlw/archivesspace-vagrant)
  * Démo officielle : [https://archivesspace.org/application/demo](https://archivesspace.org/application/demo)
* CollectiveAccess
  * Documentation pour installation : [https://collectiveaccess.org/getting-started](https://collectiveaccess.org/getting-started)
  * Démo officielle : [https://demo.collectiveaccess.org/index.php/system/auth/login](https://demo.collectiveaccess.org/index.php/system/auth/login)
* Constellio
* [Dokuwiki](https://www.dokuwiki.org/dokuwiki)
* Elasticsearch
* [Koha](https://koha-community.org/)
* Nuxeo
  * Fichiers à télécharger [https://nuxeo.github.io/downloads.html](https://nuxeo.github.io/downloads.html)
  * Documentation d'intallation [https://doc.nuxeo.com/nxdoc/installing-the-nuxeo-platform-on-linux/](https://doc.nuxeo.com/nxdoc/installing-the-nuxeo-platform-on-linux/)
* [OpenKM](https://www.openkm.com/)
  * Documentation : [https://docs.openkm.com/kcenter/view/okm-6.3-com/installation.html](https://docs.openkm.com/kcenter/view/okm-6.3-com/installation.html)
* Rocket.chat
  * Documentation pour une installation avec Vagrant : [https://docs.rocket.chat/installation/automation-tools/vagrant](https://docs.rocket.chat/installation/automation-tools/vagrant)
* [SubjectPlus](http://www.subjectsplus.com/)
* [Tematres](https://www.vocabularyserver.com/)
  * Documentation d'installation
  * Démo officielle : [https://r020.com.ar/tematres/demo/index.php?setLang=en](https://r020.com.ar/tematres/demo/index.php?setLang=en)
* Wikipedia
  * Documentation pour une installation avec Vagrant : [https://www.mediawiki.org/wiki/MediaWiki-Vagrant](https://www.mediawiki.org/wiki/MediaWiki-Vagrant)
