require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << 'test'
end

desc "Run tests"
task :default => :test

desc "Launch irb session preloaded with this lib"
task :console do
  sh "irb -rubygems -I lib -r igc-kml.rb"
end