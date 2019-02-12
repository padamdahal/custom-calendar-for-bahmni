# custom-calendar-for-bahmni
This script helps to add custom calendar for [Bahmni](https://www.bahmni.org "Bahmni Home"). This is an example of using Nepali calendar with the jquery calendar plugin available [here](https://www.npmjs.com/package/nepali-date-picker).

## Usage
Include scripts and style for nepali date picker mentioned above, and customCalendar.js (after existing scripts) in bahmni apps index.html (registration/index.html, clinical/index.html)

### Typical nepali calendar implementation
**<link rel="stylesheet" href="../components/nepaliDatePicker.min.922e4e85.css"/>**
**<style>.nepali-date-picker{z-index:9999999;}</style> **
......
......
<script src="../components/angular-elastic/elastic.5f4647d6.js"></script>
**<script src="../components/jquery.nepaliDatePicker.min.b4803b8f.js"></script>**
<script src="../components/react/react.min.6edad0b0.js"></script>
........
........
<script src="./clinical.min.web.3c956368.js"></script>
**<script src="../components/customCalendar.js"></script>**
.......
.......
