# Lab Framework

HTML5-based open source scientific models, visualizations, graphing, and probeware from the
[Concord Consortium](http://www.concord.org).

- **[lab.concord.org](http://lab.concord.org/)** _(production)_
- **[lab.dev.concord.org](http://lab.dev.concord.org/)** _(development)_
- **[Developer Readme](http://lab.dev.concord.org/readme.html)** _(working demo links)_
- **[github.com/concord-consortium/lab](https://github.com/concord-consortium/lab)** _(source)_

_Note: some of the demo links in this readme do not resolve properly at
[github.com/concord-consortium/lab](https://github.com/concord-consortium/lab).
A live version of the readme is always available here:
[lab.dev.concord.org/readme.html](http://lab.dev.concord.org/readme.html)._

**Table of Contents**

* toc
{:toc}

## Licensing

Lab is Copyright 2012 (c) by the Concord Consortium and is distributed under
any of the following licenses:

- [Simplified BSD](http://www.opensource.org/licenses/BSD-2-Clause),
- [MIT](http://www.opensource.org/licenses/MIT), or
- [Apache 2.0](http://www.opensource.org/licenses/Apache-2.0).

The complete licensing details can be read [here](license.html).

If you have have received a **distribution archive** of the
[Concord Consortium Lab project](https://github.com/concord-consortium/lab)
our copyright applies to all resources **except** the files in the
`vendor/` directory. The files in the `vendor/` directory are from
third-parties and are distributed under either BSD, MIT, or Apache 2.0 licenses.

## Model-type examples

The Lab framework supports embedding multiple model-types into the Lab Interactive form.
Each of the examples below also has an **embeddable** form that fluidly scales to the browser
window it is rendered in and is designed to be easily embedded using an iframe.

_Note: these demo links do not resolve properly at
[github.com/concord-consortium/lab](https://github.com/concord-consortium/lab).
A live version of the readme where these links work is always available here:
[lab.dev.concord.org/readme.html](http://lab.dev.concord.org/readme.html)._

### MD2D model-type: 2D molecular modeling

#### MD2D: Basic 2D molecular modeling

1. [Oil and water](interactives.html#interactives/samples/1-oil-and-water-shake.json), _([embeddable](embeddable.html#interactives/samples/1-oil-and-water-shake.json))_
2. [Charged and neutral atoms](interactives.html#interactives/samples/3-100-atoms.json), _([embeddable](embeddable.html#interactives/samples/3-100-atoms.json))_
3. [The volume-pressure relationship](interactives.html#interactives/sam/gas-laws/3-volume-pressure-relationship.json), _([embeddable](embeddable.html#interactives/sam/gas-laws/3-volume-pressure-relationship.json))_
4. [The temperature-volume relationship](interactives.html#interactives/sam/gas-laws/4-temperature-volume-relationship.json), _([embeddable](embeddable.html#interactives/sam/gas-laws/4-temperature-volume-relationship.json))_
5. [Phase changes with two bar graphs](interactives.html#interactives/sam/phase-change/6-phase-changes-caused-by-energy-input-two-bar-graphs.json), _([embeddable](embeddable.html#interactives/sam/phase-change/6-phase-changes-caused-by-energy-input-two-bar-graphs.json))_
6. [Diffusion and temperature](interactives.html#interactives/sam/diffusion/2-temperature.json), _([embeddable](embeddable.html#interactives/sam/diffusion/2-temperature.json))_
7. [Force and deformation in a metal-like material](interactives.html#interactives/visual/recycling/2-metalforces.json), _([embeddable](embeddable.html#interactives/visual/recycling/2-metalforces.json))_
8. [Force and deformation in a ceramic-like material](interactives.html#interactives/visual/recycling/1-ceramicforces.json), _([embeddable](embeddable.html#interactives/visual/recycling/1-ceramicforces.json))_
9. [Force and deformation in a plastic-like material](interactives.html#interactives/visual/recycling/3-plasticforces.json), _([embeddable](embeddable.html#interactives/visual/recycling/3-plasticforces.json))_

#### MD2D: Using macroscopic units with the molecular modeling engine

Normally MD2D uses units of femtoseconds and nanometers however it is also possible
to use the same engine with MKS macroscopic units. In the models listed below modeling
Coulomb forces is turned off and the Lennard-Jones force modeling has no effect.

1. [Pendulum](interactives.html#interactives/inquiry-space/pendulum/1-pendulum.json), _([embeddable](embeddable.html#interactives/inquiry-space/pendulum/1-pendulum.json))_
2. [Spring](interactives.html#interactives/inquiry-space/pendulum/2-spring.json), _([embeddable](embeddable.html#interactives/inquiry-space/pendulum/2-spring.json))_
3. [Springy pendulum](interactives.html#interactives/inquiry-space/pendulum/3-springy-pendulum.json), _([embeddable](embeddable.html#interactives/inquiry-space/pendulum/3-springy-pendulum.json))_

#### MD2D: Protein and DNA

_Currently in early development._

1. [Protein folding](interactives.html#interactives/samples/5-amino-acids.json), _([embeddable](embeddable.html#interactives/samples/5-amino-acids.json))_
2. [DNA transcription and translation folding](interactives.html#interactives/sam/DNA-to-proteins/3-modeling-translation.json), _([embeddable](embeddable.html#interactives/sam/DNA-to-proteins/3-modeling-translation.json))_

#### MD2D: Light and Matter (simple quantum dymanics)

A plugin for MD2D.

_Currently in early development._

1. [Quantum collision](interactives.html#interactives/conversion-tests/quantum-collision.json), _([embeddable](embeddable.html#interactives/conversion-tests/quantum-collision.json))_
2. [Quantum emission](interactives.html#interactives/conversion-tests/quantum-emission.json), _([embeddable](embeddable.html#interactives/conversion-tests/quantum-emission.json))_

### Solar System model-type

_Currently in early development._

- [Earth in orbit](interactives.html#interactives/solar-system/earth.json), _([embeddable](embeddable.html#interactives/solar-system/earth.json))_

### Signal generator model-type

_Currently in early development._

The signal-generator is a very simple model-type that was developed as a scaffold for building a sensor model-type.

- [Signal generator](interactives.html#interactives/signal-generator/signal-generator.json), _([embeddable](embeddable.html#interactives/signal-generator/signal-generator.json))_

### Probeware (sensor) model-type

_Currently in early development._

NOTE: this interactive uses an invisible Java applet to connect to a
[Vernier GoMotion](http://www.vernier.com/products/sensors/motion-detectors/go-mot/)
sonar ranger.

- [Sensor: Vernier GoMotion](interactives.html#interactives/sensor/sensor.json), _([embeddable](embeddable.html#interactives/sensor/sensor.json))_

## Additional examples

### Graphing examples

1. [Line graphs](examples/grapher/grapher.html)
2. [Bar graphs](examples/grapher-bar-graph/bar-graph.html)

**Experimental**

- [Digital signal processing graphs](experiments/dsp/dsp.html)

### Probeware

NOTE: this interactive uses an invisible Java applet to connect to a number of different
commercial probeware inerfaces from [Vernier](http://www.vernier.com/).

1. [Vernier GoLink](http://www.vernier.com/products/interfaces/go-link/)
2. [Vernier GoTemp](http://www.vernier.com/products/sensors/temperature-sensors/go-temp/)
3. [Vernier GoMotion](http://www.vernier.com/products/sensors/motion-detectors/go-mot/)
4. [Vernier LabQuest](http://www.vernier.com/products/interfaces/lq-mini/)

[Vernier Sensor Grapher](experiments/goio-sensor-grapher/index.html) _(only works on web-server)_

### Energy2D: thermal simulation

NOTE: The Energy2D thermal simulation models are not yet integrated into the Lab Interactive form.

- [Energy2D Models](examples/energy2d-model/energy2d-model.html)
- [Energy2D Models (WebGL physics solvers)](examples/energy2d-gpu-model/energy2d-model.html#interactives/vortex-street100.json)

## Distribution of Project and Examples

Compressed archives of the generated Lab distribution are available for download:

- [Lab distribution (tar.gz archive)](https://github.com/concord-consortium/lab/tarball/gh-pages) _(32MB)_
- [Lab distribution (zip archive)](https://github.com/concord-consortium/lab/zipball/gh-pages) _(42MB)_

Download and expand one of these archives to create a folder named `concord-consortium-lab-xxxxxxx`.
The seven characters at the end of the archive filename are the first seven characters of the git
commit SHA.

To access the content on your local you will need to serve the files from a web server running on your
local computer. Once there open the file index.html in the expanded archive.

For example Chrome generates this error when I try and load the sample Oil and Water Interactive directly
from my filesystem:

    XMLHttpRequest cannot load file:///Users/stephen/Downloads/concord-consortium-lab-9771ec6/interactives/samples/1-oil-and-water-shake.json.
    Origin null is not allowed by Access-Control-Allow-Origin.

## Setup Development

Lab uses a number of RubyGems and node modules to manage development. Lab's test framework
uses [Vows](http://vowsjs.org) amd [Mocha](http://visionmedia.github.io/mocha/) which both depend
on [nodejs](http://nodejs.org/) and [npm](http://npmjs.org/) the Node Package Manager.

In addition JavaScript minification is done using [UglifyJS](https://github.com/mishoo/UglifyJS).
JavaScript dependency management is handled by [RequireJS](http://requirejs.org/).

### Prerequisites:

#### RVM, Ruby 2.0 and the RubyGem bundler

We normally use [RVM](https://rvm.io/) to mange our development dependency on [Ruby 2.0.0](http://www.ruby-lang.org/en/)
and the specific Ruby Gems needed for building Lab and running the Lab server.

1. [Install RVM](https://rvm.io/rvm/install/)

After installation you should see something like the following:

    $  ruby -v
    ruby 2.0.0p247 (2013-06-27 revision 41674) [x86_64-darwin10.8.0]

If you already have RVM installed update to the most up-to-date stable version.

    $ rvm get stable

Once you have a working version of Ruby 2.0.0 check to see if the RubyGem [bundler](http://gembundler.com/)
is already installed:

    $ gem list bundler

    *** LOCAL GEMS ***

    bundler (1.3.5)

If Bundler is not installed install it now into the global gemset for ruby-2.0.0-p247

    $ rvm gemset use global
    $ gem install bundler
    Fetching: bundler-1.3.5.gem (100%)
    Successfully installed bundler-1.3.5
    1 gem installed

#### nodejs and npm, the Node Package Manager

[nodejs](http://nodejs.org/) and [npm](http://npmjs.org/), the Node Package Manager are additional
development dependencies.

[npm](http://npmjs.org/), the Node Package Manager is included as part of [nodejs](http://nodejs.org/)

Install the latest stable version of node (currently v0.10.4) with installers available here: [http://nodejs.org/#download](http://nodejs.org/#download)

Currently development is being done with these versions of node and npm:

    $ node -v
    v0.10.4

    $ npm -v
    1.2.18

#### Java

Java is needed for the legacy Java applications we are porting to HTML5.

Test to see if Java is installed and available:

    $ java -version
	java version "1.6.0_33"
	Java(TM) SE Runtime Environment (build 1.6.0_33-b03-424-11M3720)
	Java HotSpot(TM) 64-Bit Server VM (build 20.8-b03-424, mixed mode)

On Mac OS X 10.7 and later Java is not automatically installed. However running the command
`java -version` when Java is not installed will bring up an operating system dialog enabling
Java to be installed.

###Linux (Ubuntu)

Before any of this make sure that "run command as login shell" is checked. if it isn't go to edit-profile
preferences-Title and Command, and check Run command as a login shell.

To [Install RVM](https://rvm.io/rvm/install/) you need to have curl:

    $ sudo apt-get install curl </code></pre>

Install RVM using curl with:

    $ curl -L https://get.rvm.io | bash -s stable --ruby

After RVM has finnished installing it will ask you to run a command similar to

    $ source /home/user_name/.rvm/scripts/rvm

After installation you should see something like the following:

    $  ruby -v
    ruby 2.0.0p247 (2013-06-27 revision 41674) [x86_64-darwin12.4.0]

RVM has some additional dependancies, to view these type:

    $ rvm requirements

Under additional dependancies and ruby, copy the list of dependancies and paste them in to your terminal
and install them using `sudo`. The command will look something like this:

    sudo /usr/bin/apt-get install build-essential openssl libreadline6 libreadline6-dev curl git-core zlib1g zlib1g-dev libssl-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt-dev autoconf libc6-dev ncurses-dev automake libtool bison subversion</code></pre>

Becouse of some unknown bugs RVM doesn't recognise readline without being explictly pointed to it.
To do this I've had to reinstall ruby 2.0.0p247.

  $ rvm reinstall 2.0.0-p247 --with-zlib1g-dev

[ruby gem bundler](http://gembundler.com/) should be installed. To check if it has been try:

    $ gem list bundler

    *** LOCAL GEMS ***

    bundler (1.3.5)

If it doesn't return anything install Bundler:

    $ gem install bundler

#### nodejs and npm

[nodejs](http://nodejs.org/) and [npm](http://npmjs.org/), the Node Package Manager are additional
development dependencies.

[npm](http://npmjs.org/), the Node Package Manager has been included as part of [nodejs](http://nodejs.org/)
since version 0.6.3.

To install the latest stable versions of node you first need to add this PPA repositories:

1. [node PPA repo](https://launchpad.net/~chris-lea/+archive/node.js/)

For this to work as intended python software properties must also be installed.

    $ sudo apt-get install python-software-properties
    $ sudo apt-add-repository ppa:chris-lea/node.js
    $ sudo apt-get update

Now install node and npm:

    $ sudo apt-get install nodejs npm

Neither the Java run time environment nor the Java development kit are installed by
default, both of which are used for the java projects.

    sudo apt-get install  default-jre openjdk-6-jdk

The Ruby Gem Nokogiri requires libxslt and libxml2, install them with:

    sudo apt-get install libxslt-dev libxml2-dev

Final note, before you `make everything` setup the project configurations files by copying the
configuration samples:

    cp config/config.sample.yml config/config.yml

#### Known problems with Linux during Lab build process

- D3.js build process fails:

        locale: Cannot set LC_ALL to default locale: No such file or directory

    Solution:

        $ sudo locale-gen en_US

- D3.js build process fails:

        make[1]: /usr/lib/nodejs:/usr/share/javascript/uglify-js/bin/uglifyjs: Command not found

    Workaround:

        $ unset NODE_PATH

    and try to build the project again.

### Use git to create a local clone of the Lab repository.

If you have commit access to the repository use this form:

    git clone git@github.com:concord-consortium/lab.git

Alternatively if you don't have commit access use this form:

    git clone git://github.com/concord-consortium/lab.git

### Setup the local Lab repository for development

Make sure you have already installed the prerequistes: [Ruby 2.0](http://www.ruby-lang.org/en/),
the RubyGem [bundler](http://gembundler.com/), and [nodejs](http://nodejs.org/) (which now includes
[npm](http://npmjs.org/) the Node Package Manager.

Open a shell and change to the `lab/` directory. The first time you `cd` into the `lab/` directory
RVM will switch to using `ruby-2.0.0-p247` based on the `.ruby-version` file in the repository.
Additionally the `.ruby-gemset` tells RVM to install the gems in a gemset named `lab`. So together
these files tell RVM to store and load gems from the `ruby-2.0.0-p247@lab` gemset.

    cd lab

If you don't have `ruby-2.0.0-p247` already installed rvm will display the command you need to
run to install it. Run this command if required.

If you do end up having to install a new version of Ruby with RVM change out of and back into the lab directory after the RVM install of Ruby is complete:

    cd ..
    cd lab

#### Initial configuration

Copy the sample project configuration file to `config/config.yml` (you can examine it and edit if you want).

    cp config/config.sample.yml config/config.yml

#### Create a git post-commit hook

After every commit `src/lab/lab.version.js` should be updated to include recent version and build information for Lab's distrobution. To do this make a git `post-commit` hook by creating the file `.git/hooks/post-commit` with this content:

    #!/bin/sh
    (cd ../.. && ./script/update-git-commit-and-branch.rb)

Make the file `.git/hooks/post-commit` executable:

    chmod u+x .git/hooks/post-commit

Now run a make task that will download and install all the dependencies and build the whole project
for the first time.

    make everything

When `make everything` is run on a freshly cloned repository it performs the following tasks:

1.  Install the runtime dependencies as git submodules into the `vendor/` directory:

        git submodule update --init --recursive

2.  Install the development dependencies that use [nodejs](http://nodejs.org/) and
    are managed by [npm](http://npmjs.org/):

        npm install

    You can see the list of dependencies to be installed in the file `package.json`. In addition
    `vendor/d3` and `vendor/science.js` are manually installed into `node_modules/`.

3.  Install the additional RubyGems used for development: haml, sass, guard ...

        bundle install --binstubs

    This creates the `bin/` directory and populates it with command-line executables for running
    the specific versions of the RubyGems installed for development.

4.  Generates the `public` directory:

5.  Generates the Java resources in the `public/jnlp` directory:

You should now be able to open the file: `public/index.html` in a browser and run some of the examples.
On Chrome browsers you will need to start a server, using `bin/rackup` (see below) or `python -m SimpleHTTPServer` from the lab root directory.

#### Automatic build processing using Guard

Start watching the `src/` and `test/` directories with [Guard](#guard) and when files are
changed automatically generate the JavaScript Lab modules, the examples, and run the tests.

    bin/guard

Now any change you make in `src/examples/` will generate the corresponding content in `public/examples/`.
In addition changes in `src/lab/` generate the associated Lab modules in `lab/` and copy these modules
to `public/lab/`. In addition any change in either the `src/lab/` or `test/`directories will run the
tests and display the results in the console window where `bin/guard`
is running.

#### Startup the Rack-based Lab server for local development

The Lab server is a simple Rack application.

    bin/rackup config.ru

Now open http://localhost:9292/index.html

This developer server and the production server are running an [embedded Jnlp service](developer-doc/jnlp-rack-app.md).

#### Java Resources

[Java Resources](developer-doc/java.md)

## Project Configuration

Configuration variables used by the runtime JavaScript code are available in the JavaScript global
object `Lab.config`.

In a full build environment the JavaScript configuration is set in the `:jsconfg` section of
`config/config.yml`:

    :jsconfig:
      :sharing: true
      :home: http://lab.concord.org
      :homeForSharing:
      :homeInteractivePath: /examples/interactives/interactive.html
      :homeEmbeddablePath: embeddable.html
      :utmCampaign: <external-campaign-key>

**`sharing`** A boolean attribute used to determine if the **Share** link in the Interactives will be enabled.
The default value for this is `true`.

**`home`** Url used to reference cannonical site when sharing is turned off.

**`homeForSharing`** Set :homeForSharing to the host where shared Interactives are found
if you don't want to share the ones on the actual server. Example if you host the
Interactives on a static S3 site and want the sharing links to point to the same
Interactives at "http://lab.concord.org"

**`homeInteractivePath`** Path to page to run non-embeddable version of Interactives.

**`homeEmbeddablePath`** Path to page to run embeddable version of Interactives.

**`utmCampaign`** If present a UTM suffix is added to links in the About box.
Set to a string which identifies the external organization.

When the build environment is active these values are used to generate JavaScript code integrated
into the project by the Ruby program:
[`script/generate-js-config.rb`](https://github.com/concord-consortium/lab/blob/master/script/generate-js-config.rb)

### Interactive Share link

Normally the **Share** link in an Interactive is enabled. The **Share** dialog allows a user to more easily
share the Interactive in an email or IM, and also provides generated HTML content that can be copied and pasted
to embed the Interactive into a blog or web page.

If you are hosting this content on an external server where supporting
sharing is impractical in some manner you can disable the display of the Interactive **Share** link by setting
`:sharing` in `config/config.yml` to `false`:

    :jsconfig:
      :sharing: false
      :home: http://lab.concord.org
      :homeForSharing: http://lab.concord.org
      :homeInteractivePath: /examples/interactives/interactive.html
      :homeEmbeddablePath: embeddable.html
      :utmCampaign: <external-campaign-key>

The additional values for `:home`, `homeInteractivePath`, and `homeEmbeddablePath` are used to construct an
additional paragraph in the Interactive **About** box providing a link to the Interactive on the production
[site for the project](http://lab.concord.org).

You can also enable Sharing **but** use a separate host for generating the sharing urls by entering a value
for **homeForSharing**. If you are *also* hosting the the Lab Interactives in a subdirectory you must also
set the values for **homeEmbeddablePath** and **homeInteractivePath** as shown above.

The value for `utmCampaign` is optional. If present and the **home** site has enabled Google Analytics
setting a value for `utmCampaign` will allow better tracking of users who click through links in the
Interactive **About** box.

### Google Analytics

In addition there is a optional section in `config/config.yml` which if present enables embedding google
analytics script into the head of the main `index.html` and all html pages in the `examples/` and `doc/`
directories. This includes all the Interactives which are located in `examples/interactives` directory.

Include your Google Analytics account number here to enable insertion of the Google Analytics
script by the build system into the generated HTML pages.

    :google_analytics:
      :account_id: <account-id>

The content from which the embedded Google Analytics script is generated is contained in this Ruby file:
[`script/setup.rb`](https://github.com/concord-consortium/lab/blob/master/script/setup.rb).

### Limitations changing configuration in an archive distribution

If you have downloaded a distribution archive you can manually modify the code that initializes the JavaScript
runtime configuration in the files: `lab/lab.js` and `lab/lab.min.js`. Editing the value for `Lab.config.sharing`
in these files will affect the JavaScript runtime settings when these files are loaded.

Additionally you can turn on UTM suffixes by adding a string value to `Lab.config.utmCampaign``.

However generation and insertion of the Google Analytics script into HTML pages can only be done by
setting a value for the `:google_analytics :account_id` and running the build process.

## Contributing to Lab

If you think you'd like to contribute to Lab as an external developer:

1. Create a local clone from the repository located here: http://github.com/concord-consortium/lab.
   This will by default have the git-remote name: **origin**.

2. Make a fork of http://github.com/concord-consortium/lab to your account on github.

3. Make a new git-remote referencing your fork. I recommend making the remote name your github user name.
   For example my username is `stepheneb` so I would add a remote to my fork like this:

        git remote add stepheneb git@github.com:stepheneb/lab.git

4. Create your changes on a topic branch. Please include tests if you can. When your commits are ready
   push your topic branch to your fork and send a pull request.

## Continuous Integration on travis-ci

[travis-ci](http://travis-ci.org) is a free open-source web-based distributed continuous integration system.

When code is checked in to the master branch the [concord-consortium/lab](http://travis-ci.org/#!/concord-consortium/lab)
project on [travis-ci](http://travis-ci.org) automatically runs all the unit tests.

If any test fails the author of the commit will get an email as well the developers listed in the
[.travis.yml](https://github.com/concord-consortium/lab/blob/master/.travis.yml) configuration file.

### Setting up travis-ci integration

I created an account on [travis-ci](http://travis-ci.org) linked to the [stepheneb](https://github.com/stepheneb)
acocunt on github by having travis-ci authenticate me with github using oauth.

I was then able to manually setup a Travis service hook for the lab repository. I needed to
do this manually because I was integrating a repository under the concord-consortium github
organization instead of one directly under my own account.

Useful [travis-ci](http://travis-ci.org) resources

- [The Travis Architecture](http://about.travis-ci.org/docs/dev/overview/)
- [How to setup and trigger the hook manually](http://about.travis-ci.org/docs/user/how-to-setup-and-trigger-the-hook-manually/)
- [Build configuration](http://about.travis-ci.org/docs/user/build-configuration/)
- [Ruby projects](http://about.travis-ci.org/docs/user/languages/ruby/)
- [Nodejs projects](http://about.travis-ci.org/docs/user/languages/javascript-with-nodejs/)
- [GUI and Headless Browser testing](http://about.travis-ci.org/docs/user/gui-and-headless-browsers/)

## Repository structure

### vendor/

[Third-party JavaScript runtime dependencies](#javascript-library-runtime-dependencies)
for Lab are located in the
**[`vendor/`](https://github.com/concord-consortium/lab/tree/master/vendor)**
directory and are installed as git submodules
the first time `make` is run in a new checkout of the source code repository.

Only the necessary JavaScript library files and other resources needed for runtime operation along
with the associated README and LICENSE files are copied to **`public/vendor`** during
the build process.

All of the files copied to **`public/vendor`** are licensed and distributed under
one or more of the following licenses:
[Simplified BSD](http://www.opensource.org/licenses/BSD-2-Clause),
[The BSD 3-Clause](http://www.opensource.org/licenses/BSD-3-Clause),
[MIT](http://www.opensource.org/licenses/MIT), or
[Apache 2.0](http://www.opensource.org/licenses/Apache-2.0).

### src/

The **[src/](https://github.com/concord-consortium/lab/tree/master/src)** directory
contains the main source code for the Lab framework, examples, and documentation. This
code is either copied directly or used to generate resources  that are copied.

#### src/lab/

The **[src/lab\](https://github.com/concord-consortium/lab/tree/master/src/lab)**
directory includes JavaScript source code for the Lab JavaScript modules.
During the build process individual files are copied into modules which are placed in
the **`public/lab`** directory.

##### src/lab/md2d

The [md2d](https://github.com/concord-consortium/lab/tree/master/src/lab/md2d) model-type contains a basic
**Next Generation Molecular Workbench* application. It built using a hybrid of a MVC design pattern
with a dataflow architecture necessary for performance and consist of following units:

- Models - [`src/lab/md2d/models`](https://github.com/concord-consortium/lab/tree/master/src/lab/md2d/models)
- Views - [`src/lab/md2d/views`](https://github.com/concord-consortium/lab/tree/master/src/lab/md2d/views)
- Controllers - [`src/lab/md2d/controllers`](https://github.com/concord-consortium/lab/tree/master/src/lab/md2d/controllers)

The source code of the core molecular dynamics engine is currently located in the
[src/lab/md2d/models/engine](https://github.com/concord-consortium/lab/tree/master/src/lab/md2d/models/engine)
directory, which is organized as a set of related RequireJS modules. These modules are compatible
both with the Web browser environment and Node.

###### MD2D Headless Mode

###### [`node-bin/run-md2d`](https://github.com/concord-consortium/lab/blob/master/node-bin/run-md2d)

There is one working script for now:
[`node-bin/run-md2d`](https://github.com/concord-consortium/lab/blob/master/node-bin/run-md2d)

It runs simulation for desired time and prints Time, Kinetic Energy, Total Energy every tick.

Usage:

    ./node-bin/run-md2d -i [path] -o [path or stdout] -i [num]

    Options:
      -i, --input   Model JSON file        [string]  [required]
      -o, --output  Output file or stdout  [string]  [default: "stdout"]
      -t, --time    Integration time       [default: 100]

Example results:

    Model file: public/imports/legacy-mw-content/converted/new-examples-for-nextgen/simple-gas$0.json
    Output: stdout
    Integration time: 150
    time    KE      TE
    0       3.0988  3.1003
    50      3.1748  3.1011
    100     3.1748  3.0998
    150     3.1868  3.0986

###### Writing new scripts

In addition, new Node-based executables can be written. These are expected to be useful for verifying and tuning the model by running the model headless and saving summary results into a file for offline analysis.

If you want to create your own script running simulation in headless mode, the most reasonable solution is to use [`src/lab/md2d/models/modeler.js`](https://github.com/concord-
consortium/lab/blob/master/src/lab/md2d/models/modeler.js) as it provides high level API and
allows to load model description using JSON file. To run simulation use the `tick()` method.

[RequireJS](https://http://requirejs.org/) package must be correctly configured and used to load this module (see [the section about
RequireJS](#javascript-dependency-management-and-build-process---requrejs)). It also depends on [jQuery](http://jquery.com/) and [d3.js](http://mbostock.github.com/d3/) libraries.

Fortunately, you do not have to think about this configuration each time. There is prepared the entry point for external Node.js applications:

[`src/helpers/md2d/md2d-node-api.js`](https://github.com/concord-consortium/lab/blob/master/src/helpers/md2d/md2d-node-api.js)

This module configures RequireJS loader, environment (D3, jQuery) and exports MD2D Node API using Node.js/CommonJS approach.

Usage:

    var md2dAPI = require("../src/helpers/md2d/md2d-node-api");
    // (...)
    // To create e.g. Modeler mentioned above:
    var model = md2dAPI.Modeler(properties);

If you need to use something what is not included in this API, you can:

- Extend API defined in [`md2d-node-api.js`](https://github.com/concord-consortium/lab/blob/master/src/helpers/md2d/md2d-node-api.js). It should easy to do it looking at the existing code.
- Configure RequireJS yourself and use it to load module. Again, take a look at [`md2d-node-api.js`](https://github.com/concord-consortium/lab/blob/master/src/helpers/md2d/md2d-node-api.js) how to do it.

There is a chance that existing RequireJS config won't be sufficient (e.g. if you wan't to use dynamic cs files loading).

- The official, complete documentation:

  [http://requirejs.org/docs/api.html#config](http://requirejs.org/docs/api.html#config)

- RequireJS config for tests, as they also use similar approach:

  [`test/requirejs-config.js`](https://github.com/concord-consortium/lab/blob/master/test/requirejs-config.js)

Hashbang scripts for starting these executables (i.e., files which start with the line
`#!/usr/bin/env node` and which have the execute bit set) should be placed in the directory
[`node-bin`](https://github.com/concord-consortium/lab/tree/master/node-bin). Lab's
[`packages.json`](https://github.com/concord-consortium/lab/blob/master/package.json) file
specifies [`node-bin`](https://github.com/concord-consortium/lab/tree/master/node-bin) as the
location of the executable scripts which `npm` should make available whenever Lab is imported into
another project as a Node module. (For developer convenience, `bin/` is being reserved for Ruby
executables made available via Bundler.)

###### MD2D simulation stepping

Main parameters which define speed and accuracy of simulation in MD2D are:

- timeStep,
- timeStepsPerTick,
- modelSampleRate.

To explain them let's start from the definition of the model "tick". One "tick" consists of:

- running simulation for **timeStepsPerTick** * **timeStep** femtoseconds,
- update of the view.

The "tick" is constantly repeated while simulation is running.

So, when timeStepsPerTick= 50 and timeStep = 1fs, one "tick" causes that the engine performs calculations for 50fs.

**timeStep** defines a time value used during the one integration step in the engine internals. It affects accuracy of calculations.
**timeStepsPerTick** in fact defines number of these integration steps during one "tick". It is defined because it makes no sense to refresh view too often.

Using pseudo-code we can say that tick is:

    for (i = 0 to timeStepsPerTick) {
       engine.advanceBy(timeStep)
    }
    view.update()

That's why timeStepsPerTick = 50 and timeStep = 1fs is different from timeStepsPerTick = 25 and timeStep = 2fs.
First one will be more accurate and two times slower (more or less) than second one, however both configurations will cause that one "tick" advance model by 50fs (25 * 2fs or 50 * 1fs).

**modelSampleRate** defines how often we should execute "tick". Of course, in most cases we should call it as often as it's possible and that's the default behavior (with upper limit of 60 times per second to avoid running simple models too fast).

You can test how these parameters work using the
[Model integration time step, period, and sample rate](interactives.html#interactives/basic-examples/sample-rate-and-refresh-rate.json)
interactive.

##### src/lab/grapher/

- [src/lab/grapher](https://github.com/concord-consortium/lab/tree/master/src/lab/grapher)

##### src/lab/common/

- [src/lab/common](https://github.com/concord-consortium/lab/tree/master/src/lab/common)

##### src/lab/import-export/

- [src/lab/import-export](https://github.com/concord-consortium/lab/tree/master/src/lab/import-export)

##### src/lab/energy2d/

The **[src/lab/energy2d](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d)** model-type contains
a basic **Energy2D* application*. It is a direct port of [Java Energy2D](http://energy.concord.org/energy2d/).
Energy2D is also built over MVC design pattern and consist of following units:

- Models - [`src/lab/energy2d/models`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/models)
- Views - [`src/lab/energy2d/views`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/views)
- Controllers - [`src/lab/energy2d/controllers`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/controllers)

and additionally:

- Internal Utils - [`src/lab/energy2d/utils`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/utils)
- GPU Toolkit - [`src/lab/energy2d/gpu`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/gpu)

GPU Toolkit is a small set of utilities which wraps basic WebGL structures and objects, providing
higher level API. It is useful, as Energy2D uses WebGL for General-Purpose Computing on
Graphics Processing Unit. So, a lot of physics calculations are performed on the GPU if user's Web
browser supports WebGL technology.

The source code of the core physics engine is located in the [`src/lab/energy2d/models`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/models) directory.
Especially important units are listed below:

- Core Model [`src/lab/energy2d/models/core-model.js`](https://github.com/concord-consortium/lab/blob/master/src/lab/energy2d/models/core-model.js) - constructs all physics solvers,
stores simulation data (arrays, textures) and delegates physics calculations to proper objects.
- Physics Solvers [`src/lab/energy2d/models/physics-solvers`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/models/physics-solvers) - directory containing sequential
(plain JavaScritp) implementation of physics algorithms used by core model.
- Physics Solvers GPU [`src/lab/energy2d/models/physics-solvers-gpu`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d/models/physics-solvers-gpu) - directory containing parallel
implementation (WebGL-based) of heat and fluid solvers.

Necessary GLSL (GL Shading Language) sources are stored in separate files. They are loaded using
RequireJS *text* plug-in which just allows to load plain text files. Finally, they are inlined in
the resulting library due to the RequireJS optimization process.

#### src/examples/, src/doc/, and src/experiments/

The
**[src/examples/](https://github.com/concord-consortium/lab/tree/master/src/examples)**,
**[src/doc](https://github.com/concord-consortium/lab/tree/master/src/doc)** and,
**[src/experiments](https://github.com/concord-consortium/lab/tree/master/src/experiments)**
directories contain additional resources for generating the html, css, and image resources
for the matching target folders in **`public`**.

**Note:** remember to make changes you want saved in the **`src/examples/`**, **`src/doc/`**,
and **`src/experiments/`** and not in the target directories of the same names in
**`public`**. Change made in **`public`** will be overwritten during the next
build process.

#### src/resources

The **[src/resources/](https://github.com/concord-consortium/lab/tree/master/src/resources)** directory contains image resources and are copied directly to
**`public/resources`**.

#### src/sass

The **[src/sass/](https://github.com/concord-consortium/lab/tree/master/src/sass)** directory contains Sass templates and the Bourbon Sass library are are used
during the build process to generate CSS resources.

#### src/helpers

The **[src/helpers/](https://github.com/concord-consortium/lab/tree/master/src/helpers)** directory contains
CoffeeScript and JavaScript modules as well as Ruby programs only used as part of the testing and
build process and are not copied to **`public/resources`**.

### JavaScript Dependency Management and Build Process - RequreJS

Lab's modules use [RequireJS](http://requirejs.org/) for dependency management. It is a JavaScript
file and module loader optimized for in-browser use, but it can be used in other JavaScript
environments, like Rhino and Node. So, you don't have to worry about manual JavaScript files
concatenation and the library build process - everything is done automatically.

[RequireJS](http://requirejs.org/) might be used for fully asynchronous in-browser module loading,
but it can also be used for combining all source files into one output JavaScript file. The Lab
project mostly uses the second approach. The tool which resolves all dependencies and combines them
into single output file is called **RequireJS Optimizer**.

Useful RequireJS resources:

- [How to get started with RequireJS](http://requirejs.org/docs/start.html)
- [RequireJS API](http://requirejs.org/docs/api.html)
- [RequireJS Optimization](http://requirejs.org/docs/optimization.html)
- [RequireJS in Node](http://requirejs.org/docs/node.html)
- [RequireJS Google Group](https://groups.google.com/forum/?fromgroups#!forum/requirejs)


#### Adding new source file intended to work in the Web browser

Adding a new source to existing module is straightforward.

1. Put the source file in an appropriate directory (e.g. `src/lab/module-name/`).

2. Define it as a module using RequireJS syntax, e.g. following this pattern:

        define(function (require) {
          // Dependencies.
          var utils = require('other-module-name/file-name');
          // Preparation code.
          // (...)
          // Finally, return module API.
          return {
            // (...)
          };
          // Or just constructor function:
          // return function ClassName() {
          //   (...)
          // };
        });

    You can read more about RequireJS modules syntax
    [here](http://requirejs.org/docs/api.html#define).


3. In case of need, reference this file in other sources using RequireJS syntax:

          var dependency = require('module-name/file-name');

That's all! Your file will be automatically included during module build process.

#### Adding new source file intended to work in the Web browser and in Node

If you are working on file which should also work in the Node environment as a typical package
(without using RequireJS as a dependency and its syntax), follow instructions above and
additionally:

1. Add following snippet at the beginning of the source file:

        if (typeof define !== 'function') { var define = require('amdefine')(module) }

2. Make sure that `amdefine` package is listed as a dependency in your `package.json` file (it can be
Lab's [`packages.json`](https://github.com/concord-consortium/lab/blob/master/package.json) file
or separate one if you work on the independent module, like those stored in
[`src/modules`](https://github.com/concord-consortium/lab/tree/master/src/modules) directory).

The Lab's **array** module uses this technique, so you may look for a reference in
[`src/modules/arrays`](https://github.com/concord-consortium/lab/tree/master/src/modules/arrays).


#### Adding new module which should be built as a separate library

This involves a few additional steps comparing with adding a single source file.

1. Create a new directory in `src/lab`.
2. Put all related sources there or in `src/lab/common` (if you think that they are generic enough
and may be reused by other modules).
3. Define `module-name.build.js` and `public-api.js` files in your new directory (described below).
4. Add build routines to the [`Makefile`](https://github.com/concord-consortium/lab/blob/master/Makefile):

    4.1. Define a new target, for example:

        public/lab/lab.module-name.js: \
            $(NEW_MODULE_SRC_FILES) \
            $(COMMON_SRC_FILES)
            $(R_OPTIMIZER) -o src/lab/module-name/module-name.build.js

    4.2. List this target in `LAB_JS_FILES` Makefile variable containing the list of all Lab JavaScript
      modules to be generated.

Your module will be built during Lab's build process. You may use one of the existing modules for
reference in case of any troubles
([`md2d`](https://github.com/concord-consortium/lab/tree/master/src/lab/md2d),
[`energy2d`](https://github.com/concord-consortium/lab/tree/master/src/lab/energy2d) or
[`grapher`](https://github.com/concord-consortium/lab/tree/master/src/lab/grapher)).

#### Module Build Configuration - *.build.js file

Each Lab's module contains file `name.build.js`. It is a RequireJS Optimizer build profile. Useful,
related resources:

- [RequireJS Build Profile Help](http://requirejs.org/docs/optimization.html#wholeproject)
- [Example Build File with All Options
Documented](https://github.com/jrburke/r.js/blob/master/build/example.build.js)

**If you create new build file, make sure that you use one of the existing build profiles as a
reference!** It will enforce consistent style and options across all Lab's modules.

Lab's build profiles use [almond](https://github.com/jrburke/almond) module - a replacement AMD
loader for RequireJS. It is a smaller "shim" loader, providing the minimal AMD API footprint that
includes loader plugin support.

Why? [almond](https://github.com/jrburke/almond) allows us to create the resulting library which is
totally independent from RequireJS. It is a reasonable approach as RequireJS is used only for module
definition, dependency resolving and building a single file library using Optimizer. The
asynchronous module loading is not utilized by the final Lab library, so there is no need to force
users to load whole RequireJS library. Instead, use and include minimalistic RequireJS API
replacement.

#### Module Public API - public-api.js file

If module exposes API using global variables, it should define it in `public-api.js` file. It is
a typical RequireJS module, which just adds properties to `window` object. You can look at
[`src/md2d/public-api.js`](https://github.com/concord-consortium/lab/blob/master/src/lab/md2d/public-api.js),
[`src/energy2d/public-api.js`](https://github.com/concord-consortium/lab/blob/master/src/lab/energy2d/public-api.js)
or [`src/grapher/public-api.js`](https://github.com/concord-consortium/lab/blob/master/src/lab/grapher/public-api.js)
file for a reference.

This files are **not necessary**, but **highly recommended** if module has to define some global
variables. It is a convention used internally by Lab repository. Such files are enforcing clean
definition of public API exposed by modules. Developers will have certainty that all global
variables are defined **there and only there**.

Execution of this script should be enforced by build profile (*.build.js files described above).
Most often is done by `wrap` option:

      // Protect global namespace and call Public API export.
      wrap: {
        start: "(function() {",
        // Almond by default simulates async call of require (sets timeout).
        // Last argument (true) forces sync call instead.
        end: "require(['module-name/public-api'], undefined, undefined, true); }());"
      }

#### CoffeeScript Files Support

The Lab project is configured to easily support CoffeeScript sources. RequireJS plugin called
**require-cs** is used for dynamic loading of CoffeeScript sources.

To enable CoffeeScript support, make sure that module's build profile (see section about *.build.js
files) contains following options:

    // Additional modules.
    paths: {
    'cs' :'../vendor/require-cs/cs',
    'coffee-script': '../vendor/coffee-script/extras/coffee-script'
    },
    //Stub out the cs module after a build since
    //it will not be needed.
    stubModules: ['cs'],
    // The optimization will load CoffeeScript to convert
    // the CoffeeScript files to plain JS. Use the exclude
    // directive so that the coffee-script module is not included
    // in the built file.
    exclude: ['coffee-script']

`md2d` module has CoffeeScript support enabled, so you can use
[its build profile](https://github.com/concord-consortium/lab/blob/master/src/lab/md2d/md2d.build.js)
as a reference.

- To define a CoffeeScript module just use typical RequireJS syntax converted to CoffeeScript:

        define (require) ->
          # Dependencies.
          CoffeeScriptDependency = require 'cs!other-module-name/file-name'
          JavaScriptDependency   = require 'module-name/file-name'

          class SomeClass extends BaseClass
          // (...)

- You can also load CoffeeScript in JavaScript files:

        define(function (require) {
          // Dependencies.
          var CoffeeScriptDependency = require('cs!module-name/file-name');
          // (...)

Just remember about **cs!** prefix in paths when loading CoffeeScript sources. RequireJS Optimizer
will convert such files to plain JavaScript and include them in the final library.

### Generated Examples: `public/examples/`

The `public/examples/` directory is automatically generated running `make` and is not part of the repository.

When `bin/guard` is running any changes to files in the `src/examples/` directory cause automatic rebuilding
of the associated files in the `public/examples/` directory.

### HTML and CSS Generation

[Haml](http://haml-lang.com/) is used to generate most of the HTML in the `public/` directory.

[kramdown](http://kramdown.rubyforge.org/) is used to generate `readme.html` in `public/` from Mardown markup.

[Sass](http://sass-lang.com/) is used to generate the CSS assets. The Sass markup may be in the form of
`*.sass` or `*.scss` files

The [Bourbon](http://thoughtbot.com/bourbon/) library of Sass mixins is included.

- [Bourbon documentation](http://thoughtbot.com/bourbon/)
- [ASCIIcast 330: Better SASS With Bourbon](http://asciicasts.com/episodes/330-better-sass-with-bourbon)
- [Introducing Bourbon Sass Mixins](http://robots.thoughtbot.com/post/7846399901/introducing-bourbon-sass-mixins)


## Testing: `test/`

Lab's JavaScript tests use [Vows](http://vowsjs.org), an asynchronous behavior driven framework based
on [Node.js](http://nodejs.org/). In addition Lab uses [jsdom](https://github.com/tmpvar/jsdom), a
lightweight CommonJS implementation of the W3C DOM specifications. Lab's test setup was inspired
by that used by [d3.js](http://mbostock.github.com/d3/). The development dependencies for running the
tests are installed using [npm](http://npmjs.org/).

Running the tests:

    $ make test
    ................................. . . .. . . .
    x OK > 40 honored (0.012s)

If you are running `bin/guard` the tests run automatically anytime a change is made in the JavaScript
files in the `src/` or `test/` directory.

The results of the tests are displayed in the console that `bin/guard` is running in.

If the bottom of the console window is viewable you will see new test results whenever you save a changes.

Recent versions of nodejs/v8 support TypedArrays -- this make it possible to more extensively
test lab.arrays which is designed to support using either typed or regular arrays for computation.

`test/env.js` uses the node module [jsdom](https://github.com/tmpvar/jsdom) to setup resources for
simple emulation of a browser.

[Vows](http://vowsjs.org) integrates the [standard nodejs assertions](http://nodejs.org/docs/latest/api/assert.html)
with an additional collection of useful [assertions](http://vowsjs.org/#assertions) summarized below:

- numerical

        assert.greater (3, 2);
        assert.lesser (2, 3);
        assert.inDelta (Math.random(), 0, 1);

- equality

        assert.equal          (4, 4);
        assert.strictEqual    (4 > 2, true);
        assert.notEqual       (4, 2);
        assert.strictNotEqual (1, true);
        assert.deepEqual      ([4, 2], [4, 2]);
        assert.notDeepEqual   ([4, 2], [2, 4]);

- type

        assert.isFunction (function () {});
        assert.isObject   ({goo:true});
        assert.isString   ('goo');
        assert.isArray    ([4, 2]);
        assert.isNumber   (42);
        assert.isBoolean  (true);
        assert.typeOf     (42, 'number');
        assert.instanceOf ([], Array);

- truth

        assert.isTrue  (true);
        assert.isFalse (false);

- null, undefined, NaN

        assert.isNull      (null);
        assert.isNotNull   (undefined);
        assert.isUndefined ('goo'[9]);
        assert.isNaN       (0/0);

- inclusion

        assert.include ([4, 2, 0], 2);
        assert.include ({goo:true}, 'goo');
        assert.include ('goo', 'o');

- regexp matching

        assert.match ('hello', /^[a-z]+/);

- length

        assert.length ([4, 2, 0], 3);
        assert.length ('goo', 3);  *** not working ***

- emptiness

        assert.isEmpty ([]);
        assert.isEmpty ({});
        assert.isEmpty ("");

- exceptions

        assert.throws(function () { x + x }, ReferenceError);
        assert.doesNotThrow(function () { 1 + 1 }, Error);

Additionally `test/env-assert.js` has a number of useful additional assertions copied from
[d3.js](http://mbostock.github.com/d3/).

_**Note**: Using a more specific assertion usually results in more useful error reports._

There are also many interesting test examples and patterns in the
[d3.js test directory](https://github.com/mbostock/d3/tree/master/test) that can be adapted for use in Lab.

### A Simple Example of Test Driven Development

Here's a simple example that is part of the tests for `lab.arrays.js` to test the `arrays.max()` function:

    "find max in array with negative and positive numbers": function(max) {
      assert.equal(max([3, -1, 0, 1, 2, 3]), 3);
    },

The 'model stepping' tests are a good example where the tests help helped drive new features. The basic
features I was testing in this section relate to the existing functionality exposed by the Stop, Start, Go, and
Reset buttons as wells as the extended keyboard controls that allow stepping forward and backwards a step at a time.

First I created this test that passed:

    "after running running one tick the model is at step 1": function(model) {
      model.tick();
      assert.equal(model.stepCounter(), 1);
      assert.isTrue(model.isNewStep());
    },

In thinking about driving out changes to KE, PE and Temperature of the molecular model itself I realized
I'd like the capability to run a specific number of steps forward and then check the results.

I then wrote this test that failed -- because the model.tick() function didn't yet take an optional argument to
run multiple steps forward:

    "after running 9 more ticks the model is at step 10": function(model) {
      model.tick(9);
      assert.equal(model.stepCounter(), 10);
      assert.isTrue(model.isNewStep());
    },

After saving the change I saw the new test failure reported in my console. I then implemented the new
feature in the actual `src/lab/molecules.js`. Less than a second after saving the file the tests
completed and the report showed it passing.

This is a very simple example -- but part of the value of this kind of test driven development is in first
thinking of how something should behave rather than in how to get it to actually do the work.

Since I already had this function for running one model step:

    model.tick()

Adding an optional numeric argument for running more steps is a fine way to express the intent of the new feature:

    model.tick(9)

In more complicated coding thinking about how to express the intent clearly and then what the result
should be if that intent is successful **FIRST** ... and then 'driving out' the actual implementation to
achieve that result can result in a better architecture -- and of course you also end up with tests.

Because the tests run SO quickly I can interactively change the code in the module or the test and
immediately see results.

### Debugging Tests using the node debugger

Sometimes it can be helpful to break into a debugger when there is a problem in either the code
or the test setup itself. Node comes with a [debugger](http://nodejs.org/docs/latest/api/debugger.html)
which can be used in combination with vows and the tests.

First set a breakpoint by inserting the statement: `debugger;`

    suite.addBatch({
      "Thermometer": {
        topic: function() {
          debugger;
          return new components.Thermometer("#thermometer");
        },
        "creates thermometer": function(t) {
          assert.equal(t.max, 0.7)
        }
      }
    });

Start the node debugger and pass in the full command line to run the tests:

    node debug ./node_modules/vows/bin/vows --no-color

The debugger will break at the beginning of vows:

    < debugger listening on port 5858
    connecting... ok
    break in node_modules/vows/bin/vows:3
      1
      2
      3 var path   = require('path'),
      4     fs     = require('fs'),
      5     util   = require('util'),

Enter `cont` to continue execution until your breakpoint.

    debug> cont
    < ·
    < ········
    < ·
    <
    break in test/lab/components/components-test.js:13
     11   "Thermometer": {
     12     topic: function() {
     13       debugger;
     14       return new components.Thermometer("#thermometer");
     15     },

To evaluate expressions type `repl`  -- use ctrl-C to exit the repl:

    repl
    Press Ctrl + C to leave debug repl
    > initialization_options
    { model_listener: false,
      lennard_jones_forces: true,
      coulomb_forces: true }
    > atoms[0].charge
    -1

Enter **ctrl-C** to exit the repl and return to the debugger.

Enter **ctrl-D** to exit the debugger.

[node-inspector](https://github.com/dannycoates/node-inspector)
[npm package for node-inspector](http://search.npmjs.org/#/node-inspector)

#### Using node-inspector while debugging

[node-inspector](https://npmjs.org/package/node-inspector) supports using the webkit inspector in Chrome to support
interactive debugging in node. This can be particualrly help when debugging tests.

Example:

Add a debugger statement to your test:

    originalModelJson = fs.readFileSync(testDir + "expected-json/" + modelJsonFile).toString();
    modelName = /\/?([^\/]*)\.json/.exec(modelJsonFile)[1];
    debugger;
    originalModel = JSON.parse(originalModelJson);
    model = new Model(originalModel);

Start a debugging session:

    $ node --debug-brk ./node_modules/vows/bin/vows --no-color test/vows/mml-conversions/deserialize-serialize-test.js
    debugger listening on port 5858

Start node-inspector:

    $ ./node_modules/.bin/node-inspector &
    info  - socket.io started
    visit http://0.0.0.0:8080/debug?port=5858 to start debugging

## Physical constants and units

The core of the molecular dynamics engine performs computations using dimensioned quantities; we do
not nondimensionalize to reduced units.  The units used internally are:

- femtoseconds
- nanometers
- Dalton (atomic mass units)
- elementary charges
- Kelvin

(Note that we will shortly switch to representing time in picoseconds rather than femtoseconds.)

The above implies that the 'natural' unit of energy within the application is the "Dalton nm^2 /
fs^2", and the natural unit of force is the "Dalton nm / fs^2". We call these "MW Energy Units" and
"MW Force Units" respectively; however, externally-facing methods accept and report energies in
electron volts, rather than "MW Units".

The molecular dynamics engine in `src/md-engine` contains a submodule, defined in `src/md-
engine/constants/` which defines physical useful constants and allows one to perform some unit
conversions in a mnemonic way.

Once you have `require()`d the constants module appropriately, you can access the constants, 2
converter methods, and an object that defines the various units. For the following, assume the
`constants` module has been `require()`d into the variable `constants`.

### Units

The various units are available as properties of the object `constants.unit`, and are named
appropriately. The units themselves are objects, but their properties are not external API; rather,
the unit objects are expected to be passed as arguments to conversion methods which return numeric
values. Units are named in the singular and are written as all-uppercase (they are constants).

Some example units are:

- `constants.unit.JOULE` constants.unit.MW_ENERGY_UNIT` (Dalton nm^2 / fs^2, see above)
- `constants.unit.METERS_PER_FARAD`

### Physical Constants

The various constants are defined as properties of the `constants` object. However, these do not
have numerical values; instead, they each contain a single method, `as`, which accepts a unit (see
above) and returns the numerical value of that constant in terms of that unit. This is intended to
be a convenience for the programmer and to reduce the likelihood that he or she will forget to keep
track of the units in which a value is stored.

For example,

- `constants.BOLTZMANN_CONSTANT.as(constants.unit.JOULES_PER_KELVIN)` (== 1.380658e-23)
- `constants.PERMITTIVITY_OF_FREE_SPACE.as(constants.unit.FARADS_PER_METER)` (== 8.854187e-12)

### Unit conversions

The `constants` module does not attempt to do dimensional analysis (for example, converting kg m/s^2
into Newtons). However, it can convert a value between two different units that measure the same
type of quantity, and it can supply conversion ratios that make it easier to do dimensional analysis
carefully in your own code.


#### Converting a value between two unit types:

To convert the value 1kg into Daltons (aka atomic mass units), use the `convert` method:

`constants.convert(1, { from: constants.unit.KILOGRAM, to: constants.unit.DALTON })` (==
6.022137376997844e+26)

#### Finding the ratio between two unit types and rolling your own unit conversions:

To find the number of atomic masses in 1 kg, use the `ratio` method with the `per` argument:

`constants.ratio(constants.unit.DALTON, { per: constants.unit.KILOGRAM })`
(== 6.022137376997844e+26)

This form of ratio is especially useful for unit conversion, and the "per" is intended as a
mnemonic. The number reported above, for example, is easily understood to be "6.022 x 10^26 Dalton
per kilogram" and can therefore be used as a factor that "cancels" kilograms and replaces them with
Daltons in a compound unit such as "kg m/s".

However, sometimes you want the value of a Dalton expressed as kilograms. Although you *could*
reverse the units in the above function call, or divide 1 by the result above, it is better to use
the mnemonic `as` form of `ratio`:

`constants.ratio(constants.unit.DALTON, { as: constants.unit.KILOGRAM })` (== 1.66054e-27)

## Deployment

[Deployment](developer-doc/deployment.md)

## References

### Molecular Simulation

- [Basic molecular dynamics](http://li.mit.edu/Archive/Papers/05/Li05-2.8.pdf)
- [CHARMM: A theoretical introduction to molecular dynamics simulations and practical examples](http://www.ch.embnet.org/MD_tutorial/)

  This site has a basic introduction to the physics of molecular dynamics simulations, and practical
  exercises with the CHARMM package

- [Thermostat Algorithms for Molecular Dynamics Simulations](http://phjoan23.technion.ac.il/~phr76ja/thermostats.pdf)
- [the "flying ice cube"](http://en.wikipedia.org/wiki/Flying_ice_cube)

  One kind of unphysical effect that can arise. See linked paper.

- [SklogWiki: Lennard-Jones](http://www.sklogwiki.org/SklogWiki/index.php/Lennard-Jones_model)

#### Courses

- [CHE 800-002: Molecular Simulation](http://www.pages.drexel.edu/~cfa22/msim/msim.html)
    Cameron Abrams Department of Chemical Engineering at Drexel

- [Computational Physics](http://courses.theophys.kth.se/SI2530/)
- [Benchmark results for Lennard-Jones fluid](http://www.cstl.nist.gov/srs/LJ_PURE/index.htm)
- [Statistical Physics and Simulation](http://homepage.univie.ac.at/franz.vesely/simsp/dx/dx.html)

#### Reduced Units

- [softmatter:Simulation Variables/Units](http://matdl.org/matdlwiki/index.php/softmatter:Reduced_units)
- [An MD Code for the Lennard-Jones Fluid](http://www.pages.drexel.edu/~cfa22/msim/node27.html)
- [2.4 Reduced Units](http://homepage.univie.ac.at/franz.vesely/simsp/dx/node11.html)
- [Understanding molecular simulation: from algorithms to applications](http://books.google.com/books?id=XmyO2oRUg0cC&pg=PA41&lpg=PA41&dq=Reduced+Units+Lennard-Jones&source=bl&ots=Zx0F10o1yR&sig=2UJ4C-W8LuASjrvkoTxPA63XBos&hl=en&sa=X&ei=R0AWT7fmNOn10gHKx4jxAg&ved=0CGIQ6AEwBw#v=onepage&q=Reduced%20Units%20Lennard-Jones&f=false)
- [Molecular Dynamics Simulation: Nneoma Ogbonna](http://users.aims.ac.za/~nneoma/theses/NneomaAimsEssay.pdf)

## Dependencies

[Dependencies](developer-doc/dependencies.md)

### Full Screen API

- [JavaScript Full Screen API, Navigation Timing and repeating CSS Gradients](http://peter.sh/2011/01/javascript-full-screen-api-navigation-timing-and-repeating-css-gradients/)
- [Fullscreen API, enhanced Element Highlighting and progress on Flexbox](http://peter.sh/2011/08/fullscreen-api-enhanced-element-highlighting-and-progress-on-flexbox/)
- [Native Fullscreen JavaScript API (plus jQuery plugin)](http://johndyer.name/native-fullscreen-javascript-api-plus-jquery-plugin/)
- [Gecko:FullScreenAPI](https://wiki.mozilla.org/Gecko:FullScreenAPI)
- [Mozilla full-screen API progress update](http://blog.pearce.org.nz/2011/09/mozilla-full-screen-api-progress-update.html)
- [fullscreen API coming to browsers near you?](http://ajaxian.com/archives/fullscreen-api-coming-to-browsers-near-you)
- [Full Screen Demos](http://html5-demos.appspot.com/static/fullscreen.html)
- [stackoverflow: Chrome Fullscreen API](http://stackoverflow.com/questions/7836204/chrome-fullscreen-api)
