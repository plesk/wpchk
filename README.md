# WPchk powered by Plesk

Plesk WPchk is a WordPress Security checker tool to analyze the security status of all WordPress instances on a Linux server.

It will not make any changes, but display security issues found for each of the found WordPress instances.
We are happy to receive your feedback at wpchk@plesk.com.

## How to use

1. Download and install the standalone script using this command in your terminal:

   `curl https://raw.githubusercontent.com/plesk/wpchk/master/installer > wpchk-installer && sh wpchk-installer`

2. Run the script with this command:

   `wpchk`

That's it!

![WPchk powered by Plesk](screenshot.png)

### Additional options

Displays the help page:

`wpchk --help`

Updates WPchk to the latest version to include latest security checks:

`wpchk --update`

Outputs scan results in the JSON format:

`wpchk --json`

Scan specific path only (can also be combined with `--json`):

`wpchk --path=/var/www/vhosts/example.com`

Shows WPchk version:

`wpchk --version`

## How to fix

Get the WordPress Toolkit to fix all issues with one click and stay always up-to-date & secure: <https://www.plesk.com/wp-toolkit/>.

If you have any questions or feedback, please don't hesitate to contact us: wpchk@plesk.com.

## Technical Requirements

The minimum required PHP version is 5.4 due to WP-CLI dependency.

## License

Licensed under the Plesk Software License. You may obtain a copy of the License at <https://github.com/plesk/wpchk/blob/master/LICENSE.md>.
