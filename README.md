# Icejoomla Plugin

Welcome to the Icejoomla Plugin repository on GitHub. 

Here you can browse the source code, look at open issues and keep track of development.


## Requirements

- PHP with the 21 Oct 2026 security fixes for critical remote code execution flaws (GHSA-w8hw-w9fx-j79w, GHSA-6wmf-4rv5-p3rp; [php.net advisory](https://www.php.net/releases/8_2_35.php)): **8.2.35, 8.3.36, 8.4.27, 8.5.12 or later**. PHP 8.1 and older no longer receive security fixes.
- The plugin code itself has been checked for PHP 8.2 to 8.5 (syntax, PHPCompatibility, and a run against stubbed Joomla/IceBooking classes). It has not been run inside a real Joomla or IceBooking installation.
- Joomla / IceBooking: this plugin targets legacy Joomla (1.5/2.5-era) APIs (`JRequest`, the `DS` constant, `JApplicationHelper::getPath`, a 1.5 install manifest) and the commercial [IceBooking](http://icejoomla.com) gateway interface. It has not been ported to Joomla 4/5. [Joomla 4.4 recommends PHP 8.2](https://manual.joomla.org/docs/4.4/get-started/technical-requirements/), [Joomla 5.x requires PHP 8.1 or later and recommends 8.3](https://manual.joomla.org/docs/5.4/get-started/technical-requirements/) and [Joomla 6.x requires PHP 8.3 or later](https://manual.joomla.org/docs/next/get-started/technical-requirements), but we could not find any statement that IceBooking supports Joomla 4 or later. Unless IceBooking's vendor confirms support for a Joomla version that runs a patched PHP 8.2+, a site using this plugin should not be assumed able to run a patched PHP. Check with the IceBooking vendor before upgrading PHP.

## Documentation

* [Paystack Documentation](https://developers.paystack.co/v2.0/docs/)
* [Paystack Helpdesk](https://paystack.com/help)

## Support

For bug reports and feature requests directly related to this plugin, please use the [issue tracker](https://github.com/PaystackHQ/plugin-icejoomla/issues). 

For general support or questions about your Paystack account, you can reach out by sending a message from [our website](https://paystack.com/contact).

## Community

If you are a developer, please join our Developer Community on [Slack](https://slack.paystack.com).
