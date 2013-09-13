HOME = ENV['HOME']

desc "Build the PivotalTracker.app bundle"
task :build do
  sh %(bundle exec macgap build --name 'Pivotal Tracker' --output ./pkg ./public)
end

desc "Build and install PivotalTracker.app to /Applications"
task :install => %w(build) do
  %x(cp -a 'pkg/Pivotal Tracker.app' #{HOME}/Applications/)
  puts %(Installed 'Pivotal Tracker.app' to ~/Applications)
end

desc "Uninstall built version of Pivotal Tracker"
task :uninstall do
  %x(rm -rf '#{HOME}/Applications/Pivotal Tracker.app')
  puts %(Removed 'Pivotal Tracker.app' from ~/Applications)
end

task :default => :build
