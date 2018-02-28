﻿# Date.IsInPreviousQuarter
Indicates whether this date occurs during the previous quarter, as determined by the current date and time on the system.
***
function (optional dateTime as nullable any) as nullable any
***
# Descrition 
Indicates whether the given datetime value <code>dateTime</code> occurs during the previous quarter, as determined by the current date and time on the system.
      <ul>
      <li><code>dateTime</code>: A <code>date</code>, <code>datetime</code>, or <code>datetimezone</code> value to be evaluated.</li>
      </ul>
# Category 
Date
# Examples 
Determine if the quarter before the current system time is in the previous quarter.
```
Date.IsInPreviousQuarter(Date.AddQuarters(DateTime.FixedLocalNow(), -1))
```
> true
***