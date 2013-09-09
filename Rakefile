require 'rspec/core/rake_task'
require 'bundler/gem_tasks'

task :default => :spec

desc 'run rspec tests'
RSpec::Core::RakeTask.new(:spec) do |task|
  task.pattern = 'spec/*_spec.rb'
  task.rspec_opts = %w(--format documentation --color)
end

