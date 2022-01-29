# Inesonic SpeedSentry PHP API

This package provides a simple PHI API API you can use to communicate with
Inesonic SpeedSentry infrastructure.  You can use this API to:

- Configure Inesonic SpeedSentry programmatically.

- Query latency, SSL expiration data, and event histories associated with your Inesonic SpeedSentry subscription.

- Pause and resume monitoring.

- Trigger custom events, using Inesonic SpeedSentry to report those events to you.

For details on Inesonic SpeedSentry, please goto https://speed-sentry.com.

## Developer Documentation

The API is designed to be simple to use.  For details on how to integrate
Inesonic SpeedSentry into your site or project, see
https://speedsentry-documentation.inesonic.com

## PHP Versions

This API is specifically written to work with PHP 7.4 and later.

## Dependencies

The PHP API is designed to use WordPress' functions if available.  If the PHP
API is ** not ** installed within WordPress, the plug-in will fall-back on
using the PHP file_get_contents function.

## License And Support

This package is licensed under the LGPLv3.

You are welcome to submit patches and/or request new features either through
GitHub or through SpeedSentry's internal support system.
