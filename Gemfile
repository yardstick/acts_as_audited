source :gemcutter

gem "rails", ">= 3.0.3"

group :development do
  if defined?(:Java)
    gem "jdbc-sqlite3"
    gem "activerecord-jdbcsqlite3-adapter"
  else
    gem "sqlite3-ruby"
  end
  gem "rspec-rails", "~> 2.4.0"
  gem "rcov"
  gem "yard"
  gem "jeweler"
end
