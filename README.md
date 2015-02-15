## Susy Basic Starter

This is a starter project template that Ruby Sass to compile Susy into CSS. This requires you to install the Susy gem file. 

## Project Setup  

1. Install Susy and Compass 

Skip this step if you already have the Susy gem installed. 

~~~
$ sudo gem install susy
~~~

2. Clone the repo 

~~~
git clone https://github.com/zellwk/basic-susy-starter.git
~~~

## Usage 

Run the following command

~~~
$ sass --watch scss:css -r susy
~~~

This command tells Sass to watch all files in the `scss` directory, output them all into the `css` directory and to require the `susy` gem. 

That's it!
