# Rails4static

Framework for static contents with Rails + Haml + Sass + Compass + jQuery + CoffeeScript + FontAwesome   
RailsとHamlとSassとCompassとjQueryとCoffeeScriptとFontAwesomeで静的ページを作る的なアレ

## How do I get started?

1) Fork it.

2) Clone your rails4static to your local machine.

```
git clone git@github.com:YOURUSER/rails4static.git
```

3) Start up Ruby on Rails.

```
cd rails4static
rails s
```

4) Edit markup on `/app/views/home/index.html.haml`

5) Edit Sass on `/app/assets/stylesheets/style.css.sass`   
If you needs add other Sass file, add this to `app/assets/stylesheets/basic.sass.erb` 
```
@import FILENAME
```
