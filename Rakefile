require 'bundler/gem_tasks'

task :default => :test

mock = ENV['FOG_MOCK'] || 'true'
desc 'Run tests.'
task :test do
  sh("export FOG_MOCK=#{mock} && bundle exec shindont")
end
