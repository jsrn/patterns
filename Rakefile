desc "Serve the page."
task :serve do
  system("bundle exec middleman serve")
end

desc "Build and stage the app."
task :build do
  system("bundle exec middleman build; git checkout docs/CNAME; git add .")
end