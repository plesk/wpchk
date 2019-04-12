# WPchk powered by Plesk

Plesk WPchk is a WordPress Security checker tool to analyze the security status of all WordPress instances on a Linux server.

It will not make any changes, but display security issues found for each of the found WordPress instances.
We are happy to receive your feedback at wpscan@plesk.com.

## How to use

1. Download and install the standalone script using this command in your terminal:

`sh <(curl https://raw.githubusercontent.com/plesk/wpchk/master/installer)`

2. Run the script with this command:

`wpscan`

That's it!

![WPchk powered by Plesk](https://raw.githubusercontent.com/plesk/wpchk/master/wpscan-screenshot.png)

### Additional options

`wpchk --help`

Displays the help page.

`wpchk --update`

Updates WPchk to the latest version to include latest security checks.

`wpchk --json`

Outputs scan results in the JSON format.

## How to fix

Get the WordPress Toolkit to fix all issues with one click and stay always up-to-date & secure: https://www.plesk.com/wp-toolkit/

If you have any questions or feedback, please don't hesitate to contact us: wpscan@plesk.com

## License

Licensed under the Plesk Software License. You may obtain a copy of the License at https://github.com/plesk/wpchk/blob/master/LICENSE.md.
