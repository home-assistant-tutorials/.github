## Welcome

This organization has the purpose to bundle some tutorials about Home Assistant.
For the beginning the scope is the development of custom code like cards or
integrations.

## Howto

Each tutorial is done as a separate github repository to be able to ship code
alongside. To learn how to set up the development environment at all see
*tutorial 1*.

Depending on the type of the tutorial the repository is cloned into different
"workspaces". Tutorials of cards are cloned into a frontend workspace with the
path `config/www/tutor`. A `hello-moon` repository would get the path
`config/www/tutor/hello-moon`.

## Tutorials

### Table of contents

#### [01. Setting up the development environment](https://github.com/home-assistant-tutorials/01.development-environment)

* how to use the container of the core developers

#### [02. Hello world card](https://github.com/home-assistant-tutorials/02.hello-world-card)

* how to get some hello world output from a card
* how to define the card as a custom Element of HTML
* how to add the card as a new resource

#### [03. Hello world card plus](https://github.com/home-assistant-tutorials/03.hello-world-card-plus)

* how to assist the setup with error messages
* how to provide a default configuration for the card
* how to add the card to the visual selection

#### [04. Plain vanilla javasript toggle card](https://github.com/home-assistant-tutorials/04.toggle-card-vanilla-js)

* how to do an interactive toggle card with plain vanilla javascript
* how to create the toggle helper entity
* how to organize the class
* how to encapsulate CSS by use of a prefix (BEM inspired)
* how to read and write from/to the hass object (full roundtrip)
* how to bind the card to the event callback

#### [05. Toggle card with shadow DOM](https://github.com/home-assistant-tutorials/05.toggle-card-with-shadow-dom)

* how to attach a shadow dom inside the constructor
* how to clean up the lifecycle
* how to get rid of the prefixes
* how to migrate from BEM methodology to nested CSS modifiers

#### [06. Toggle with graphical card configuration (vanilla js)](https://github.com/home-assistant-tutorials/06.toggle-with-graphical-configuration)

* how to create and organize the class of the editor
* how to register the editor
* about the lifecycle of the editor
* how to implement minimal requirements

#### [07. Toggle card to hacs](https://github.com/home-assistant-tutorials/07.toggle-card-to-hacs)

* how to install HACS
* how to layout the Github repository for a custom HACS card
* how to use the HACS repository

#### [08. Toggle card with a toolchain](https://github.com/home-assistant-tutorials/08.toggle-card-with-toolchain)

* how to install nodejs and npm into the development container
* how to update them to recent versions
* how to use npm (the basics)
* how to install *Parcel*
* how to setup and organize the projects layout
* how to inline *HTML* and *CSS* files

## Home Assistant

This organization provides community created content. It is related to the Home
Assistant project. It is not an official part of it.

* [Home Assistant Home](https://www.home-assistant.io)
* [Home Assistant on Github](https://github.com/home-assistant)
* [Home Assistant Community](https://community.home-assistant.io)
* [Home Assistant on Discord](https://discord.com/channels/330944238910963714/332167321311510530)
