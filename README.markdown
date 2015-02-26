= Puppet Ferret =

Installs [Ferret](http://ferret.pmel.noaa.gov/Ferret)

== Developing ==

The development tools make use of [bundler](http://bundler.io/)

Install development libraries with

    bundle config build.nokogiri --use-system-libraries
    bundle install --path vendor

Run unit tests with

    bundle exec rake spec

Run integration tests on a Vagrant VM with

    bundle exec rake acceptance

See the [Beaker workflow
documentation](https://github.com/puppetlabs/beaker/wiki/How-to-Write-a-Beaker-Test-for-a-Module#typical-workflow)
for how to re-use the test VM.
