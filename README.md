# Friends of Shopware

FriendsOfShopware is a group of developers who have banded together to build solid, well tested Shopware Plugins using modern coding standards.

# How do I get in touch?
Several of us hang out in [Shopware's gitter channel](https://gitter.im/shopware/shopware). We also have our [own gitter channel](https://gitter.im/FriendsOfShopware/Lobby). Finally if you want to ask for a vote (for example to propose a new topic/plugin) create a issue in our [repository](https://github.com/FriendsOfShopware/friendsofshopware.github.com).

# Rules

* Import all classes
* See .php_cs.dist for Codestyle and max PHP 7.0 due limitations from shopware
* List on Packagist with **Frosh** as the vendor namespace.
* Write unit tests. Aim for at least 80% coverage
* DocBlock for all the things
* Use [Semantic Versioning](https://semver.org/) to manage version numbers.
* Keep a Changelog.md and an entry in `plugin.xml`
* Use Travis-CI to automatically check coding standards and run tests.
* Have an extensive `README.md`.
* Exclude non-essential files in `.gitattributes`. 
* Plugin should have a benefit for the community
* Plugin name must start with "Frosh"
* Obvious stuff can be committed without review
* Non obvious stuff should try to get review from at least one more member
* Git-Workflow: https://guides.github.com/introduction/flow/

# I want to join!
Generally we are open to anyone joining if there is enough overlap in interest with the other members. The point is to enable collaboration among most of the members.
If there isn’t enough overlap with the existing members, just create a new vendor namespace and invite others to join.
We also want to keep the number of members somewhat manageable to make it easy to keep everyone in the loop so that there is no need to have complex organizational structures.

# Projects

| Project     | Description                                                | Project lead                 |
|-------------|------------------------------------------------------------|------------------------------|
| [Codeception](https://github.com/FriendsOfShopware/FroshCodeCeptionTests) | Codeception Testsuite for default Responsive Theme         | Tim Windelschmidt ([@fionera](https://github.com/fionera)) |
| [Profiler](https://github.com/FriendsOfShopware/FroshProfiler)    | Symfony Profiler ported to Shopware with custom collectors | Soner Sayakci ([@shyim](https://github.com/shyim))       |
| [Grafana](https://github.com/FriendsOfShopware/FroshGrafana)     | Track your shopware and server statistics within Grafana   | Kai Neuwerth ([@Crease29](https://github.com/Crease29))      |
| [TemplateMail](https://github.com/FriendsOfShopware/FroshGrafana)     | Store mail templates in theme   | Soner Sayakci ([@shyim](https://github.com/shyim))      |
