desc "Generate config files using dice_bag's rake tasks"
task :release do
  Rake::Task['config:deploy'].invoke

  # Other custom configuration steps associated with the 12-Factor app release stage should be included here.
  Rake::Task['assets:precompile'].invoke
end

