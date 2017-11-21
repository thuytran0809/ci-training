echo ruby-2.3.4 >> .ruby-version
echo rails-ci >> .ruby-gemset
gem install bundler --pre
gem install rails -v 5.1.2
rails new /Users/khuyen/Repo/rails-ci

rails generate devise:install
rails generate devise User
rails generate simple_form:install
