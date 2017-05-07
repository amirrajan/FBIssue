# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'FB Issue'

  app.pods do
    pod 'FBSDKCoreKit', git: 'https://github.com/amirrajan/facebook-ios-sdk.git'
    pod 'FBSDKLoginKit', git: 'https://github.com/amirrajan/facebook-ios-sdk.git'
    pod 'FBSDKShareKit', git: 'https://github.com/amirrajan/facebook-ios-sdk.git'
  end
end
