source 'https://rubygems.org/'
gemspec :name => 'puppet_docs'

gem 'versionomy'
gem 'rake'
gem 'rack'
gem 'git'
gem 'json'

group(:build_site) do
  gem 'jekyll', '3.0.1'
  gem 'kramdown', '~> 1.9'
  gem 'vlad'
  gem 'vlad-git'
  gem 'listen', '~> 3.0.0' # Preserve ability to run on Ruby 2.0, since listen 3.1 requires Ruby ~> 2.2.
end

group(:generate_references) do
  gem 'ronn'
  gem 'yard'
  gem 'rdoc'
end

group(:unknown) do
  gem 'maruku'
  gem 'activerecord', '~>3'
end

# group(:debug) do
#   gem 'byebug'
# end
