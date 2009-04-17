require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('lukewendling-activecalendar', '2009041701') do |p|
  p.description    = "Rails 2.x-compatible activecalendar"
  p.url            = "http://github.com/lukewendling/activecalendar"
  p.author         = "Luke Wendling"
  p.email          = "luke (at) lukewendling (dot) com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }


