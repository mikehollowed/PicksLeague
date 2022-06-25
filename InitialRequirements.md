# Requirements
The requirements for the PicksLeague application assume that picks are made only on who wins matchups without point spread considerations or confidence points. This is a simple application that tracks a user's winning accuracy picking winners of matchups of a given sports league season or tournament and not meant to have gambling or confidence considerations. This may be updated in a future release.

## Database


## UX
1. Users must be able to make picks on matches at least one week in advance of the scheduled match.
2. Users must be able to change their picks on a given matchup as often as they'd before the commencement of said matchup.
3. Users must be able to see their current rankings (as of the most recently completed day of matchups) relative to other users in their league.
4. Rankings must be updated at the end of a each day. Rankings may be updated as soon as matchups have been ruled final.
5. Matchup scores may be updated live at some regular interval (hourly or sooner) if data is available.

## Scoring
1. Ties are ruled as losses (winning percentage is how often a user picks *the winning team*).
