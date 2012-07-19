wh: BUNDLE_GEMFILE=~/Wildfire/warehouse/Gemfile rvm ree@warehouse exec bundle exec shotgun -p 4000 ~/Wildfire/warehouse/config.ru
am: cd ../account_management && BUNDLE_GEMFILE=~/Wildfire/account_management/Gemfile rvm ree@account-management exec bundle exec rails s -p 3001
rq: cd ../app_suite && QUEUE=\* VVERBOSE=true rvm ree@app-suite exec bundle exec rake environment resque:work
pm: cd ../app_suite && rvm ree@app-suite exec bundle exec rails s --debugger
