# Uncomment the next line to define a global platform for your project
platform :ios, ‘8.0’

target 'MyApp' do
  use_frameworks!

  pod 'AFNetworking','3.1.0'
  pod 'RxSwift', '4.0'
  pod 'RxCocoa', '4.0'

  post_install do |installer|
    installer.pods_project.build_configuration_list.build_configurations.each do |configuration|
        configuration.build_settings['CLANG_ALLOW_NON_MODULAR_INCLUDES_IN_FRAMEWORK_MODULES'] = 'YES'
        configuration.build_settings['SWIFT_VERSION'] = '4.0'
        configuration.build_settings['ENABLE_BITCODE'] = 'NO'

  end
end

end
