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

desc 'drop into pry'
task :console => :environment do
  Pry.start
end

namespace db do
  task :migrate => :environment do
    
    
  end
end
  
  
  