# frozen_string_literal: true

source "https://rubygems.org"
gemspec

rails_version = "#{ENV['RAILS_VERSION'] || '6.0.0'}"

gem "rails", rails_version == "master" ? { github: "rails/rails" } : rails_version
gem "sqlite3", rails_version >= "6.0.0" ? ">= 1.4.0" : "< 1.4.0"
