# Rails4static

The startup kit for designing static prototype with Rails + Haml + Sass + Compass + jQuery + CoffeeScript + FontAwesome   
RailsとHamlとSassとCompassとjQueryとCoffeeScriptとFontAwesomeで静的ページを手っ取り早く作る的なアレ

## How do I get started?

1) Fork it.

2) Clone your rails4static to your local machine.

```
git clone git@github.com:YOURUSER/rails4static.git
```

3) Bundle Gemfiles.

```
bundle
```
4) Startup Ruby on Rails.

```
cd rails4static
rails s
```

5) Edit markup on `/app/views/home/index.html.haml`

6) Edit Sass on `/app/assets/stylesheets/style.css.sass`   
If you needs add other Sass file, add this to `app/assets/stylesheets/basic.sass.erb` 
```
@import FILENAME
```
