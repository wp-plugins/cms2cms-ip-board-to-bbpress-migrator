=== CMS2CMS IP Board to bbPress Migrator  ===
Contributors: cms2cms
Tags: IP Board to bbPress, IP Board to bbPress migration, convert IP Board to bbPress, migrate IP Board to bbPress, bbPress, IP.Board, bbpress migration
Requires at least: 3.0.0
Tested up to: 3.9.1
Stable tag: 3.6.2
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

If you are about to migrate your website from IP Board to bbPress, this plugin can help to transfer your content automatically and with no programming skills needed.

== Description ==

If you are about to migrate your website from IP Board to bbPress, this plugin can help to transfer your content automatically and with no programming skills needed. The whole migration takes from a few minutes to a couple of hours  depending on how many topics/replies and other content your forum has got.   

* *There is Free Demo available (migration of limited number of posts, threads, etc.).*
* *Full Migration starts from $39.*

= What is converted from IP Board to bbPress forum? =
* replies
* threads
* categories
* users
* tags
* attachments

= Features: =
- clearing data from WordPress website before moving data in there (optional)
- relations between categories/posts are preserved
- free Demo available - so that you can see how it works before making the payment.
- live chat & ticket support before, during and after migration.

= Video =
[youtube https://www.youtube.com/watch?v=k5JeNf0wg58]

More info: http://www.cms2cms.com/supported-cms/ip-board-to-bb-press-migration

IP.Board to bbPress migrator installs the bridge on your WordPress website, required for data interaction between the Invision Power Board and bbPress databases. To complete the migration, you will be redirected to CMS2CMS website after you activate the plugin.

= Important. Website design (styles, themes, templates) isn’t converted. =

= Pre-Migration Checklist= 
- WordPress and bbPress should be installed before the migration.
- WordPress website should be available online to perform the migration. 
- Have IP.Board site FTP access details (host, username, password).

== Installation ==

1. Download the plugin zip file
1. Extract plugin zip file to your PC
1. Upload extracted file to wp-content/plugin directory
1. Go to Admin -> Plugins, find “CMS2CMS IP Board to bbPress Migrator” and click Activate
1. You’ll be redirected to CMS2CMS website in order to complete your migration

== Frequently Asked Questions ==

= Your website is unreachable =
If your website cannot be reached, pay attention to the following points:
1. Make sure your site is available online at the moment.
2. It’s possible that your firewall blocks certain IP requests. Contact your system administrator or hosting provider support for details about this issue.

= Your server responds with 401 Unauthorized =
If you get this error, try the following solutions:
1. Ensure that access to your site content is not blocked by HTTP Basic Authentication (http://en.wikipedia.org/wiki/Basic_access_authentication). HTTP Basic Authentication is a protection method which requests additional login and password to access webpage or other resource.
2. Make sure that your website content is available on the Internet during the Migration process.

= Your server responds with 403 Forbidden =
This error means that access to certain files or folders is limited. Find below the possible solutions:
1. Your firewall may be causing this by blocking access to the server for our IP addresses. Please, contact your hosting provider and ask them to add the following IPs to the white-list:
92.52.129.82
204.62.12.42
Port 80.
This is done to enable data exchange between your websites. After the migration is complete, you’ll be able to remove our IPs from the white list.
2. Check the access permissions. For ‘cms2cms’ folder specify the file permissions 755. For files in the ‘cms2cms’ folder specify permissions 644.
3. Find out whether there are access restrictions for bridge file. Usually, restrictions are specified in .htaccess file. Contact your system administrator for details.

= Your server responds with 413 Request Entity Too Large =
It indicates that the request is too large for your server. These are possible solutions:
Increase values for the following parameters: ‘memory_limit’ and ‘post_max_size’ in PHP configuration.
If the module suhosin for PHP is installed on the server, increase the parameter ‘suhosin.post.max_value_length’. Usually, the value of 32 Mb is enough.

= Your server responds with 500 Server Error =
Incorrect permissions for bridge folder are the most common reason of this internal server error.
1. for \'cms2cms\' folder, specify the file permissions 755
2. for \'index.php\', \'bridge.php\' and \'key.php\' files in \'cms2cms\' folder, specify the permissions 644
3. If it won’t help, contact your system administrator who can provide you with server logs access for further error detection. You can also request technical assistance from your hosting provider.

= Failed to connect to host / Operation timed out / Nothing was returned from the server / The connection to your server has timed out =
Each of these errors indicates that your website cannot be reached online. Solutions are as follows:
1. Make sure your site is available online at the moment.
2. It’s possible that your firewall blocks certain IP requests. Contact your system administrator or hosting provider support for details about this issue.

= POST Method Not Allowed =
This is a server error. Contact your system administrator or your hosting provider support to have POST method allowed for your server.

= Site is connected already by another account =
Each CMS2CMS user has the unique key which can be found in the Bridge file. So, the Bridge of user A is different from the Bridge of user B. If you have downloaded a bridge using one account, but you try to migrate with this bridge under another account, you get this error.

To fix it, you should either download the bridge again under the account you are going to use for migration or login to the account you used previously to download the Bridge file.

= Invalid response received =
Сontact us at support@cms2cms.com.

= An error occurred when trying to connect to your site =
Сontact us at support@cms2cms.com.

= An unknown error occurred =
Сontact us at support@cms2cms.com.

== Screenshots ==

1. /assets/screenshot-1.png
2. /assets/screenshot-2.png
3. /assets/screenshot-3.png
4. /assets/screenshot-4.png
5. /assets/screenshot-5.png

== Changelog ==

= 2.0.2 =
* Bug fixes

= 2.0.1 =
* Improved Connection Bridge

= 1.0.3 =
* Bug fixes

= 1.0.2 =
* Bug fixes

= 1.0.1 =
* Added German Language
* Minor fixes of html

= 1.0 =
* Initial commit
