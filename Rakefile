require 'opal/rspec/rake_task'
Opal.append_path "./opal"
Opal.append_path "./spec"

Opal::RSpec::RakeTask.new(:default) do |server, task|
  task.pattern = 'spec/**/*_spec.rb'
end