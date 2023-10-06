Modules:
* Modules are small pieces of software that are generally built for one specific purpose. (The app is already multi-purpose; there is no need for a module that fulfills multiple purposes. If a user wishes to make the module fulfill multiple needs, they should get multiple modules to accommodate such needs. However people are still free to do whatever is comfortable.)
* The functionality of the app is entirely determined by modules.
* A user can choose to install, remove, or exclude a module.
* Modules run one level after another **(Dependencies/Hierarchy)**.
* There are some modules that, unlike most others, cannot be removed. **(Core UI)**

Modules --> Core UI:
* The "Core UI" is the backbone of the app.
* Theoretically, a user can delete essential modules if left unchecked, therefore rendering the app unusable.
* To nullify the chance of this happening, removing the Core UI modules is impossible.

Modules --> Advanced Features:
* Modules can refernce each other with links.

Dependencies/Hierarchy:
* A module can run on any level as long as it's not above its dependencies.
* A module will always run after its dependency.
* When a module runs, changes are made to the UI. These changes are called "migrations."