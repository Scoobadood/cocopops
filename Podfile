
install! 'cocoapods', 
         :deduplicate_targets => true,
		 :deterministic_uuids => false

# iOS 10 plus only
platform :ios, '10.0'


# We want frameworks
use_frameworks!

# Need to identify the xcodeproject for the additional build specs
project 'SimpleProject', 'Copy Of Debug' => :debug

# Explicilty name the workspace
workspace 'SimpleProject'

# Common dependencies
def common
    pod 'CocoaLumberjack', '= 3.2.1'
end

# Actual lib 
target 'SimpleProject' do
    common
end
