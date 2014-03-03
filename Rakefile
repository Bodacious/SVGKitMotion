# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  app.name = 'SVGKitMotion'
  app.frameworks += %w[ CoreText CoreImage libxml2.dylib QuartzCore CoreGraphics UIKit ]
  app.deployment_target = '5.1'
  app.sdk_version = '7.0'
  app.pods do
    pod 'SVGKit'
  end    
end
