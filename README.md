In this project, we're working with an ODI dataset that includes details of different teams and players. Our focus is on analyzing how batsmen perform, especially looking into how they get out, how many runs they score, and against which bowlers.

What we're doing:
Start by creating smaller, cleaner dataframes (you can think of them as mini-tables) from the main dataset. This helps us work on specific parts of the data more easily.

For example, we'll take the "Out Type" column and convert the text (like "bowled", "caught", etc.) into numbers so it's easier to process:

Bowled → 1

LBW → 2

Caught → 3

Run Out → 4

Stumped → 5

Then we filter out just Pakistan's matches from the dataset so we can look specifically at Pakistani batsmen.

Once we have that, we clean up the data a bit — like removing the "batting team" column (because we already know it’s Pakistan) and dropping extra info like the non-striker’s name.

We then focus only on the most important details: match ID, ball number, bowling team, bowler name, runs scored, and how the batsman got out.

🧠  Shahid Afridi’s Performance
To make this even more interesting, we pick a specific player — Shahid Afridi — and study his performance:

Total matches played

Total runs in ODIs

Highest runs in a match

Average runs in ODIs

Matches where he got out on 0

Dismissal Stats (How he got out)

This setup makes it easier to zoom in on any batsman and get detailed stats, whether you're a cricket fan or working on a sports data project!
