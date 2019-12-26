# Uncomment the next line to define a global platform for your project
platform :ios, '12.0'

plugin 'cocoapods-pod-merge'

target 'PodMergePrivateHeader' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  pod 'SDWebImage', '~> 5.0'

  pod 'ImagePods', :path => 'MergedPods/ImagePods'

  target 'PodMergePrivateHeaderTests' do
    inherit! :search_paths
    # Pods for testing
  end

end
