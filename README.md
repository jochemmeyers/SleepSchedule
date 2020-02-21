# SleepSchedule
## About
SleepSchedule lets you plan a non-24h [monophasic sleep cycle](https://en.wikipedia.org/wiki/Biphasic_and_polyphasic_sleep), without having to figure out manually when you'll be awake and asleep. This tool is partially inspired by the XKCD comic [28-hour day](https://xkcd.com/320/).

Some people have circadian rythms that don't match up with the 24 hour cycle. Others might want to experiment with shorter or longer days.

## Usage
Set the day you want to begin your cycle experiment, then simply drag the sliders around to set your day length, sleep length, and start time on day 1.

If you have unmovable events, or recurring events, you can add them with the Add Event button at the bottom.

Event recursion is pretty basic: Either daily (Every X days), or monthly (Every month on the same day). 

If you want to put in workdays, simply add the appropriate number of events set to recur every 7 days (so one for Mondays, one for Tuesdays...).

## Saving / loading your schedule
The settings and contents of your schedule are compressed and stored in the Save/load string at the top right of the page.

To save, simply copy the Save/load string, and store it somewhere safe like a text document on your PC. If you make any changes, make sure to copy and replace the save string.

To load your saved schedule and settings, copy the Save/load string from your text document, and paste it in the Save/load string field.

You can also share the Save/load string with others if you want.

## Privacy
No data you enter is ever transmitted over the internet, unless you do so yourself. It isn't even stored in your browser past closing or refreshing the page.

Note that the save string is compressed, not encrypted. It can be decrompressed by anyone that has it.
