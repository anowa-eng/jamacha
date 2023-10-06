# Notes
## Modules:
1. The app is already multi-purpose; there is no need for a module that fulfills many purposes. If a user wishes to make the module fulfill many needs, they should get many modules to accommodate such needs. Anyhow, people are still free to do whatever is comfortable.

# Outline
## Modules:
* MODULES are small pieces of software in the app. They are generally built for one specific purpose. The app is already multi-purpose; there is no need for a module that fulfills many purposes. If a user wishes to make the module fulfill many needs, they should get as many modules as needed to accommodate them. Anyhow, people are still free to do whatever is comfortable.
* The functionality of the app is entirely determined by modules.
* A user can choose to install, remove, or exclude a module.
* Modules run one level after another **(Dependencies/Hierarchy)**.
* There are some modules that, unlike most others, cannot be removed. **(Core UI)**

### Core UI:
* The "CORE UI" is the backbone of the app.
* Theoretically, a user can delete essential modules if left unchecked. This can render the app unusable.
* To nullify the chance of this happening, removing the Core UI modules is impossible.

### Advanced Features:
* Modules can reference each other with links.

### Hierarchy:
* A module can run on any level as long as it's not above its dependencies.

#### Dependencies:
* DEPENDENCIES are modules that other modules depend on to add extra elements to; in other words, MIGRATE the UI.
* When a module runs, changes are made to the UI. These changes are called "migrations."
* A module's migration will always run after its dependency.