A few walls written by me that block common attacks that people use while trying to attack cloudflare protected sites.

The allow rules allow connections by useragent to allow your site to be picked up by google and other various types of crawlers so your site will be properly displated on google / other search engines

The challenge captcha rules block checkhost, which is commonly used by attackers to ping your site if it's already dropping the attackers connection because checkhost uses multiple servers to check the ping. It also challenges ASNs of ranges with vulnerable devices, commonly those that would be infected with malware used in botnets.

The block rules block by a few ASNs, also blocks some referers which use to bypass cloudflares under attack mode / challenge rules.
