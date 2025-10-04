# BovineLabs Solace

BovineLabs Solace is an integration library for Unity Services within the DOTS/ECS framework.

Access and updates are provided on [Buy Me a Coffee](https://buymeacoffee.com/bovinelabs) and support on [Discord](https://discord.gg/RTsw6Cxvw3).

## Installation

Solace is currently provided as a zip file containing itself and its dependencies. To install, extract it to your Unity `ProjectName/Packages` folder.

Solace depends on the base version of BovineLabs Core, which should be included in the release, and requires Extensions to be enabled with the Service world created.

While optional, Solace is designed to work with [BovineLabs Nerve](https://gitlab.com/tertle/com.bovinelabs.nerve), which provides integration with NetCode.

## Features

- **Authentication**: Simplified Unity Authentication Service integration with automatic token management
- **Analytics**: ECS-friendly analytics tracking with support for various data types
- **NetCode Integration**: Streamlined connection approval flow using Unity authentication tokens