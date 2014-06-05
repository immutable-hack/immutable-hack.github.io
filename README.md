# Immute

An Om and Datomic inspired development stack.

# Get Involved
* [Visit our backlog](https://www.pivotaltracker.com/n/projects/1074796) to see how you can help!
* [Join our NYC Meetup](http://www.meetup.com/The-New-York-Immutable-Hack/) and drop in to hack the stack.

# Get Started

## Prerequisites

* Install [Leiningen](http://leiningen.org/#install)
* Install the [Leiningen cljs-build plugin](https://github.com/emezeske/lein-cljsbuild#installation)

## Get the Immutable Stack

Git checkout the [immutable-stack](https://github.com/KitchenTableCoders/immutable-stack.git) so you have the demonstration app from David and Kovas ([see Inspiration](#Inspiration))

```bash
git clone https://github.com/KitchenTableCoders/immutable-stack.git
```

## Install the Immute Template for Leiningen
This template lets you build a basic app - [currently incomplete](https://www.pivotaltracker.com/story/show/72307658)

Do the following to install the app: 

```bash
git clone https://github.com/immutable-hack/immute-template
cd immute-template
lein install
cd ..
```

Create a new app with the template:
```bash
lein new immute my-first-immute-app
```

# Inspiration

This project draws inspiration from:

* [David Nolen](https://github.com/swannodette) - who is an enthusiastic and friendly Clojure developer. 
He and his cohort, [Kovas Boguta](https://github.com/kovasb) created [The Immutable Stack](http://kitchentablecoders.com/class/2014/04/12/the-immutable-stack/).
* [Ruby On Rails](http://rubyonrails.org/) - teaches us what to do (ease the transition to a new language and stack) and what not to do (railroad users into a brittle app framework which promotes low cohesion). 
