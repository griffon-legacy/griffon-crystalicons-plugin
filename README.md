
Everaldo's Crystal icon set
---------------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/crystalicons](http://artifacts.griffon-framework.org/plugin/crystalicons)


Provides a shortcut for adding icons based on Everaldo's [Crystal icon set][1].

Usage
-----

The following nodes will become available on a View script upon installing this plugin

| *Node*      | *Property* | *Type* | *Default*   | *Bindable* |
| ----------- | ---------- | ------ | ----------- | ---------- |
| crystalIcon | icon       | String |             | no         |
|             | size       | int    | `16`        | no         |
|             | category   | String | `actions`   | no         |

Valid values for `icon` can be obtained by running **crystal-icon-selector** and inspecting the tooltip of the chosen icon.

Valid values for `size` property are: 16, 22, 24, 32, 48, 64, 128.

Valid values for `category` property are: actions, apps, devices, filesystems, mimetypes.

Scripts
-------

 * **crystal-icon-selector** - launches a window that displays all available icons (Hover an icon to see the icon name)

[1]: http://everaldo.com/crystal

