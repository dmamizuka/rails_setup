##setup

bundle install --path vendor/bundle

bundle exec rails s -b 0.0.0.0

##er図
bundle exec rake erd attributes=foreign_keys,primary_keys,content filename=rails-erd filetype=png
