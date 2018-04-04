# ArchivesSpace technical documentation

* [Basic administration](./administration)
  * [Getting started](./administration/getting_started.md)
  * [Running ArchivesSpace as a Unix daemon](./administration/unix_daemon.md)
  * [Running ArchivesSpace as a Windows service](./administration/windows.md)
  * [Backup and recovery](./administration/backup.md)
  * [Re-creating indexes](./administration/indexes.md)
  * [Resetting passwords](./administration/passwords.md)
  * [Upgrading](./administration/upgrading.md)
* [Architecture and components](./architecture)
  * [JSONModel -- a validated ArchivesSpace record](./architecture/jsonmodel.md)
  * [The ArchivesSpace backend](./architecture/backend.md)
  * [Background Jobs](./architecture/background_jobs.md)
  * [Working with the ArchivesSpace API](./architecture/api.md)
  * [Search indexing](./architecture/search.md)
  * [The ArchivesSpace public user interface](./architecture/public.md)
  * [OAI-PMH interface](./architecture/oai-pmh.md)
* [Customization and configuration](./customization)
  * [Configuring ArchivesSpace](./customization/configuration.md)
  * [Adding support for additional username/password-based authentication backends](./customization/authentication.md)
  * [Configuring LDAP authentication](./customization/ldap.md)
  * [ArchivesSpace Plug-ins](./customization/plugins.md)
  * [Customizing text in ArchivesSpace](./customization/locales.md)
  * [Theming ArchivesSpace](./customization/theming.md)
  * [Managing frontend assets with Bower](./customization/bower.md)
* [Provisioning and server configuration](./provisioning)
  * [Running ArchivesSpace with load balancing and multiple tenants](./provisioning/clustering.md)
  * [Serving ArchivesSpace over subdomains](./provisioning/domains.md)
  * [Serving ArchivesSpace user-facing applications over HTTPS](./provisioning/https.md)
  * [JMeter Test Group Template](./provisioning/jmeter.md)
  * [Running ArchivesSpace against MySQL](./provisioning/mysql.md)
  * [Application monitoring with New Relic](./provisioning/newrelic.md)
  * [Running ArchivesSpace under a prefix](./provisioning/prefix.md)
  * [Running ArchivesSpace with external Solr](./provisioning/solr.md)
  * [Tuning ArchivesSpace](./provisioning/tuning.md)
* [Information for developers and code contributors](./development)
  * [ArchivesSpace build system](./development/build.md)
  * [Building an ArchivesSpace release](./development/release.md)
  * [Selenium test suite](./development/selenium.md)
  * [Using Supervisord for development](./development/supervisord.md)
  * [Contributor license agreements](./development/license_agreements.md)
* [Importing and exporting data in ArchivesSpace](./import_export)
  * [ArchivesSpace repository EAD Exporter](./import_export/ead_exporter.md)
  * [ArchivesSpace XSL stylesheets](./import_export/xsl_stylesheets.md)
* [Migration tools and data mapping](./migrations)
  * [Archivists' Toolkit migration tool instructions](./migrations/migrate_from_archivists_toolkit.md)
  * [Archon migration tool instructions](./migrations/migrate_from_archon.md)
