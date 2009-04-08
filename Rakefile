require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('activecalendar', '2009040801') do |p|
  p.description    = "Rails 2.1-compatible activecalendar"
  p.url            = "http://github.com/lukewendling/activecalendar"
  p.author         = "Luke Wendling"
  p.email          = "luke@lukewendling.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }


