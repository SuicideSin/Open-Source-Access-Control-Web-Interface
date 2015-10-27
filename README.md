Open Access Control Web Interface
==

Web software for managing a database of members in a collaborative grassroots workshop, and also controlling Arclight of 23b Hackerspace's Arduino access control system via Ethernet ( see: https://github.com/zyphlar/Open_Access_Control_Ethernet )

https://github.com/zyphlar/Open-Source-Access-Control-Web-Interface

Copyright Will Bradley, 2012-2014
Distributed under a Creative Commons Attribution 3.0 license http://creativecommons.org/licenses/by/3.0/

![screenshot](https://cloud.githubusercontent.com/assets/48434/8439253/a9a810e6-1f1f-11e5-8b5c-3f0b22f14a9f.png)

Contributions welcome! Simply send a pull request via Github.

To use:

* Install Imagemagick (for Paperclip / image uploads)
* Install arp-scan (for LAN Mac address scanning)
* Load into a Rails 3 environment
* Copy config/config.yml.example to config/config.yml and edit appropriately
* Copy config/database.yml.example to config/database.yml and edit appropriately
* Copy env.example to .env and edit appropriately for your Amazon S3 account OR adjust the resource.rb and contract.rb model settings to use different storage for picture attachments (via Paperclip)
* Copy config/initializers/secret_token.rb.example to config/config/initializers/secret_token.rb and edit appropriately
* See/edit db/seeds.rb for the initial admin account info.
* Run bundle install, rake db:migrate, rake db:seed, etc.
