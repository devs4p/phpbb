[![phpBB](https://www.phpbb.com/theme/images/logos/blue/160x52.png)](http://www.phpbb.com)

## ABOUT

phpBB is a free open-source bulletin board written in PHP. Modified by devs4p

## COMMUNITY

Get your copy of phpBB, find support and lots more on [phpBB.com](http://www.phpbb.com)! Discuss the development on [area51](http://area51.phpbb.com/phpBB/index.php).

## INSTALLING DEPENDENCIES

To be able to run an installation from the repo (and not from a pre-built package) you need to run the following commands to install phpBB's dependencies.

	cd phpBB
	php ../composer.phar install


## CONTRIBUTE

1. [Create an account on phpBB.com](http://www.phpbb.com/community/ucp.php?mode=register)
2. [Create a ticket (unless there already is one)](http://tracker.phpbb.com/secure/CreateIssue!default.jspa)
3. Read our [Coding guidelines](https://wiki.phpbb.com/Coding_guidelines) and [Git Contribution Guidelines](http://wiki.phpbb.com/Git)
4. Send us a pull request

## VAGRANT

Read our [Vagrant documentation](phpBB/docs/vagrant.md) to find out how to use Vagrant to develop and contribute to phpBB.

## AUTOMATED TESTING

We have unit and functional tests in order to prevent regressions. You can view the bamboo continuous integration [here](http://bamboo.phpbb.com) or check our travis builds below:

* [![Build Status](https://secure.travis-ci.org/phpbb/phpbb.png?branch=master)](http://travis-ci.org/phpbb/phpbb) **master** - Latest development version
* [![Build Status](https://secure.travis-ci.org/phpbb/phpbb.png?branch=3.2.x)](http://travis-ci.org/phpbb/phpbb) **3.2.x** - Development of version 3.2.x
* [![Build Status](https://secure.travis-ci.org/phpbb/phpbb.png?branch=3.1.x)](http://travis-ci.org/phpbb/phpbb) **3.1.x** - Development of version 3.1.x

## LICENSE

[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)
