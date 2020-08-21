# Documentation générale - Vagrant

Documentation pour le contenu des fichiers `Vagrantfile`.

## Paramètres communs

### Port forwading

Pour ouvrir un ou des ports pour accéder à l'interface Web du logiciel.

Pour faciliter l'utilisation des VM, l'adresse IP de toutes les VM est `127.0.0.1`. Si un seul port est nécessaire, il serait opportun de rediriger vers le port 80.

`config.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1", id: "apache2"`

### Mémoire vive

Pour s'assurer d'avoir assez de RAM pour la VM.

`vb.memory = "4096"`

### Partage de fichiers

Pour partager toujours le même dossier de travail.

`config.vm.synced_folder "src/", "/srv/website"`

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
* OpenKM
* Rocket.chat
  * Documentation pour une installation avec Vagrant : [https://docs.rocket.chat/installation/automation-tools/vagrant](https://docs.rocket.chat/installation/automation-tools/vagrant)
* [SubjectPlus](http://www.subjectsplus.com/)
* Wikipedia
  * Documentation pour une installation avec Vagrant : [https://www.mediawiki.org/wiki/MediaWiki-Vagrant](https://www.mediawiki.org/wiki/MediaWiki-Vagrant)