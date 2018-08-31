platform :ios, '10.0'

target 'RxStarWars' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for RxStarWars
  pod 'RxSwift', '~> 4.0'
  pod 'RxCocoa', '~> 4.0'
  # pod 'RWHttpClient' , :path => '../RWHttpClient'
  pod 'RWHttpClient', :git => 'https://github.com/ryanwyc/RWHttpClient', :branch => 'master'

  target 'RxStarWarsTests' do
    inherit! :search_paths
    
    # Pods for testing
    pod 'RxBlocking', '~> 4.0'
    pod 'RxTest',     '~> 4.0'
    
  end

end
