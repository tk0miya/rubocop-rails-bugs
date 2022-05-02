# rubocop-rails-bugs

```
$ bundle install
$ bundle exec rubocop --require rubocop-rails
Inspecting 2 files
.C

Offenses:

test.rb:3:8: C: Rails/FilePath: Prefer Rails.root.join('path/to').
PATH = "#{Rails.root}:/path/to/directory"
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2 files inspected, 1 offense detected
```
