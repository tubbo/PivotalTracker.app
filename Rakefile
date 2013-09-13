desc "Build the PivotalTracker.app bundle"
task :build do
  sh "bundle exec macgap build --name 'Pivotal Tracker' --output ./pkg ./public"
end

desc "Build and install PivotalTracker.app to /Applications"
task :install => %w(build) do
  sh "mv 'pkg/Pivotal Tracker.app' ~/Applications/"
end
