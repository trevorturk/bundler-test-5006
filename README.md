cd /tmp
git clone git@github.com:trevorturk/bundler-test-5006.git
cd bundler-test-5006
gem install bundler --version 1.13.2
bundle
# => Bundle complete!
bundle install --deployment
# => Your Gemfile.lock is corrupt. The following gem is missing from the DEPENDENCIES section: 'bacon'
