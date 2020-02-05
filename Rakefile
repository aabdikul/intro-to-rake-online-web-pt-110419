namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end

desc 'makes sure console rake task exists'
task :console do
end

namespace :db do
  desc 'inovkes the environment as a dependency'
  task :migrate => :environment do
    Student.create_table
  end

  desc 'seeds  the database with dummy data'
  task :seed
   require_relative './db/seeds.rb'
 end
 end
