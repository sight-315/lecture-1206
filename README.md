# テクノロジー（藤原）12/6授業

## Bashの実行ログ

```
sight315:~/workspace $ cd lecture-1129/asagao
sight315:~/workspace/lecture-1129/asagao (master) $ bundle install
The latest bundler is 1.16.0, but you are currently running 1.15.4.
To update, run `gem install bundler`
The git source `git://github.com/flori/json.git` uses the `git` protocol, which transmits data without encryption. Disable this warning with `bundle config git.allow_insecure true`, or switch to the `https` protocol to keep your data secure.
Warning: the running version of Bundler (1.15.4) is older than the version that created the lockfile (1.16.0). We suggest you upgrade to the latest version of Bundler by running `gem install bundler`.
Using rake 12.2.1
Using concurrent-ruby 1.0.5
Using minitest 5.10.3
Using thread_safe 0.3.6
Using builder 3.2.3
Using erubis 2.7.0
Using mini_portile2 2.3.0
Using crass 1.0.2
Using rack 1.6.8
Using mini_mime 0.1.4
Using arel 6.0.4
Using debug_inspector 0.0.3
Using bundler 1.15.4
Using byebug 9.1.0
Using coffee-script-source 1.8.0
Using execjs 2.7.0
Using thor 0.20.0
Using ffi 1.9.18
Using multi_json 1.12.2
Using json 1.8.6 from git://github.com/flori/json.git (at v1.8@7f4cfd8)
Using rb-fsevent 0.10.2
Using rdoc 4.3.0
Using tilt 2.0.8
Using sqlite3 1.3.13
Using turbolinks-source 5.0.3
Using i18n 0.9.1
Using tzinfo 1.2.4
Using nokogiri 1.8.1
Using rack-test 0.6.3
Using sprockets 3.7.1
Using mail 2.7.0
Using binding_of_caller 0.7.3
Using coffee-script 2.4.1
Using uglifier 3.2.0
Using rb-inotify 0.9.10
Using sdoc 0.4.2
Using turbolinks 5.0.1
Using activesupport 4.2.10
Using loofah 2.1.1
Using sass-listen 4.0.0
Using rails-deprecated_sanitizer 1.0.3
Using globalid 0.4.1
Using activemodel 4.2.10
Using jbuilder 2.7.0
Using spring 2.0.2
Using rails-html-sanitizer 1.0.3
Using sass 3.5.3
Using rails-dom-testing 1.0.8
Using activejob 4.2.10
Using activerecord 4.2.10
Using actionview 4.2.10
Using actionpack 4.2.10
Using actionmailer 4.2.10
Using railties 4.2.10
Using sprockets-rails 3.2.1
Using coffee-rails 4.1.1
Using jquery-rails 4.3.1
Using rails 4.2.10
Using sass-rails 5.0.6
Using web-console 2.3.0
Bundle complete! 15 Gemfile dependencies, 60 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
sight315:~/workspace/lecture-1129/asagao (master) $ bin/rails g controller lesson
      create  app/controllers/lesson_controller.rb
      invoke  erb
      create    app/views/lesson
sight315:~/workspace/lecture-1129/asagao (master) $ bin/rails s -b $IP -p $PORT
=> Booting WEBrick
=> Rails 4.2.10 application starting in development on http://0.0.0.0:8080
=> Run `rails server -h` for more startup options
=> Ctrl-C to shutdown server
[2017-12-06 01:12:38] INFO  WEBrick 1.3.1
[2017-12-06 01:12:38] INFO  ruby 2.4.0 (2016-12-24) [x86_64-linux]
[2017-12-06 01:12:38] INFO  WEBrick::HTTPServer#start: pid=1719 port=8080


Started GET "/" for 125.204.151.95 at 2017-12-06 01:12:44 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by TopController#index as HTML
  Rendered top/index.html.erb within layouts/application (1.8ms)
Completed 200 OK in 357ms (Views: 344.7ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step1/Sato" for 125.204.151.95 at 2017-12-06 01:13:16 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step1 as HTML
  Parameters: {"name"=>"Sato"}
  Rendered text template (0.0ms)
Completed 200 OK in 7ms (Views: 6.3ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step1/sight" for 125.204.151.95 at 2017-12-06 01:14:21 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step1 as HTML
  Parameters: {"name"=>"sight"}
  Rendered text template (0.0ms)
Completed 200 OK in 1ms (Views: 0.4ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step2" for 125.204.151.95 at 2017-12-06 01:18:29 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step2 as HTML
  Rendered text template (0.0ms)
Completed 200 OK in 3ms (Views: 2.2ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step8" for 125.204.151.95 at 2017-12-06 01:21:58 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step8 as HTML
  Rendered lesson/step8.html.erb within layouts/application (0.5ms)
Completed 200 OK in 15ms (Views: 14.5ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step8" for 125.204.151.95 at 2017-12-06 01:28:49 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step8 as HTML
  Rendered lesson/step8.html.erb within layouts/application (0.1ms)
Completed 200 OK in 30ms (Views: 29.6ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step8" for 125.204.151.95 at 2017-12-06 01:34:05 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step8 as HTML
  Rendered lesson/step8.html.erb within layouts/application (0.4ms)
Completed 200 OK in 41ms (Views: 40.7ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step9" for 125.204.151.95 at 2017-12-06 01:35:11 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step9 as HTML
  Rendered lesson/step8.html.erb within layouts/application (0.1ms)
Completed 200 OK in 12ms (Views: 11.0ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step10" for 125.204.151.95 at 2017-12-06 01:35:58 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step10 as HTML
Completed 500 Internal Server Error in 9ms (ActiveRecord: 0.0ms)

ActionView::MissingTemplate (Missing template lesson/step10, application/step10 with {:locale=>[:en], :formats=>[:html], :variants=>[], :handlers=>[:erb, :builder, :raw, :ruby, :coffee, :jbuilder]}. Searched in:
  * "/home/ubuntu/workspace/lecture-1129/asagao/app/views"
):
  actionview (4.2.10) lib/action_view/path_set.rb:46:in `find'
  actionview (4.2.10) lib/action_view/lookup_context.rb:121:in `find'
  actionview (4.2.10) lib/action_view/renderer/abstract_renderer.rb:18:in `find_template'
  actionview (4.2.10) lib/action_view/renderer/template_renderer.rb:40:in `determine_template'
  actionview (4.2.10) lib/action_view/renderer/template_renderer.rb:8:in `render'
  actionview (4.2.10) lib/action_view/renderer/renderer.rb:46:in `render_template'
  actionview (4.2.10) lib/action_view/renderer/renderer.rb:27:in `render'
  actionview (4.2.10) lib/action_view/rendering.rb:100:in `_render_template'
  actionpack (4.2.10) lib/action_controller/metal/streaming.rb:217:in `_render_template'
  actionview (4.2.10) lib/action_view/rendering.rb:83:in `render_to_body'
  actionpack (4.2.10) lib/action_controller/metal/rendering.rb:32:in `render_to_body'
  actionpack (4.2.10) lib/action_controller/metal/renderers.rb:37:in `render_to_body'
  actionpack (4.2.10) lib/abstract_controller/rendering.rb:25:in `render'
  actionpack (4.2.10) lib/action_controller/metal/rendering.rb:16:in `render'
  actionpack (4.2.10) lib/action_controller/metal/instrumentation.rb:44:in `block (2 levels) in render'
  activesupport (4.2.10) lib/active_support/core_ext/benchmark.rb:12:in `block in ms'
  /usr/local/rvm/rubies/ruby-2.4.0/lib/ruby/2.4.0/benchmark.rb:308:in `realtime'
  activesupport (4.2.10) lib/active_support/core_ext/benchmark.rb:12:in `ms'
  actionpack (4.2.10) lib/action_controller/metal/instrumentation.rb:44:in `block in render'
  actionpack (4.2.10) lib/action_controller/metal/instrumentation.rb:87:in `cleanup_view_runtime'
  activerecord (4.2.10) lib/active_record/railties/controller_runtime.rb:25:in `cleanup_view_runtime'
  actionpack (4.2.10) lib/action_controller/metal/instrumentation.rb:43:in `render'
  actionpack (4.2.10) lib/action_controller/metal/implicit_render.rb:10:in `default_render'
  actionpack (4.2.10) lib/action_controller/metal/implicit_render.rb:5:in `send_action'
  actionpack (4.2.10) lib/abstract_controller/base.rb:198:in `process_action'
  actionpack (4.2.10) lib/action_controller/metal/rendering.rb:10:in `process_action'
  actionpack (4.2.10) lib/abstract_controller/callbacks.rb:20:in `block in process_action'
  activesupport (4.2.10) lib/active_support/callbacks.rb:117:in `call'
  activesupport (4.2.10) lib/active_support/callbacks.rb:555:in `block (2 levels) in compile'
  activesupport (4.2.10) lib/active_support/callbacks.rb:505:in `call'
  activesupport (4.2.10) lib/active_support/callbacks.rb:92:in `__run_callbacks__'
  activesupport (4.2.10) lib/active_support/callbacks.rb:778:in `_run_process_action_callbacks'
  activesupport (4.2.10) lib/active_support/callbacks.rb:81:in `run_callbacks'
  actionpack (4.2.10) lib/abstract_controller/callbacks.rb:19:in `process_action'
  actionpack (4.2.10) lib/action_controller/metal/rescue.rb:29:in `process_action'
  actionpack (4.2.10) lib/action_controller/metal/instrumentation.rb:32:in `block in process_action'
  activesupport (4.2.10) lib/active_support/notifications.rb:164:in `block in instrument'
  activesupport (4.2.10) lib/active_support/notifications/instrumenter.rb:20:in `instrument'
  activesupport (4.2.10) lib/active_support/notifications.rb:164:in `instrument'
  actionpack (4.2.10) lib/action_controller/metal/instrumentation.rb:30:in `process_action'
  actionpack (4.2.10) lib/action_controller/metal/params_wrapper.rb:250:in `process_action'
  activerecord (4.2.10) lib/active_record/railties/controller_runtime.rb:18:in `process_action'
  actionpack (4.2.10) lib/abstract_controller/base.rb:137:in `process'
  actionview (4.2.10) lib/action_view/rendering.rb:30:in `process'
  actionpack (4.2.10) lib/action_controller/metal.rb:196:in `dispatch'
  actionpack (4.2.10) lib/action_controller/metal/rack_delegation.rb:13:in `dispatch'
  actionpack (4.2.10) lib/action_controller/metal.rb:237:in `block in action'
  actionpack (4.2.10) lib/action_dispatch/routing/route_set.rb:74:in `dispatch'
  actionpack (4.2.10) lib/action_dispatch/routing/route_set.rb:43:in `serve'
  actionpack (4.2.10) lib/action_dispatch/journey/router.rb:43:in `block in serve'
  actionpack (4.2.10) lib/action_dispatch/journey/router.rb:30:in `each'
  actionpack (4.2.10) lib/action_dispatch/journey/router.rb:30:in `serve'
  actionpack (4.2.10) lib/action_dispatch/routing/route_set.rb:817:in `call'
  rack (1.6.8) lib/rack/etag.rb:24:in `call'
  rack (1.6.8) lib/rack/conditionalget.rb:25:in `call'
  rack (1.6.8) lib/rack/head.rb:13:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/params_parser.rb:27:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/flash.rb:260:in `call'
  rack (1.6.8) lib/rack/session/abstract/id.rb:225:in `context'
  rack (1.6.8) lib/rack/session/abstract/id.rb:220:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/cookies.rb:560:in `call'
  activerecord (4.2.10) lib/active_record/query_cache.rb:36:in `call'
  activerecord (4.2.10) lib/active_record/connection_adapters/abstract/connection_pool.rb:653:in `call'
  activerecord (4.2.10) lib/active_record/migration.rb:377:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/callbacks.rb:29:in `block in call'
  activesupport (4.2.10) lib/active_support/callbacks.rb:88:in `__run_callbacks__'
  activesupport (4.2.10) lib/active_support/callbacks.rb:778:in `_run_call_callbacks'
  activesupport (4.2.10) lib/active_support/callbacks.rb:81:in `run_callbacks'
  actionpack (4.2.10) lib/action_dispatch/middleware/callbacks.rb:27:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/reloader.rb:73:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/remote_ip.rb:78:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/debug_exceptions.rb:17:in `call'
  web-console (2.3.0) lib/web_console/middleware.rb:20:in `block in call'
  web-console (2.3.0) lib/web_console/middleware.rb:18:in `catch'
  web-console (2.3.0) lib/web_console/middleware.rb:18:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/show_exceptions.rb:30:in `call'
  railties (4.2.10) lib/rails/rack/logger.rb:38:in `call_app'
  railties (4.2.10) lib/rails/rack/logger.rb:20:in `block in call'
  activesupport (4.2.10) lib/active_support/tagged_logging.rb:68:in `block in tagged'
  activesupport (4.2.10) lib/active_support/tagged_logging.rb:26:in `tagged'
  activesupport (4.2.10) lib/active_support/tagged_logging.rb:68:in `tagged'
  railties (4.2.10) lib/rails/rack/logger.rb:20:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/request_id.rb:21:in `call'
  rack (1.6.8) lib/rack/methodoverride.rb:22:in `call'
  rack (1.6.8) lib/rack/runtime.rb:18:in `call'
  activesupport (4.2.10) lib/active_support/cache/strategy/local_cache_middleware.rb:28:in `call'
  rack (1.6.8) lib/rack/lock.rb:17:in `call'
  actionpack (4.2.10) lib/action_dispatch/middleware/static.rb:120:in `call'
  rack (1.6.8) lib/rack/sendfile.rb:113:in `call'
  railties (4.2.10) lib/rails/engine.rb:518:in `call'
  railties (4.2.10) lib/rails/application.rb:165:in `call'
  rack (1.6.8) lib/rack/lock.rb:17:in `call'
  rack (1.6.8) lib/rack/content_length.rb:15:in `call'
  rack (1.6.8) lib/rack/handler/webrick.rb:88:in `service'
  /usr/local/rvm/rubies/ruby-2.4.0/lib/ruby/2.4.0/webrick/httpserver.rb:140:in `service'
  /usr/local/rvm/rubies/ruby-2.4.0/lib/ruby/2.4.0/webrick/httpserver.rb:96:in `run'
  /usr/local/rvm/rubies/ruby-2.4.0/lib/ruby/2.4.0/webrick/server.rb:290:in `block in start_thread'


  Rendered /usr/local/rvm/gems/ruby-2.4.0@global/gems/actionpack-4.2.10/lib/action_dispatch/middleware/templates/rescues/_source.erb (4.9ms)
  Rendered /usr/local/rvm/gems/ruby-2.4.0@global/gems/actionpack-4.2.10/lib/action_dispatch/middleware/templates/rescues/_trace.html.erb (2.4ms)
  Rendered /usr/local/rvm/gems/ruby-2.4.0@global/gems/actionpack-4.2.10/lib/action_dispatch/middleware/templates/rescues/_request_and_response.html.erb (1.1ms)
  Rendered /usr/local/rvm/gems/ruby-2.4.0@global/gems/actionpack-4.2.10/lib/action_dispatch/middleware/templates/rescues/missing_template.html.erb within rescues/layout (36.5ms)


Started GET "/lesson/step10" for 125.204.151.95 at 2017-12-06 01:36:50 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step10 as HTML
  Rendered lesson/step10.html.erb within layouts/application (0.4ms)
Completed 200 OK in 10ms (Views: 9.8ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step16" for 125.204.151.95 at 2017-12-06 01:38:05 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step16 as HTML
  Rendered lesson/step16.html.erb within layouts/application (0.7ms)
Completed 200 OK in 10ms (Views: 9.5ms | ActiveRecord: 0.0ms)


Started GET "/" for 125.204.151.95 at 2017-12-06 01:38:09 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by TopController#index as HTML
  Rendered top/index.html.erb within layouts/application (0.1ms)
Completed 200 OK in 13ms (Views: 12.7ms | ActiveRecord: 0.0ms)
^C[2017-12-06 01:38:49] INFO  going to shutdown ...
[2017-12-06 01:38:49] INFO  WEBrick::HTTPServer#start done.
Exiting
sight315:~/workspace/lecture-1129/asagao (master) $ cd app/assets/images/
sight315:~/workspace/lecture-1129/asagao/app/assets/images (master) $ curl -O https://kd-site2017.firebaseapp.com/slides/2017-11-29/images/rails.png
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 84889  100 84889    0     0   121k      0 --:--:-- --:--:-- --:--:--  121k
sight315:~/workspace/lecture-1129/asagao/app/assets/images (master) $ ls
rails.png
sight315:~/workspace/lecture-1129/asagao/app/assets/images (master) $ cd ../../../
sight315:~/workspace/lecture-1129/asagao (master) $ bin/rails s -b $IP -p $PORT
=> Booting WEBrick
=> Rails 4.2.10 application starting in development on http://0.0.0.0:8080
=> Run `rails server -h` for more startup options
=> Ctrl-C to shutdown server
[2017-12-06 01:52:13] INFO  WEBrick 1.3.1
[2017-12-06 01:52:13] INFO  ruby 2.4.0 (2016-12-24) [x86_64-linux]
[2017-12-06 01:52:13] INFO  WEBrick::HTTPServer#start: pid=1901 port=8080


Started GET "/lesson/step17" for 125.204.151.95 at 2017-12-06 01:52:15 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step17 as HTML
  Rendered lesson/step17.html.erb within layouts/application (226.5ms)
Completed 200 OK in 321ms (Views: 307.3ms | ActiveRecord: 0.0ms)


Started GET "/assets/rails-03bb170d74e34a9d3ab9157113c6ab68d2eb4a61a1a7ec5f77e45bc55d9e168e.png" for 125.204.151.95 at 2017-12-06 01:52:17 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255


Started GET "/lesson/step18" for 125.204.151.95 at 2017-12-06 01:54:05 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step18 as HTML
  Rendered lesson/step18.html.erb within layouts/application (0.6ms)
Completed 200 OK in 14ms (Views: 13.6ms | ActiveRecord: 0.0ms)


Started GET "/lesson/step19" for 125.204.151.95 at 2017-12-06 01:56:21 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by LessonController#step19 as HTML
  Rendered lesson/step19.html.erb within layouts/application (11.2ms)
Completed 200 OK in 31ms (Views: 30.1ms | ActiveRecord: 0.0ms)


Started GET "/" for 125.204.151.95 at 2017-12-06 01:56:45 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by TopController#index as HTML
  Rendered top/index.html.erb within layouts/application (0.8ms)
Completed 200 OK in 146ms (Views: 145.2ms | ActiveRecord: 0.0ms)
^C[2017-12-06 01:57:26] INFO  going to shutdown ...
[2017-12-06 01:57:26] INFO  WEBrick::HTTPServer#start done.
Exiting
sight315:~/workspace/lecture-1129/asagao (master) $ cd ~/workspace/lecture-1129
sight315:~/workspace/lecture-1129 (master) $ git add *
sight315:~/workspace/lecture-1129 (master) $ git commit -m '11/29 Rails 課題'
[master 407a4c7] 11/29 Rails 課題
 10 files changed, 58 insertions(+), 10 deletions(-)
 create mode 100644 asagao/app/assets/images/rails.png
 create mode 100644 asagao/app/controllers/lesson_controller.rb
 create mode 100644 asagao/app/views/lesson/step10.html.erb
 create mode 100644 asagao/app/views/lesson/step16.html.erb
 create mode 100644 asagao/app/views/lesson/step17.html.erb
 create mode 100644 asagao/app/views/lesson/step18.html.erb
 create mode 100644 asagao/app/views/lesson/step19.html.erb
 create mode 100644 asagao/app/views/lesson/step8.html.erb
sight315:~/workspace/lecture-1129 (master) $ git push
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
Counting objects: 20, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (17/17), done.
Writing objects: 100% (20/20), 85.23 KiB | 17.04 MiB/s, done.
Total 20 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To github.com:sight-315/lecture-1129.git
   7d68d27..407a4c7  master -> master
sight315:~/workspace/lecture-1129 (master) $ cd ~/workspace
sight315:~/workspace $ git clone git@github.com:sight-315/lecture-1206.git
Cloning into 'lecture-1206'...
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
remote: Counting objects: 95, done.
remote: Compressing objects: 100% (79/79), done.
remote: Total 95 (delta 2), reused 95 (delta 2), pack-reused 0
Receiving objects: 100% (95/95), 38.69 KiB | 226.00 KiB/s, done.
Resolving deltas: 100% (2/2), done.
sight315:~/workspace $ cd lecture-1206/asagao
sight315:~/workspace/lecture-1206/asagao (master) $ bundle install

The latest bundler is 1.16.0, but you are currently running 1.15.4.
To update, run `gem install bundler`
The git source `git://github.com/flori/json.git` uses the `git` protocol, which transmits data without encryption. Disable this warning with `bundle config git.allow_insecure true`, or switch to the `https` protocol to keep your data secure.
Warning: the running version of Bundler (1.15.4) is older than the version that created the lockfile (1.16.0). We suggest you upgrade to the latest version of Bundler by running `gem install bundler`.
Using rake 12.2.1
Using concurrent-ruby 1.0.5
Using minitest 5.10.3
Using thread_safe 0.3.6
Using builder 3.2.3
Using erubis 2.7.0
Using mini_portile2 2.3.0
Using crass 1.0.2
Using rack 1.6.8
Using mini_mime 0.1.4
Using arel 6.0.4
Using debug_inspector 0.0.3
Using bundler 1.15.4
Using byebug 9.1.0
Using coffee-script-source 1.8.0
Using execjs 2.7.0
Using thor 0.20.0
Using ffi 1.9.18
Using multi_json 1.12.2
Using json 1.8.6 from git://github.com/flori/json.git (at v1.8@7f4cfd8)
Using rb-fsevent 0.10.2
Using rdoc 4.3.0
Using tilt 2.0.8
Using sqlite3 1.3.13
Using turbolinks-source 5.0.3
Using i18n 0.9.1
Using tzinfo 1.2.4
Using nokogiri 1.8.1
Using rack-test 0.6.3
Using sprockets 3.7.1
Using mail 2.7.0
Using binding_of_caller 0.7.3
Using coffee-script 2.4.1
Using uglifier 3.2.0
Using rb-inotify 0.9.10
Using sdoc 0.4.2
Using turbolinks 5.0.1
Using activesupport 4.2.10
Using loofah 2.1.1
Using sass-listen 4.0.0
Using rails-deprecated_sanitizer 1.0.3
Using globalid 0.4.1
Using activemodel 4.2.10
Using jbuilder 2.7.0
Using spring 2.0.2
Using rails-html-sanitizer 1.0.3
Using sass 3.5.3
Using rails-dom-testing 1.0.8
Using activejob 4.2.10
Using activerecord 4.2.10
Using actionview 4.2.10
Using actionpack 4.2.10
Using actionmailer 4.2.10
Using railties 4.2.10
Using sprockets-rails 3.2.1
Using coffee-rails 4.1.1
Using jquery-rails 4.3.1
Using rails 4.2.10
Using sass-rails 5.0.6
Using web-console 2.3.0
Bundle complete! 15 Gemfile dependencies, 60 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
sight315:~/workspace/lecture-1206/asagao (master) $ 
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:create
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rails g model member
      invoke  active_record
      create    db/migrate/20171206024551_create_members.rb
      create    app/models/member.rb
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:migrate
== 20171206024551 CreateMembers: migrating ====================================
-- create_table(:members)
   -> 0.0006s
== 20171206024551 CreateMembers: migrated (0.0007s) ===========================

sight315:~/workspace/lecture-1206/asagao (master) $ bin/rails c
Loading development environment (Rails 4.2.10)
2.4.0 :001 > ^C
2.4.0 :001 > ^C
2.4.0 :001 > [3;3~mkdir -p db/seeds/development
2.4.0 :002?>   ls
2.4.0 :003?>   ^C
2.4.0 :003 > ^Z
[1]+  Stopped                 bin/rails c
sight315:~/workspace/lecture-1206/asagao (master) $ mkdir -p db/seeds/development
sight315:~/workspace/lecture-1206/asagao (master) $ touch db/seeds/development/members.rb
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:reset
-- create_table("members", {:force=>:cascade})
   -> 0.0172s
-- initialize_schema_migrations_table()
   -> 0.0502s
-- create_table("members", {:force=>:cascade})
   -> 0.0090s
-- initialize_schema_migrations_table()
   -> 0.0187s
Creating members...
rake aborted!
ActiveRecord::UnknownAttributeError: unknown attribute 'number' for Member.
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:59:in `rescue in _assign_attribute'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:54:in `_assign_attribute'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:41:in `block in assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `each'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:566:in `init_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:281:in `initialize'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/persistence.rb:33:in `create'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:5:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `upto'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `block in require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:6:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `each'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `block in load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-4.2.10/lib/rails/engine.rb:547:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/tasks/database_tasks.rb:253:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:173:in `block (2 levels) in <top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:132:in `block (2 levels) in <top (required)>'

Caused by:
NoMethodError: undefined method `number=' for #<Member id: nil, created_at: nil, updated_at: nil>
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activemodel-4.2.10/lib/active_model/attribute_methods.rb:433:in `method_missing'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:54:in `public_send'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:54:in `_assign_attribute'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:41:in `block in assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `each'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:566:in `init_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:281:in `initialize'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/persistence.rb:33:in `create'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:5:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `upto'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `block in require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:6:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `each'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `block in load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-4.2.10/lib/rails/engine.rb:547:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/tasks/database_tasks.rb:253:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:173:in `block (2 levels) in <top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:132:in `block (2 levels) in <top (required)>'
Tasks: TOP => db:setup => db:seed
(See full trace by running task with --trace)
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:reset
-- create_table("members", {:force=>:cascade})
   -> 0.0143s
-- initialize_schema_migrations_table()
   -> 0.0434s
-- create_table("members", {:force=>:cascade})
   -> 0.0081s
-- initialize_schema_migrations_table()
   -> 0.0155s
Creating members...
rake aborted!
ActiveRecord::UnknownAttributeError: unknown attribute 'number' for Member.
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:59:in `rescue in _assign_attribute'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:54:in `_assign_attribute'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:41:in `block in assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `each'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:566:in `init_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:281:in `initialize'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/persistence.rb:33:in `create'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:5:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `upto'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `block in require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:6:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `each'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `block in load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-4.2.10/lib/rails/engine.rb:547:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/tasks/database_tasks.rb:253:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:173:in `block (2 levels) in <top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:132:in `block (2 levels) in <top (required)>'

Caused by:
NoMethodError: undefined method `number=' for #<Member id: nil, created_at: nil, updated_at: nil>
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activemodel-4.2.10/lib/active_model/attribute_methods.rb:433:in `method_missing'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:54:in `public_send'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:54:in `_assign_attribute'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:41:in `block in assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `each'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/attribute_assignment.rb:35:in `assign_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:566:in `init_attributes'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/core.rb:281:in `initialize'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/inheritance.rb:61:in `new'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/persistence.rb:33:in `create'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:5:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `upto'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds/development/members.rb:4:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `block in require'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:274:in `require'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:6:in `block in <top (required)>'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `each'
/home/ubuntu/workspace/lecture-1206/asagao/db/seeds.rb:2:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `block in load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:240:in `load_dependency'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activesupport-4.2.10/lib/active_support/dependencies.rb:268:in `load'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-4.2.10/lib/rails/engine.rb:547:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/tasks/database_tasks.rb:253:in `load_seed'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:173:in `block (2 levels) in <top (required)>'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/activerecord-4.2.10/lib/active_record/railties/databases.rake:132:in `block (2 levels) in <top (required)>'
Tasks: TOP => db:setup => db:seed
(See full trace by running task with --trace)
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:drop
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:migrate
== 20171206024551 CreateMembers: migrating ====================================
-- create_table(:members)
   -> 0.0009s
== 20171206024551 CreateMembers: migrated (0.0010s) ===========================

sight315:~/workspace/lecture-1206/asagao (master) $ bin/rake db:seed
Creating members...
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rails c
Loading development environment (Rails 4.2.10)
2.4.0 :001 > pp Member.first
  Member Load (0.1ms)  SELECT  "members".* FROM "members"  ORDER BY "members"."id" ASC LIMIT 1
#<Member:0x0000000419e408
 id: 1,
 number: 10,
 name: "Taro",
 full_name: "佐藤 太郎",
 email: "Taro@example.com",
 birthday: Tue, 01 Dec 1981,
 gender: 0,
 administrator: true,
 created_at: Wed, 06 Dec 2017 12:15:58 JST +09:00,
 updated_at: Wed, 06 Dec 2017 12:15:58 JST +09:00>
 => #<Member id: 1, number: 10, name: "Taro", full_name: "佐藤 太郎", email: "Taro@example.com", birthday: "1981-12-01", gender: 0, administrator: true, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58"> 
2.4.0 :002 > 
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rails db
SQLite version 3.8.2 2013-12-06 14:53:30
Enter ".help" for instructions
Enter SQL statements terminated with a ";"
sqlite> .tables
members            schema_migrations
sqlite> .schema members
CREATE TABLE "members" ("id" INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL, "number" integer NOT NULL, "name" varchar NOT NULL, "full_name" varchar, "email" varchar, "birthday" date, "gender" integer DEFAULT 0 NOT NULL, "administrator" boolean DEFAULT 'f' NOT NULL, "created_at" datetime NOT NULL, "updated_at" datetime NOT NULL);
sqlite> SELECT * from members;
1|10|Taro|佐藤 太郎|Taro@example.com|1981-12-01|0|t|2017-12-06 03:15:58.163820|2017-12-06 03:15:58.163820
2|11|Jiro|鈴木 次郎|Jiro@example.com|1981-12-01|0|f|2017-12-06 03:15:58.177367|2017-12-06 03:15:58.177367
3|12|Hana|高橋 花子|Hana@example.com|1981-12-01|1|f|2017-12-06 03:15:58.189243|2017-12-06 03:15:58.189243
4|13|John|田中 太郎|John@example.com|1981-12-01|0|f|2017-12-06 03:15:58.200939|2017-12-06 03:15:58.200939
5|14|Mike|佐藤 次郎|Mike@example.com|1981-12-01|0|f|2017-12-06 03:15:58.210688|2017-12-06 03:15:58.210688
6|15|Sophy|鈴木 花子|Sophy@example.com|1981-12-01|1|f|2017-12-06 03:15:58.225142|2017-12-06 03:15:58.225142
7|16|Bill|高橋 太郎|Bill@example.com|1981-12-01|0|f|2017-12-06 03:15:58.237835|2017-12-06 03:15:58.237835
8|17|Alex|田中 次郎|Alex@example.com|1981-12-01|0|f|2017-12-06 03:15:58.250191|2017-12-06 03:15:58.250191
9|18|Mary|佐藤 花子|Mary@example.com|1981-12-01|1|f|2017-12-06 03:15:58.261994|2017-12-06 03:15:58.261994
10|19|Tom|鈴木 太郎|Tom@example.com|1981-12-01|0|f|2017-12-06 03:15:58.273869|2017-12-06 03:15:58.273869
sqlite> 
sight315:~/workspace/lecture-1206/asagao (master) $ bin/rails c
Loading development environment (Rails 4.2.10)
2.4.0 :001 > Member.ids
   (0.1ms)  SELECT "members"."id" FROM "members"
 => [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 
2.4.0 :002 > member = Member.find(3)
  Member Load (0.4ms)  SELECT  "members".* FROM "members" WHERE "members"."id" = ? LIMIT 1  [["id", 3]]
 => #<Member id: 3, number: 12, name: "Hana", full_name: "高橋 花子", email: "Hana@example.com", birthday: "1981-12-01", gender: 1, administrator: false, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58"> 
2.4.0 :003 > member.email
 => "Hana@example.com" 
2.4.0 :004 > member = Member.find_by(name: "Taro")
  Member Load (0.3ms)  SELECT  "members".* FROM "members" WHERE "members"."name" = ? LIMIT 1  [["name", "Taro"]]
 => #<Member id: 1, number: 10, name: "Taro", full_name: "佐藤 太郎", email: "Taro@example.com", birthday: "1981-12-01", gender: 0, administrator: true, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58"> 
2.4.0 :005 > member = Member.find_by(gender: 0, administrator: false
2.4.0 :006?>   )
  Member Load (0.3ms)  SELECT  "members".* FROM "members" WHERE "members"."gender" = ? AND "members"."administrator" = ? LIMIT 1  [["gender", 0], ["administrator", "f"]]
 => #<Member id: 2, number: 11, name: "Jiro", full_name: "鈴木 次郎", email: "Jiro@example.com", birthday: "1981-12-01", gender: 0, administrator: false, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58"> 
2.4.0 :007 > member = Member.find_by(gender: 1, administrator: true)
  Member Load (0.2ms)  SELECT  "members".* FROM "members" WHERE "members"."gender" = ? AND "members"."administrator" = ? LIMIT 1  [["gender", 1], ["administrator", "t"]]
 => nil 
2.4.0 :008 > member = Member.where(name: "Taro")
  Member Load (0.3ms)  SELECT "members".* FROM "members" WHERE "members"."name" = ?  [["name", "Taro"]]
 => #<ActiveRecord::Relation [#<Member id: 1, number: 10, name: "Taro", full_name: "佐藤 太郎", email: "Taro@example.com", birthday: "1981-12-01", gender: 0, administrator: true, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58">]> 
2.4.0 :009 > puts member.to_sql
SELECT "members".* FROM "members" WHERE "members"."name" = 'Taro'
 => nil 
2.4.0 :010 > members = Member.where(name: "Taro").where("number < 20")
  Member Load (0.3ms)  SELECT "members".* FROM "members" WHERE "members"."name" = ? AND (number < 20)  [["name", "Taro"]]
 => #<ActiveRecord::Relation [#<Member id: 1, number: 10, name: "Taro", full_name: "佐藤 太郎", email: "Taro@example.com", birthday: "1981-12-01", gender: 0, administrator: true, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58">]> 
2.4.0 :011 > members = Member.where(gender: 1).order("number")
  Member Load (0.3ms)  SELECT "members".* FROM "members" WHERE "members"."gender" = ?  ORDER BY number  [["gender", 1]]
 => #<ActiveRecord::Relation [#<Member id: 3, number: 12, name: "Hana", full_name: "高橋 花子", email: "Hana@example.com", birthday: "1981-12-01", gender: 1, administrator: false, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58">, #<Member id: 6, number: 15, name: "Sophy", full_name: "鈴木 花子", email: "Sophy@example.com", birthday: "1981-12-01", gender: 1, administrator: false, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58">, #<Member id: 9, number: 18, name: "Mary", full_name: "佐藤 花子", email: "Mary@example.com", birthday: "1981-12-01", gender: 1, administrator: false, created_at: "2017-12-06 03:15:58", updated_at: "2017-12-06 03:15:58">]> 
2.4.0 :012 > 
```