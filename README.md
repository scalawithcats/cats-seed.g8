# Cats Seed

Minimal Giter8 template to get you set up with Cats.

Copyright 2017 Underscore Consulting LLP. Licensed [CC0 1.0][license].

## Getting Started

You'll need to [SBT][sbt] 0.13.13 or higher to use this template.

Run the following shell command:

~~~bash
$ sbt new underscoreio/cats-seed.g8
~~~

You'll be prompted to enter a project and package name. Press enter twice to accept the defaults:

~~~bash
name [Cats Sandbox]:
package [sandbox]:
~~~

The project will be created in a directory based off of the `name` you specified. If you accepted the defaults, you should be able to run the code as follows:

~~~bash
$ cd ./cats-sandbox
$ sbt run
~~~

If you see the message "Hello Cats!", you're good to go!

[license]: https://creativecommons.org/publicdomain/zero/1.0/
[sbt]: http://scala-sbt.org
