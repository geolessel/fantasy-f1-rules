# Lessel Fantasy Formula 1 Rules

This is an attempt to clarify all the various rules and edge cases that may
arise from our custom-made fantasy Formula 1 league. These rules have slightly
morphed over the years but have remained relatively the same as they were in
2010.

These rules have worked amazingly well for a league size of three people. Most
things would most likely need to be adjusted in a larger league size.

---

## Teams Teams are made up of five drivers. Each driver may only be on one
team. Once a driver is acquired by a team, they are that team's and may only
be acquired by a different team through a [trade](#trades) or, if released by
the owning team, through a [free agent](#team-roster-changes) acquisition.

---

## Driver Draft Teams are set at the beginning of the season through an
auction-style driver draft. Each team begins the draft with 100 points. The
minimum bid for a driver is seven points. The order the drivers are up for
auction has changed over the years but the current preferred method is the
[Random Driver](#random-driver-method) method. Another method used in the past
is the [Random Elector](#random-elector-method) method.

#### Random Driver Method

* All drivers are put into a pool.
* One driver at a time is selected randomly from that pool is available for
  bidding.

#### Random Elector Method

* All teams are put into a pool.
* One team at a time is selected randomly from that pool and is responsible
  for choosing the next driver up for auction.

### Bidding

Once it has been decided which driver is being auctioned, bidding for that
driver takes place.

* Bidding order can either be determined in two ways:
  1. as a specific predetermined order where each team in turn has the option
     to bid or explicitly pass
  1. as a regular auction in which bidding is open
     and is completed after a reasonable amount of time passes after the last
     bid
* If every team passes its bid (no team makes a bid), the driver goes back
  into the pool and is available for future draws.
* Once a driver has received a bid from one team and all other teams have
  passed, that driver now belongs to the high-bidding team and their draft
  points balance is reduced by their bid amount.

It is possible for a team to get itself into a situation in which it cannot
meet the minimum bid for a driver (seven points). That situation hasn't yet
arisen and hopefully will not ever. Keep yourself in check. Don't be that guy.

Any leftover points are placed into a starting pool of points available for
[team roster changes](#team-roster-changes). These points **do not** count as
team league points and can only be used for roster changes.

---

## Scoring Scoring is determined on a per race basis. A race's score is the
sum of the following calculations.

#### Movement points
= Starting grid position – finishing position

> **Examples**
>
> Hamilton starts from pole position (P1) and finished in 8th (P8). His score
> for this category would be `1–8 = -7`.
>
> Vettel _qualified_ in P4 but suffered a penalty between qualifying and race
> start. He _starts_ last from pit lane with a 22-driver lineup (P22). He
> finishes in 6th place. His score for this category would be `22-6 = 16`.

#### Lap points
= number of laps completed at the end of the race

> **Example**
>
> In the [2010 Australian Grand
> Prix](http://en.wikipedia.org/wiki/2010_Australian_Grand_Prix), the race
> length was 58 laps. Heikki Kovalainen completed 56 laps by race end. His
> score for this category would be `56`.

#### Championship points
= 2x the earned championship points for the driver's finishing position

*Note: through penalties, it is possible that a driver crosses the finish line
in one position and is officially qualified in another. The official
qualification is the one that counts.*

> **Example**
>
> Massa finished 3rd in the race earning him 15 championship points. His score
> for this category would be `30`.

---

## Bets In order to add some extra points-earning opportunities and excitement
to each race, proposition bets are available per race. Each team can bet a
portion of their points pool on three bets. These points can be split up
however the team likes but cannot exceed, per race, 50 points in total or
their maximum amount of points, whichever is less.

#### Driver on pole position
* Bet on which driver will start the race on pole position
* **Note that through penalties, this can be a different driver than the one
  that _qualified_ on pole position**
* Pays 2:1 (a successful 50-point bet would yield 100 net points)
* Bets are closed at the start of race qualifying

#### Winning driver
* Bet on which driver will finish the race at P1
* **Note that through penalties, this can be a different driver than the one
  that crossed the finish line in P1**
* Pays 2:1 (a successful 50-point bet would yield 100 net points)
* Bets are closed at race start

#### Driver with most positions gained
* Bet on which driver will gain the most positions during a race
* **Because of penalties on both race start and end, this needs clarification:
  this is based on which position the driver _starts_ the race, not where he
  _qualified_. Also his official qualification in the race standings by the
  race stewards is what is taken into account and _not_ in which position he
  crosses the finish line.**
* Pays 4:1 (a successful 50-point bet would yield 200 net points)
* Bets are closed at race start

---

## Team Roster Changes At any point during the season, a team may make changes
to their driver roster. Each driver is valued at a [calculated
amount](#driver-value-calculation) of points based on their current Driver's
Championship standings. A team may use any leftover draft points plus trade
(at a [predetermined ratio](#points-trade-ratio)) any necessary amount of
league points in order to complete a transaction.

**Note that buying and selling must occur in tandem. At no time is a team
allowed to have more or less drivers than five.**

All trades must be completed before the start of a race's first qualifying
session. From then, no roster changes can be made until after the weekend's
race has been completed. This means that if a driver is removed from a race
between qualifying start and race completion, the owning team is out of luck
and that driver scores no points for the team.

#### Driver value calculation A drivers value is calculated as the total
number of drivers who are listed in the official Driver's Championship
standings minus that drivers current standing in the Driver's Championship.
This means it is a moving value and can change race by race and higher ranked
drivers are valued higher.

> **Example**
>
> Twenty (20) Drivers are listed in the Driver's Championship standings.
> Alonso is currently ranked 4th in the standings. His value is `20-4 = 16`.

#### Points trade ratio If a driver does not have enough points between their
leftover draft points pool and selling their one driver to cover the cost of
adding the new driver, the team may trade league points to trade points at a
1:4 ratio.

> **Example**
>
> Team B had 2 points leftover from the initial driver draft. They would like
> to drop Driver 1 with a value of 2 and replace him with Driver 2 with a
> value of 16. Driver 1's value of 2 would bring the transaction amount
> balance to 14. Team B would use their 2 leftover draft points to bring the
> transaction balance to 12. They would then need to use `12*4 = 48` league
> points to bring the transaction balance to 0 and complete the transaction.
> They would then have 0 leftover draft points.

#### Leftover points after a transaction Any positive points remaining after a
transaction goes into the Team's pool and is available for any future
transactions. These points **do not ever** translate into league points.

> **Example**
>
> Team C has 0 points available for roster changes. They would like to drop
> Driver 1 with a value of 4 and replace him with Driver 2 with a value of 1.
> The transaction balance would be `1-4 = -3`. After the transaction
> completes, Team C would have 3 points available for future roster changes.

---

## Edge Cases

### A driver drops out of a race If a driver does not race for any reason, it
is up to the owning team to make the decision to keep or drop them from their
roster. All deadlines are still in effect. If you're not paying attention
between races, this can bite you.

### Queueing up races vs. deadlines This is borne from our particular issue in
which there are times in which we record races and watch multiple back to
back. Even though we try to avoid learning about races that we have not
watched but have already passed, deadlines that apply to those and future
races still apply. **In other words, just because we have not seen a race does
not mean any deadlines specified above do not apply – they do!**

Yes, this means one of your drivers can be injured and miss two subsequent
races without you knowing it. You get no points for those missed races. Sorry.

---

## Ideas For the Future

### Trades While trades are permitted in the league, they are rare. Any two
teams may make a driver trade (and include points) under their own terms as
long as after the trade is complete both teams still have a positive points
total and a 5-driver roster. This can be creative.
