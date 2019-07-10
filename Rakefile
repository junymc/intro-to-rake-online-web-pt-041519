namespace :greeting do

desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc 'outputs hola de Rake'
task :hola do
  puts "hola de Rake!"
end

end

namespace :db do
  desc 'micrate changes to your datebase'
  task :migrate => :environment do
    Student.create_table
end
