=== Release listener for GitHub ===
Contributors: piupiiu
Tags: github, release, webhook
Requires at least: 4.0
Tested up to: 4.7.2
Stable tag: trunk
License: GPLv2

Listens to a GitHub webhook and creates a new post every time a release is made.

== Description ==
A new post (or a custom post type is that option is selected) will be created every time a release is made on GitHub. You can display the release post with your other posts or use the shortcode to generate changelogs or links to the latest release.

== Installation ==
1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress

Setup:

1. Open plugin settings (Settings > GitHub release listener)
1. Go to your project settings on GitHub
1. Select Webhooks > Add webhook
1. Copy payload URL from the plugin settings to GitHub
1. Select 'application/json' as content type
1. Create a passcode (a random string) and copy it to 'Secret' field on both plugin settings and GitHub
1. Choose 'Let me select individual events' as triggers
1. Tick 'Release' and untick everything else
1. Save your plugin settings
1. Click 'Add webhook' on GitHub

== Screenshots ==
1. Options

== Changelog ==

= 1.1 =
* Changed the array syntaxt to support old PHP versions.
