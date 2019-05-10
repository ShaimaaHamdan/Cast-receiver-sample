# cast-receiver-sample
This Google Cast demo application shows how to build a receiver application that can cast videos from a Cast Sender device. It is meant to demonstrate the use of the Google Cast Receiver APIs. 

## Dependencies
* A Google Cast Receiver Device (eg. Chromecast)

## Setup Instructions
* You will need a Google Cast device such as a Chromecast to run this sample code
* Register your Cast device Developer Console ((http://cast.google.com/publish) to allow it to run this sample
* Register a custom receiver application on the Cast Developers Console (http://cast.google.com/publish). The URL to use will be the IP address of the system you will run the receiver server from. If you run the server using the provided NodeJS server on your local machine, enter the ip-address of your computer with it's non local IP (eg. http://172.17.21.148:9999/sample_media_receiver.html). You will get an App ID when you finish registering your application.
* Setup the project dependencies
* deploy to an existing server or run python -m http.server 1701 if you have paython installed to host the html file

## Documentation
The source is heavily documented and for additional reference please refer to the Receivers section of the Google Cast documentation.

## References and How to report bugs
* Cast APIs: http://developers.google.com/cast/docs
* Design Checklist (http://developers.google.com/cast/docs/design_checklist)
* If you find any issues, please open a bug here on GitHub

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE
