# PR Response Doc — CineLog Watchlist Feature

## AI Usage
<!-- Fill in at the end — how you used AI tools during this project -->

## Comment 1 — Rename
**What I did:** rename from save_to_watchlist to add_to_watchlist
**How I verified:** I ensured it is changed in all other references

## Comment 2 — Deduplication
**What I did:** added logic that raises and aror if the fil is already in the watch list to prevent duplicates
**How I verified:** i ran pytest tests/ -v and it passed

## Comment 3 — Missing test
**What I did:** I added a unit test for the code cahnges i made
**How I verified:** I ran pytest tests/ -v and it all passed

## Comment 4 — Default visibility
**My position:** I want to leave it as true
**Reasoning:** In asmuch as i belive in privacy for my users, CineLog is a community platform. making the watchlist collection public will let other community users view each other list and it can spur up conversations and even foster the core idea of the platform which is to connect people with the power of films
**Tradeoff acknowledged:** Privacy risk and also you won't be able to avoid spoilers

## Comment 5 — Sort order
**My position:** I agree with your stance
**Reasoning:** It makes sense to view a collection in the order by which they were added. 
**Engagement with reviewer's point:** Yeah i agree with you on this. I belive it is more intuitive to have the collection designed that way.

## Comment 6 — Rebase
**What conflicted:** the gitignore fle
**How I resolved it:** i accepted the incoming changes
**How I verified no conflict remains:** ran git status and it was clear

## PR Description
<!-- Written at the end — feature overview, design decisions, manual testing steps -->