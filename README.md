# Getting Started with Rails
The maintainer of this repository had decided it was time for them to renew their [*Rails*](https://rubyonrails.org) knowledge, and so what better place to start, than the latest edition **(v7.0.4)** of [Getting Started with Rails](https://guides.rubyonrails.org/getting_started.html)?

# Docker
One slight plot-twist found in this repository is, the maintainer of this repository develops 100% in *Docker* containers, so any variation from the official guide will be noted below.

The maintainer of this repository does not intend to publish a *Docker* *image*, since the tutorial is brief.

### Installation
[Section 3.1](https://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project-installing-rails) is about installing *Rails*.

What follows is the list of commands to run on a machine with *Docker* available in order to proceed with the tutorial:

1. `$ docker pull ruby:bullseye`
2. `$ docker run -d -p 3000:3000 -v /Users/ultasun/src:/src -t ruby:bullseye`
3. `$ docker exec -it <CONTAINER_NAME> /bin/bash`
4. `# apt-get -y update && apt-get -y upgrade`
5. `# apt-get install sqlite3`
6. `# gem install rails`

Then, the verification commands may be ran:

7. `# ruby --version`
8. `# sqlite3 --version`
9. `# rails --version`

Continue on, from [Section 3.2](https://guides.rubyonrails.org/getting_started.html#creating-the-blog-application).

# Notable Differences from *The Guide*
What follows is the **notable** differences between this repository and the guide, starting from [Section 3.2](https://guides.rubyonrails.org/getting_started.html#creating-the-blog-application).

*None so far*

# Credits
The work in this repository is the work of the team who wrote it on [RailsGuides](https://guides.rubyonrails.org/), please see the `LICENSE` file in this repository.
