# JavaScript and DOM Manipulation

## Background

Create a table dynamically based upon a [provided dataset](static/readme/data.js).
Users need the ability to filter the table data for specific values.

## Requirements

### Automatic Table and Date Search (Required)

* The basic website template has already been created.
* Use the dataset provided in the form of an array of JavaScript objects. Write code that appends a table to the web page and add new rows of data as needed.
  * Make sure that there is a column for `date/time`, `city`, `state`, `country`, `shape`, and `comment` at the very least.
* Use a date form in your HTML document and write JavaScript code that will listen for events and search through the `date/time` column to find rows that match user input.

### Considerations

* Only pure JavaScript, HTML, CSS, and D3.js can be used.
* Using multiple `input` tags and/or select dropdowns, write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns instead of just the date:

  1. `date/time`
  2. `city`
  3. `state`
  4. `country`
  5. `shape`

### Screenshot

![Screenshot - large screen](static/readme/screenshot.png)