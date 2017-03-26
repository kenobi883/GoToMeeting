# GoToMeeting Client Library

This package provides a Guzzle-based library to interact with the
[Citrix GoToMeeting API](https://developer.citrixonline.com/api/gotomeeting-rest-api).

## State of Development

**I am no longer actively working with the Citrix API**, and thus am not maintaining this library.
If you are interested in taking this client library further and becoming the maintainer,
please reach out to me via email.

## Notes

The meeting-specific part of the API is nearly fully implemented.

The group and organizer API methods need more thorough testing and methods implemented.
I currently do not have a proper account to validate the implementation with.

## Contributing

Pull requests are welcome. PHPUnit tests are provided for Model and Service classes. "Live" tests
are also available to validate implementation against the API with a real API key and account
credentials. The live tests are skipped if credentials are not provided.

When possible, please adhere to [PSR-1](http://www.php-fig.org/psr/psr-1/) and
[PSR-2](http://www.php-fig.org/psr/psr-2/) for code conventions and style.
