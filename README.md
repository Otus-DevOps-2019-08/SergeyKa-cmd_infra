# SergeyKa-cmd_infra

## Homework for 4 lesson
+ Slack+Travis connectivity issues: no notifications on #sergey_karakulanov Slack channel
+ gem install travis issues:
________________________________________________________________________________________________
Terminal tracking:
sergeyka@ubuntux940  ~/Downloads/rubygems-3.0.6  gem install travis -V
Getting SRV record failed: DNS result has no information for _rubygems._tcp.rubygems.org
HEAD https://rubygems.org/api/v1/dependencies
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=travis
200 OK
Getting SRV record failed: DNS result has no information for _rubygems._tcp.rubygems.org
GET https://rubygems.org/quick/Marshal.4.8/travis-1.8.10.gemspec.rz
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=backports,faraday,faraday_middleware,gh,highline,launchy,pusher-client,typhoeus
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=ethon
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=multipart-post
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=addressable,multi_json,net-http-persistent,net-http-pipeline
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=ffi
200 OK
GET https://rubygems.org/api/v1/dependencies?gems=json,websocket
200 OK
GET https://rubygems.org/quick/Marshal.4.8/multipart-post-2.1.1.gemspec.rz
200 OK
Downloading gem multipart-post-2.1.1.gem
GET https://rubygems.org/gems/multipart-post-2.1.1.gem
Fetching: multipart-post-2.1.1.gem (100%)
200 OK
ERROR:  While executing gem ... (Gem::FilePermissionError)
    # You don't have write permissions for the /var/lib/gems/2.5.0 directory.
____________________________________________________________________________________________
+ using sudo gem install travis -V & DNS configured to default 8.8.8.8, 8.8.4.4 fixed issues


SergeyKa-cmd Infra repository
