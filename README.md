# Jaoskel: Simple Monk Skeleton used by Jaofos
Jaoskel is a [Monk][monk] skeleton used by Jaofos to generate skeleton [Sinatra][sinatra] applications.

## Usage
Using jaoskel with [Monk][monk] is simple. Just follow these 3 easy steps:

1. Install [Monk][monk] using `gem install monk`
2. Add jaoskel to your [Monk][monk] skeletons using `monk add jaoskel git://github.com/jaofos/jaoskel.git`
3. Run `monk init -s jaoskel` inside your project's empty directory to generate a jaoskel skeleton [Sinatra][sinatra] app.

## Notes
* A `Gemfile` is included for your connivence if you use [Bundler][bundler] to manage your gem dependencies.
* Remember to delete (or overwrite) this README file from your project's directory after running `monk init -s jaoskel`.

## Credits
* A huge "Thank You" to Gavin Kistner for inspiring jaoskel with his Monk skeleton, [riblits][riblits].


[monk]: "http://monkrb.com/"
[sinatra]: "http://sinatrarb.com/"
[bundler]: "http://gembundler.com/"
[riblits]: "https://github.com/Phrogz/riblits"
[klubenskel]: "https://github.com/klubensapps/klubenskel"
