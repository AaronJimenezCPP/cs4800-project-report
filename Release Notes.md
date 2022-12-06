# 0.1.0 Initial Release

## Compatability 

This application should theoretically be compatible with all platforms than can run Node.js. 

Actual testing was only done on Windows machines and AWS Amplify, without any issues.

## Features
- Allows users to create wildfire risk predictions using future dates and their recent rainfall conditions.
- Displays predictions using a heatmap on the Google Maps JavaScript API.
- Displays a human readable table of locations and their risk levels.
- Features an information section that explains the application and some relevant facts.

## Bugs
- Currently no known bugs.

## Limitations
- Backend API returns data for a limited set of locations. The coverage is incomplete.
- API returns risk levels associated with single points. This currently does not extend to any range beyond that point. 