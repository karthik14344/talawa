# Talawa
[![Build Status](https://travis-ci.org/PalisadoesFoundation/talawa.svg?branch=master)](http://www.palisadoes.org/) 
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub stars](https://img.shields.io/github/stars/PalisadoesFoundation/talawa.svg?style=social&label=Star&maxAge=2592000)](https://github.com/PalisadoesFoundation/talawa)
[![GitHub forks](https://img.shields.io/github/forks/PalisadoesFoundation/talawa.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/PalisadoesFoundation/talawa)

[![N|Solid](images/talawa-logo-lite-200x200.png)](https://github.com/PalisadoesFoundation/talawa)

Talawa is a modular open source project to manage group activities of both non-profit organizations and businesses.

Core features include:

 1. Membership management
 2. Groups management
 3. Event registrations
 4. Recurring meetings
 5. Facilities registrations

 ``talawa`` is based on the original ``quito`` code created by the [Palisadoes Foundation][pfd] as part of its annual Calico Challenge program. Calico provides paid summer internships for  Jamaican university students to work on selected open source projects. They are mentored by software professionals and receive stipends based on the completion of predefined milestones. Calico was started in 2015. Visit [The Palisadoes Foundation's website](http://www.palisadoes.org/) for more details on its origin and activities.

# Talawa Components

`talawa` has these major software components:

1. **talawa**: [A mobile application with social media features](https://github.com/PalisadoesFoundation/talawa)
1. **talawa-api**: [An API providing access to user data and features](https://github.com/PalisadoesFoundation/talawa-api)
1. **talawa-admin**: [A web based administrative portal](https://github.com/PalisadoesFoundation/talawa-admin)
1. **talawa-docs**: [The online documentation website](https://github.com/PalisadoesFoundation/talawa-docs)

# Documentation
 - The talawa documentation can be found [here](https://palisadoesfoundation.github.io/talawa-docs/).
 - Want to contribute? Look at [CONTRIBUTING.md][link] to get started.
 - Visit the [Talawa GitHub][repo] to see the code.
 
# Installation for Developers

## Prerequisites

You'll need to setup the IDE and mobile device emulator on your local system, and have access to a system running the Talawa API which the mobile needs to access to operate properly.

1. **Development Environment**: You'll need to have the following installed:
    1. [Flutter SDK][fsdk]
    1. [Android Studio][astudio]
1. **API Environment**: 
    1. Check the [Talawa API repository](https://github.com/PalisadoesFoundation/talawa-api) for information on how to setup the API on your local machine or a machine under your legitimate control. There is a section in the README.md file that discusses installation.
    2. We also have a test environment if you are not inclined to setup or customize your own API server. Information about this can be found in the [Talawa documentation site](https://palisadoesfoundation.github.io/talawa-docs/)

## Command Line Steps

1. Clone and change into the project.
    ```sh
    $ git clone https://github.com/PalisadoesFoundation/talawa.git
    $ cd talawa
    ```
1. Install packages
    ```sh
    $ flutter pub get
    ```
1. Start developing!

# Other Important LInks
 
[repo]: <https://github.com/PalisadoesFoundation/talawa>
[pfd]: <http://www.palisadoes.org>
[fsdk]: <https://flutter.dev/docs/get-started/install>
[astudio]: <https://developer.android.com/studio>
[link]:<https://github.com/PalisadoesFoundation/talawa/blob/master/CONTRIBUTING.md>
