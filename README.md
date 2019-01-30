# FOSS4G
Attendees Registration Scanner

An android application that is used during the validation of tickets during an event. The app first scans the ticket barcode then 
checks if exists in the database then if true opens the camera to take a picture of the attendee, then nationality and is all updated
to the database.

This helps to verify the attendence and especially if a company is working on a no refund policy so people can not claim to have not 
attended if they did.

The app consists of a webview and that uses laravel to run the database queries. So you have to create your own query handling site I'd 
using laravel of any other framework that allows you to pass variables through the route which makes it easy to generate webaddresses and
concatenate them with say a Unique ticket ID and unload it once on the querying site and go on from there.
