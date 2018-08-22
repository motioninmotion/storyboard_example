# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
$:.unshift("~/.rubymotion/rubymotion-templates")

require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

IB::RakeTask.new do |project|
  # you can customize the IB::Project here
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'storyboard_example'
end
