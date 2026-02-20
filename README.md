# Helsinki Must-use Autoloader

Autoloads plugins installed in `WPMU_PLUGIN_DIR` subdirectories. Forked from [Bedrock Autoloader](https://github.com/roots/bedrock-autoloader).

Autoloaded plugins are listed in `Dashboard > Plugins > Must-use` table with `*` appended to their names.

Autoloaded plugins are listed in `wp plugin list` command output. **N.B** Due to technical limitations of the CLI command the autoloaded plugins will display `active` as their status.

## Installation

Upload `wp-mu-autoloader.php` to your `WPMU_PLUGIN_DIR` directory - usually `/wp-content/must-plugins`.

WordPress will automatically load the loader, which in turn loads the plugins in the subdirectories.
