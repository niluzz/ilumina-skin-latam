# frozen_string_literal: true

source "https://rubygems.org"

# Gemas principais
gem "jekyll", "~> 4.3"  # Verifique a versão compatível com o tema
gem "jekyll-multiple-languages-plugin", "~> 1.6"  # Plugin de i18n

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
  
gemspec

