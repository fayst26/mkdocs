# Dates and times
Expressing dates and times in a clear and unambiguous way helps support [writing for a global audience](https://developers.google.com/style/translation) and reduces confusion.
## Express times

In general, use the following guidelines to format expressions of time:

* Use the 12-hour clock, except if required to use a 24-hour time, such as when documenting features that use 24-hour time. If the UI, a command, or a code sample uses the 24-hour format, use that format throughout the page for consistency.
* Use exact times when possible, but noon and midnight are OK.
* Use hyphens in time ranges. Don't add spaces before or after the hyphens.

  &nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: 5-10 minutes ago.

* Capitalize AM and PM, and leave one space between it and the time.

  &nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: 3:45 PM.

* Remove the minutes from round hours.

  &nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: 3 PM.


## Express time zones
Avoid using time zones unless absolutely necessary. In cases where you need to use a time zone—such as describing real events at real times—use the following guidelines:

* Let the reader know if the time is local to their time—for example, 10 AM your local time.
* If a time zone is necessary, use the timestamp format as seen in the user interface (if available).
* If using a specific time zone, spell out the region and include the UTC or GMT label as a parenthetical. For example:
  * US and Canadian Pacific Standard Time (UTC-8)
  * US and Canadian Pacific Daylight Time (UTC-7)
* Don't abbreviate the name of the time zone.
* In the rare event where the time of an event doesn't change for daylight saving time, use the specific time zone, without reference to UTC.

## Express dates
In general, spell out the names of months and days of the week in full. Give the full four-digit year, not a two-digit abbreviation.

&nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: January 19, 2017

If including the day of the week, add it before the month as follows: *DAY_OF_WEEK*, *MONTH* *DAY*, *YEAR*.

&nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: Tuesday, April 27, 2021

## Partial dates and abbreviations
When giving only the month and year, don't use a comma.

&nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: She was hired in January 2017.

In most cases, don't abbreviate the day of the week or the month. However, when conserving space, such as in a heading or table, it's okay to abbreviate the month and the day of the week to their three-letter abbreviations. Capitalize the first letter and do not add a period at the end of the abbreviation.

If you abbreviate, do so for the entire date. Don't mix written-out forms with abbreviated forms in the same date.


Be consistent in where you apply abbreviations throughout your documentation. For example, if you choose to abbreviate in table cells, do so in all table cells.

&nbsp;&nbsp;&nbsp;&nbsp;**Recommended**: Mon, Sep 3, 2018

&nbsp;&nbsp;&nbsp;&nbsp;**Not recommended**: Mon, September 3, 2018

## Express divisions of the year
Avoid referring to seasons. Spring in the northern hemisphere is fall (autumn) in the southern hemisphere. Instead, use the month, quarter, or temperature (if relevant).

| Recommended | Not recommended |
| ----------- | ----------- |
| During warmer months, data centers face a higher risk of cooling failures. | During summer months, data centers face a higher risk of cooling failures. |
| In November and December, data centers experience higher traffic volume. | In winter, data centers experience higher traffic volume. |
| Changes are released in October of each year. | Changes are released in the Fall of each year. |
	
	
	