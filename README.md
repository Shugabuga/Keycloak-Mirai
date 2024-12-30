# Keycloak-Mirai
A lightweight and responsive Keycloak theme written in HTML, CSS, and some light JavaScript.

## Installation
Clone this repo in your Keycloak's themes directory, and then select it as a a Login theme in the Admin panel.

## Customization
It is best practice to customize with a separate theme and patching what files you want to edit. In a separate folder in your Keycloak themes directory, add a `theme.properties` with the following contents (assumes the Keycloak-Mirai theme is in the folder `keycloak-mirai`:

```
# Modify theme with name "keycloak-mirai"
parent=keycloak-mirai
```
