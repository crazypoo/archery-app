# Uncomment this line to define a global platform for your project
# platform :ios, '9.0'

target 'archery app' do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for archery app
pod 'RealmSwift'
end
post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '3.0' # or '3.0'
    end
  end
end
