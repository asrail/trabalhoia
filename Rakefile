task :default => [:doc] do
end

task :doc do
  require 'rdoc/rdoc'
  RDoc::RDoc.new.document(
    [ '--charset', 'utf-8' ] +
    [ '--inline-source', '--line-numbers' ] +
    Dir.glob('**/README') +
    Dir.glob('**/*.rb')
  )
end
