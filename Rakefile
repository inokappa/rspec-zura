task :default => [:spec]
begin
  require 'rspec/core/rake_task'
  RSpec::Core::RakeTask.new(:spec) do |spec|
    spec.pattern = '*_spec.rb'
    spec.rspec_opts = ['--color', '-fd']
  end
rescue LoadError => e
end
