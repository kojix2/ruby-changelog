require './changelog'

task default: :html

desc 'Generate html page with changelog'
task :html do
  Changelog.new.generate_html
end

desc 'Generate html page with changelog'
task :md do
  Changelog.new.generate_markdown
end
