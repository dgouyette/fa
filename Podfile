# Uncomment the next line to define a global platform for your project
# platform :ios, '11.0'

target 'followanalytics' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for followanalytics
  pod 'FollowApps'


post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '4.0'
        end
    end
end
end
