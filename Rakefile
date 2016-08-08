
SCSS_OPTS = 'scss', '--compass', '--sourcemap=none', 'src/stylesheets/blog.scss:assets/blog.css'

desc 'Compile the SCSS'
task(:compile) { exec(*SCSS_OPTS) }

desc 'Watch the SCSS files and compile on change'
task(:watch) { exec(*(SCSS_OPTS + %w{--watch})) }

task default: :compile
