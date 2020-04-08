platform :ios, '8.0'

source 'https://github.com/CocoaPods/Specs.git'

project 'PopoverDemo'

# Versioning syntax:
# http://guides.cocoapods.org/using/the-podfile.html
#
target "PopoverDemo" do
  pod 'UIColor+BFPaperColors', '~> 1.7'
  pod 'BFPaperCheckbox', '~> 2.1'
end

post_install do |pi|
    pi.pods_project.targets.each do |t|
      t.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '8.0'
      end
    end
end

