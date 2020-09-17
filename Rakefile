task :serve do
  system("bundle exec middleman serve")
end

task :build do
  system("bundle exec middleman build; git checkout docs/CNAME; git add .")
end