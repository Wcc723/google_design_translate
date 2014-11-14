# Data formats

## Date & time

This guide explains how to display date and time information in a consistent and user-friendly way.

These guidelines apply to:

- the current date and time
- a date and time setting, such as an alarm or reminder
- a date and time when an object was created, sent, edited, or otherwise acted upon


### Basic displays

For time, use uppercase AM or PM without periods, separated from time with a space.

10:00 AM

<br><br>

If a timestamp is within the current day,  it’s generally unnecessary to show either “today”, the day or date. Only display the time in “hour:minute AM/PM” format.

11:51 AM

<br><br>

If the day is in the past or future within the current calendar year, display the abbreviated date.

Jul 14

<br><br>

If the day is in the past or future outside of the current calendar year, display the abbreviated date and year.

Jul 14, 2012

<br><br>

If the date is a range of time, separate with an en-dash without a space on either side.

8:00 AM–12:30 PM

Jan 6–Feb 2

<br><br>

If both dates in a range start and end in the current year, omit the year. Otherwise, show the year on both the start and end.

Dec 6, 2013–Jan 2, 2014

<br><br>

When a range shares a common AM/PM, append only on the end of the range.

8:00–10:30 AM

<br><br>

When listing the time zone, drop the leading 0 for single digits.

UTC+5:00

<br><br>


### Using human and relative language and approximate time

When space permits, display the relevant date/time information in the context of the current date/time, as people normally speak to each other.

If the day is yesterday or tomorrow, use those terms.

Yesterday, Tomorrow

<br><br>

If the day is in the future and within a week, display the unabbreviated day of the week.

Tuesday

<br><br>

If a word alternative helps understanding or describes a time-of-day preset, display that alternative.

Store open 9:00 AM–Midnight

Reminder for tomorrow afternoon

<br><br>

If absolute time isn’t necessary for specificity or comparison, you may choose to display approximate relative times.

Don’t combine units (e.g. “1 hour 32 minutes ago”), rather round down to most recent largest unit (e.g. “1 hour ago”).

In 5 minutes

8 hours from now

3 days ago

<br><br>

Relative language may not always be appropriate, e.g. current date in a clock app, or the specific time of an event or alarm. In these cases, use absolute time.

Mon, Jan 10

Today, 10:00 AM

<br><br>

### Be modular

Depending on the context, show either date or time, or both date and time.

Typically, future settings should append time to a day or date.

Jan 10, 8:00 AM

<br><br>

When a past time is necessary, such as a triggered reminder, display both date and time.

Reminded Jan 5, 7:16 AM

<br><br>

When the day of week is necessary, such as on a calendar invite, display the abbreviated day separated by a comma.

Mon, Jan 10, 8:00 AM

<br><br>

When it’s an event in the distant past, omit the time.

Jan 3

<br><br>

Use HH:MM:SS to show the duration of a recording, like audio or video. If hours or seconds don’t apply, then omit them.

0:30

2:14

1:01:05

<br><br>

### Be brief

Always abbreviate months, with single or double digit dates.

Jan 6, Feb 7, Mar 8, Apr 9,

May 10, Jun 11, Jul 12, Aug 13,

Sep 14, Oct 15, Nov 16, Dec 17

<br><br>

Abbreviate days of the week when combined with a time.

Mon, 8:00 AM

Tue, 9:00 AM

Wed, 10:00 AM

Thu, 11:00 AM

Fri, 12:00 PM

Sat, 1:00 PM

Sun, 2:00 PM

<br><br>

If real estate is limited (such as with timestamps, labels on graphs, durations, etc.) abbreviate units, using numerical versions and/or by removing the “:00”:

8 AM

2 hr 32 min ago

3/12/12

<br><br>


If truncation of “tomorrow” or “yesterday” happens repeatedly, do not abbreviate. Instead, use the month date format.

Jun 6


