require 'rake/testtask'

Rake::TestTask.new(:test) do |t|
  t.libs << "test"
  t.libs << "lib"
  t.test_files = FileList['specs/*_spec.rb']
  t.pattern = "specs/**/*_spec.rb"
end

task :default => :test
