# Data Dictionary

For this project, I'm using my own sleep records, university timetable, exam dates and Screen Time data.

Since all of this information comes from different places, I thought it would be easier to list the variables first before combining everything and starting the analysis in Python.

| Variable | Description | Unit |
|---|---|---|
| date | Date of my sleep record | YYYY-MM-DD |
| sleep_start | Time I went to sleep | HH:MM |
| wake_time | Time I woke up | HH:MM |
| sleep_duration | Time between going to sleep and waking up | Minutes |
| weekday | Day of the week | Monday–Sunday |
| first_class_time | When my first class starts that day | HH:MM |
| exam_next_day | If I have an exam the following day | 0 or 1 |
| days_to_exam | How many days until my next exam | Days |
| screen_time | Total time spent on my phone that day, if available | Minutes |
| tiktok_usage | Time spent on TikTok that day, if available | Minutes |

## Notes About My Data

I chose September 28, 2026 as my starting date because that's when the fall semester started and I got back into my university routine.

I have been using my iPhone to track when I go to sleep and when I wake up.I usually update it right before I go to bed and when I wake up so the times should be pretty close to when I actually sleep.

In going over my sleep records I saw that I had multiple entries for a date.Rather than count them twice I decided to use the last entry shown for those dates.

There are also some days where I forgot to record my sleep. I don't want to make up any values for those days,so I'll just leave them as missing in my dataset.

The Screen Time data is a little different. Right now, most of what I have is weekly summaries, while my sleep records are daily. I'm not sure yet how much of it I'll be able to use,so I'll look that once I start working with everything in Python.
