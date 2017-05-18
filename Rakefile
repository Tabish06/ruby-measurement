require 'bundler/gem_tasks'
task :console do
  exec "irb -r ruby-measurement -I ./lib"
end

Dir.glob('tasks/**/*.rake').each(&method(:import))

desc 'Default: run unit specs'
task default: :spec
