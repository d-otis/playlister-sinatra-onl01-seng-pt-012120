ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

# Type `rake -T` on your command line to see the available rake tasks.
desc 'reloads all files in /app dir'
def reload!
	load_all 'app'
end

task :console do
  Pry.start
end