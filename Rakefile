desc 'Sync generated site to the server'
task :sync do
  system <<-CMD
  rsync -rlptvz \
          _site/ $ALCHEMIST:domains/andymism.com/html
  CMD
end

