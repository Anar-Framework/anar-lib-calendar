### Calender Utility Library 

In this util library , we provide the calendar utilities for ANAR Framework implementations.

### Features

- Get Ceiling : Gets a date ceiling, leaving the field specified as the most significant field.
- Get Fragment In Day: Returns the number of days within the fragment. All datefields greater than the fragment will be ignored.
- Get Fragment In Hour: Returns the number of hours within the fragment. All datefields greater than the fragment will be ignored.
- Get Fragment In Millisecond: Returns the number of milliseconds within the fragment. All datefields greater than the fragment will be ignored.
- Get Fragment In Minutes: Returns the number of minutes within the fragment. All datefields greater than the fragment will be ignored.
- Get Fragment In Seconds: Returns the number of seconds within the fragment. All datefields greater than the fragment will be ignored.
- In Same Day: Checks if two calendar objects are on the same day ignoring time.
- Is Same Instant: Checks if two calendar objects represent the same instant in time. This method compares the long millisecond time of the two objects.
- Is Same Local Time :Checks if two calendar objects represent the same local time. This method compares the values of the fields of the two objects. In addition, both calendars must be the same of the same type.
- get Round : Rounds a date, leaving the field specified as the most significant field.
- to Calender: Converts a Date of a given TimeZone into a Calendar.
- Truncate : Truncates a date, leaving the field specified as the most significant field.
- Truncate Equals: Determines if two calendars are equal up to no more than the specified most significant field.
