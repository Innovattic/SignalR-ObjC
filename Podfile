xcodeproj 'SignalR.Client.ObjC/SignalR.Client.ObjC'
workspace 'SignalR.Client.ObjC'

target :"SignalR.Client.iOS", :exclusive => true do
  platform :ios, '6.0'
  pod 'AFNetworking'
  pod 'SocketRocket', :git => "https://github.com/square/SocketRocket.git", :branch => "master"
end

target :"SignalR.Client.OSX", :exclusive => true do
  platform :osx, '10.8'
  pod 'AFNetworking'
  pod 'SocketRocket', :git => "https://github.com/square/SocketRocket.git", :branch => "master"
end

target :"SignalR.Client.Tests.OSX", :exclusive => true do
    platform :osx, '10.8'
    pod 'OCMock'
end