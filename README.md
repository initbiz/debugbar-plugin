# Debugbar Plugin

Easily see what's going on under the hood of your October CMS application.

# Installation

To install with Composer, run from your project root

    composer require rainlab/debugbar-plugin

### Usage

Set `debug` to `true` in `config/app.php`, and the debugbar should appear on your site to all authenticated backend users with the `rainlab.debugbar.access_debugbar` permission.

If you would like to make the debugbar accessible to all users regardless of authentication & permissions, then set `allow_public_access` to `true` in `config/rainlab/debugbar/config.php`.

See [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) for more usage instructions and documentation.

To include exceptions in the response header of ajax calls set `debugAjax` to `true` in `config/app.php`.
