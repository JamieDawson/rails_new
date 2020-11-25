Steps I took to create this project and launch it locally.

https://iridakos.com/programming/2013/11/24/saying-hello-world-with-ruby-on-rails

1. type `rails new hello_world` to create rails project
2. `rails generate controler pages` to create controller
3. Went to `app/controllers/pages_controller.rb` - Added this code:
   class PagesController < ApplicationController
   def home
   puts "Honey, I'm home!"
   end
   end

4. Went to `app/views/pages` and pasted `<h1>Hello World</h1>`

5. Went to `config/routes.rb` and added `root to: 'pages#home`.

6. Ran `rails server` to launch it locally.

These steps work. Now I need to launch them on the Nimbella cloud.
