source 'https://rubygems.org'

group :development do

  # Sass, Compass and extensions.
  gem 'sass', '~> 3.3.10'       # Sass.
  gem 'sass-globbing'           # Import Sass files based on globbing pattern.
  gem 'compass', '~> 1.0.0.alpha.20'    # Framework built on Sass.
  gem 'compass-validator'       # So you can `compass validate`.
  gem 'compass-normalize'       # Compass version of normalize.css.
  gem 'compass-rgbapng'         # Turns rgba() into .png's for backwards compatibility.
  gem 'susy', '2.1.2'           # Susy grid framework.
  gem 'toolkit'                 # Compass utility from the fabulous Snugug.
  gem 'breakpoint'              # Manages CSS media queries.

  # Guard
  gem 'guard'                   # Guard event handler.
  gem 'guard-compass'           # Compile on sass/scss change.
  gem 'guard-shell'             # Run shell commands.
  gem 'guard-livereload'        # Browser reload.
  gem 'yajl-ruby'               # Faster JSON with LiveReload in the browser.

  # Dependency to prevent polling. Setup for multiple OS environments.
  # Optionally remove the lines not specific to your OS.
  # https://github.com/guard/guard#efficient-filesystem-handling
  gem 'rb-inotify', '~> 0.9', :require => false      # Linux
  gem 'rb-fsevent', :require => false                # Mac OSX
  gem 'rb-fchange', :require => false                # Windows

end
