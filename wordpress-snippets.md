# Wordpress snippets

## autoupdates aktivieren

`define( 'AUTOMATIC_UPDATER_DISABLED', true );`

Aktivierung aller Core Updates für dieses Wordpress 

`add_filter( 'auto_update_plugin', '__return_true' );`

Aktivierung der automatischen Updates aller genutzten Plugins in diesem Wordpress

`add_filter( 'auto_update_theme', '__return_true' );`

Aktivierung der automatischen Updates aller genutzten Themes in diesem Wordpress