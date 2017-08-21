# frozen_string_literal: true
source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }
group :default do
  gem "sinatra", '1.4.4'
  gem "hashie"
  gem 'octokit', '~> 2.0'
  gem 'awesome_print', :git => 'git@github.com:awesome-print/awesome_print.git'
end

group :test do
  gem 'rspec'
end

gem "pry", :group => "development"

# gem "rails"
