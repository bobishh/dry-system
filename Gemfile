# frozen_string_literal: true

source "https://rubygems.org"

eval_gemfile "Gemfile.devtools"

gemspec

# Remove verson constraint once latter versions release their -java packages
gem "bootsnap", "= 1.4.9"
gem "dry-monitor"
gem "zeitwerk"

gem "dry-configurable", github: "dry-rb/dry-configurable", branch: "allow-access-to-class-level-config-between-setting-definitions"

group :tools do
  gem "pry-byebug", platforms: :mri
end
