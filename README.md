# mediawiki-pages-HealdInterface

# Requirements

* PageExchange

# Setup

* Add the following to the bottom of your LocalSettings.php: `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/WikiTeq/mediawiki-pages-HealdInterface/master/page-exchange.json';`
* Navigate to `Special:Packages` and install the package.
* (Optional) Run `php maintenance/runJobs.php`.
