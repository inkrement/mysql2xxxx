source "http://rubygems.org"

gemspec

gem 'rake'
gem 'activerecord'
gem 'posix-spawn'
gem 'iconv'

if RUBY_VERSION >= '1.9'
  gem 'debugger2', :git => "git://github.com/ko1/debugger2.git"
else
  if RUBY_PLATFORM != 'java'
    gem 'memprof'
  end
  gem 'ruby-debug'
end
