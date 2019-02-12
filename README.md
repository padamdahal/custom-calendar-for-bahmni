# custom-calendar-for-bahmni
This script helps to add custom calendar for [Bahmni](https://www.bahmni.org "Bahmni Home"). This is an example of using Nepali calendar with the jquery calendar plugin available [here](https://www.npmjs.com/package/nepali-date-picker).

It scans through the web page for the possible date inputs and values with angluar directives. For the input fields, it adds an input field for custom calendar and when date is selected in custom calendar field, date is translated into AD and filled in the original input field. For date values to be displayed, it is just read and translated and assign to the html element.
## Usage
Include scripts and style for nepali date picker mentioned above, and customCalendar.js (after existing scripts) in bahmni apps index.html (registration/index.html, clinical/index.html).

Nepali calendar implementation example is [here](https://github.com/padamdahal/custom-calendar-for-bahmni/blob/master/example-registration-index.html).
