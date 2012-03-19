desc 'Deploy'
task :deploy do
  sh "rsync -azh --progress --delete * #{ENV['SOONER_IO_HOST']}:/var/www/sooner.io/"
end
