# VRails - A Vagrant Rails Environment Ready do Go!

Code like a pro! Don't waste your time setting up your rails environment every time you need to change from one machine to another.

### What is in the box

See the packages that are in the box

* [Build-Essential] - To be able to compile anything from source. Required if you want to work with almost any programming language.
* [Ruby] - Ruby language. Version: 2.2
* [Bundler] - For manage dependencies. Version: Latest.
* [Git] - For source control. Version: Latest.
* [SQLite3] - For database. Version: Latest.
* [PostgreSQL] - For database. Version: Latest.
* [MySQL] - For database. Version: Latest.
* [Nokogiri depencencies] - (libxml2 libxml2-dev libxslt1-de) to get easy to install nokogiri.
* [Node.js] - for the runtime environment.

### Additional Information

* A superuser called 'vagrant' is already created for PostgreSQL.

### Installation

```sh
$ cd to/your/prefered/dir
$ git clone https://github.com/jcfausto/vrails.git
$ cd vrails/vm
$ vagrant up
```

### Troubles?

**Question:**

Can´t connect via http://localhost:3000 on host machine.

**Answer:**

Start your application with ```$ rails s -b 0.0.0.0.```

Details [here](http://edgeguides.rubyonrails.org/4_2_release_notes.html) and [here](http://stackoverflow.com/questions/27627286/cant-connect-localhost3000-ruby-on-rails-in-vagrant).

### License


MIT. Feel free to use :-)
