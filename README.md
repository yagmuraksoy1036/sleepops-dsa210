# SleepOps

### Exploring the Association Between Sleep, University Timetable and Screen Time

## Project Background

I've been tracking my sleep on my iPhone for years, but I never really thought of analyzing it until this semester.

As an Industrial Engineering student at Sabancı University,my weekly schedule isn't consistent. On Wednesdays, for example, I have a class at 8:40 AM, but on other days I don't need to be up nearly as early. Things get even less predictable around midterms, when I sometimes have several exams within the same week.

I started wondering whether these changes actually make a difference in my sleep patterns. I already had years of sleep records, so instead of collecting an entirely new dataset, I wanted to see what I could learn from the information I'd been recording all along.

I am looking at my sleep data in relation to my university timetable, exam dates and phone usage for my DSA210 project. I'm also interested in seeing if my sleep patterns change with my school responsibilities or if they are pretty much the same no matter what my schedule is.

## Research Questions

There are a few things I want to figure out:

1. **Early classes:** Do I actually go to bed earlier when I have an early class the next morning, or do I just end up sleeping less?
2. **Exam periods:** Is there a noticeable difference in my bedtime or sleep duration in the days leading up to an exam?
3. **Screen time:** Are the days when I spend more time on my phone also the days when I go to sleep later?

I'm also interested in trying a simple prediction model to see how much of my sleep timing can be explained by my academic schedule.

These are patterns I'm hoping to investigate, rather than assumptions I'm trying to prove.

## The Data

I'm working with four sources of information:

- **Sleep records:** I've been recording when I go to sleep and when I wake up through my iPhone's sleep settings. I update these manually, so the times are based on my own records rather than measurements from a smartwatch.
- **University timetable:** My weekly class schedule, including the starting times of my classes.
- **Exam calendar:** The dates of my midterms and finals, which I'll use to identify exam-related periods.
- **Screen Time:** My iPhone usage statistics, including apps like TikTok and Instagram.Most of the information I currently have is in weekly summaries, so I need to look more into it when comparing it with daily sleep records.

For the main analysis, I start with September 28, 2026, when the fall semester started. I also have older sleep records, including times when I was working full-time during the summer, which I might look at separately if they add something useful to the analysis.

## My Approach

The first problem is getting the data into a format that I can actually use. I was looking at my sleep history and noticed missing dates and some days with more than one entry. For now, I’ve opted to use the most recent entry listed for each date, and keep a list of the duplications so I can look them up if I need to.

Once I get my dataset organized, I want to begin with an exploratory data analysis to get a better picture of my sleeping habits through the semester. I’ll look at variation across weekdays, compare nites before early classes to other nights, and look at what happens around exams.

After that, I'll use statistical tests to check whether the differences I observe are meaningful.If I have enough usable data, I'd also like to try a few basic prediction methods and compare them against a simple baseline.

Since this is personal, observational data, I won't be able to say that an exam or an app directly caused a change in my sleep. The goal is to understand the patterns in my own records and see how much information they actually contain.

## Current Progress

I've collected my initial sleep records, class timetable,exam dates, and the Screen Time summaries available on my phone.

I'm working now to get all of this into one dataset, looking for duplicates and making sure the dates are consistent from place to place.

The next step is to finish cleaning the data and start exploring it in Python.I'll add the analysis, figures, and findings to this repository as I work through the project.
