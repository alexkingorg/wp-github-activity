# WP GitHub Activity

* Contributors: alexkingorg, crowdfavorite
* Tags: github, feed, activity, contribution, log, shortcode, widget, filter
* Requires at least: 3.5.2
* Tested up to: 3.5.2
* Stable tag: 1.0
* License: GPLv2
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display the recent activity from your GitHub account via shortcode or widget.

## Description

Pulls your activity feed from GitHub (with local caching) and allows you to display it via shortcode or widget.

You can even specify types of updates to exclude from the list (for example, you might decide 'watching' a reposity isn't noteworthy).

**Contributing**

The development home for this plugin is on GitHub. This is where active development happens, along with issue tracking and associated discussions.

https://github.com/alexkingorg/wp-github-activity

**Support**

Support for this plugin will be provided in the form of _Product Support_. This means that I intend to fix any confirmed bugs and improve the user experience when enhancements are identified and can reasonably be accomodated. There is no _User Support_ provided for this plugin. If you are having trouble with this plugin in your particular installation of WordPress, I will not be able to help you troubleshoot the problem.

This plugin is provided under the terms of the GPL, including the following:

> BECAUSE THE PROGRAM IS LICENSED FREE OF CHARGE, THERE IS NO WARRANTY
> FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW.  EXCEPT WHEN
> OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES
> PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED
> OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
> MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.  THE ENTIRE RISK AS
> TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU.  SHOULD THE
> PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING,
> REPAIR OR CORRECTION.

## Installation

1. Upload `wp-github-activity.php` or the `wp-github-activity` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Display your recent GitHub activity by adding the shortcode to a post or page, or the widget to a sidebar.

**Shortcode Syntax**

[github_activity username="alexkingorg" count="5" excluded="create, watch"]

The excluded parameter is optional, and uses the keywords included in the HTML comment that appears just before each GitHub activity item.

## Frequently Asked Questions

### Can I list activity for more than one user? 

Sure, just add another widget or shortcode with the desired username.

## Changelog

### 1.0 
* First public release.

