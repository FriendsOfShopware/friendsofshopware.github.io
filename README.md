# Friends of Shopware

FriendsOfShopware is a group of developers who have banded together to build solid, well tested Shopware Plugins using modern coding standards.

# How do I get in touch?
Several of us hang out in [Shopware's gitter channel](https://gitter.im/shopware/shopware). We also have our [own gitter channel](https://gitter.im/FriendsOfShopware/Lobby). Finally if you want to ask for a vote (for example to propose a new topic/plugin) create a issue in our [repository](https://github.com/FriendsOfShopware/friendsofshopware.github.com).

# Rules for plugin contributions
* Your plugin must support the latest version of Shopware.
* List on Packagist with Frosh as the vendor namespace.
* Use [Semantic Versioning](https://semver.org/) to manage version numbers.
* Maintain a CHANGELOG.md and also maintain the changelogs in the plugin.xml.
* Use Travis-CI to automatically run tests and bundle plugins as zip files so that they can be downloaded and uploaded in the Shopware backend.
* Have an extensive README.md.
* Your plugin name must start with "Frosh" and the repository must be owned by the Friends of Shopware organization.
* The repository license must be MIT.
* Your plugin must be well documented with DocBlocks.

# Code Review Workflow
* We have one main maintainer per project.
* Reviews will be taken by a frosh member, which is not in conjunction with the project
  * Pull Requests will be posted to a special channel on gitter (FriendsOfShopware/pullrequests)
  * Frosh members which have time can pick a pull request to review
  * At least one approve must be given by a frosh member, before a pull request can be merged
* Obvious stuff can be committed without review (Example: Typo fixes)

# How to become a member?
All maintainers of a project are automatically in the Friends of Shopware group. 

# Projects

| Project     | Description                                                | Project lead                 |
|-------------|------------------------------------------------------------|------------------------------|
| [Codeception](https://github.com/FriendsOfShopware/FroshCodeCeptionTests) | Codeception Testsuite for default Responsive Theme         | Tim Windelschmidt ([@fionera](https://github.com/fionera)) |
| [Profiler](https://github.com/FriendsOfShopware/FroshProfiler)    | Symfony Profiler ported to Shopware with custom collectors | Soner Sayakci ([@shyim](https://github.com/shyim))       |
| [Grafana](https://github.com/FriendsOfShopware/FroshGrafana)     | Track your shopware and server statistics within Grafana   | Kai Neuwerth ([@Crease29](https://github.com/Crease29))      |
| [TemplateMail](https://github.com/FriendsOfShopware/FroshTemplateMail)     | Store mail templates in theme   | Soner Sayakci ([@shyim](https://github.com/shyim))      |
