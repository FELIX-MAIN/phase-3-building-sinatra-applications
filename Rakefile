require_relative './config/environment'
require 'sinatra/activerecord/rake'

desc "Start the server"
  task :server do
    exec "rerun -b 'rackup config.ru'"
  end
end
