Features-
Takes prompt for number of subjects and their names.

Supports a weekly timetable from Monday to Sunday.

Monday and Friday have three class slots.

Tuesday, Wednesday, Thursday, and Saturday have two class slots plus a self-study session.

Sunday is marked as a holiday with a revision note.

Self-study is always included at least once daily (except Sunday).

The timetable cycles through subjects in order, filling in classes for the week.

How it works-

The script asks how many subjects you have and collects their names.

It defines the days of the week and time slots for classes and self-study.

It automatically assigns subjects to slots across the week.

Sunday is reserved as a holiday for revision/self-study.

Finally, it prints the generated timetable in a clear format.


=== Timetable Generator ===
How many subjects do you have ? 4
Enter subject #1 name: Math
Enter subject #2 name: English
Enter subject #3 name: EEE
Enter subject #4 name: CS

===== WEEKLY TIMETABLE =====

Mon:
  8:30AM - Math
  1:15PM - English
  2:50PM - EEE
  4PM - Self Study

Tue:
  8:30AM - CS
  1:15PM - Math
  Self Study - Self Study

(output continues for each day)
