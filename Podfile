# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

target 'Aniruddha Bapu Quotes' do

  pod 'Firebase'
  pod 'Firebase/Auth'
  pod 'Firebase/Database'
  pod 'SVProgressHUD'
  pod 'ChameleonFramework'
  pod 'SwiftyJSON'
  
  
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Aniruddha Bapu Quotes

end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
