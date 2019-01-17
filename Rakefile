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

task :environment do 
  require_relative './config/environment'
end

namespace :db 
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    Student.create_table
  end
  
  desc 'adds dummy data to database'
  task :seed do 
    
end


