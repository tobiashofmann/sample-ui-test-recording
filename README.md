# Sample UI test recording

This repository contains a sample Chrome DevTools recorder test. The test is showing how to use the recorder to capture an end user test. The sample app used to capture the test is the [SAP CAP SFLIGHT demo](https://github.com/SAP-samples/cap-sflight).

# UI Test

The script is used to filter the travel table for agency and travel status. A travel is selected from the result list, the detail page opened and there the booking detail is accessed.

![Sample Recording](doc//Sample%20test%20recording.gif)

# Using the test file

The recording is provided as a [JSON file](SFLIGHT%201.json). To run it in your browser, import it using the Chrome recorder. 

Ensure that the SFLIGHT app is [running and accessible](http://localhost:4004/travel_processor/webapp/index.html). You might have to log on first (user: amy / no password).
