# Arsenal-2-1-Chelsea-Data-Driven-Match-Analysis

## Overview

I built a multi-stage football analytics workflow to analyse Arsenal's 2–1 victory over Chelsea in Matchday 3 of the 2026/27 English Premier League season.

The analysis combined player-level event data, role-based performance dimensions, calibrated player ratings and match-level tactical statistics to move beyond the final score and understand how the game was actually won.

The workflow followed:

**Build → Analyse → Explain → Visualise → Publish**

## The Match in Numbers

| Metric                    | Arsenal | Chelsea | Advantage |
| ------------------------- | ------: | ------: | --------- |
| Goals                     |       2 |       1 | Arsenal   |
| xG                        |    2.87 |    0.43 | Arsenal   |
| Shots                     |      16 |      13 | Arsenal   |
| Chances created           |      14 |      10 | Arsenal   |
| Defensive actions         |      17 |      21 | Chelsea   |
| Recoveries                |      35 |      45 | Chelsea   |
| Duels won                 |      35 |      50 | Chelsea   |
| Average calibrated rating |   58.10 |   54.76 | Arsenal   |

The most significant statistical difference was expected-goal production.

Arsenal generated **2.87 xG**, compared with just **0.43 xG** for Chelsea — a difference of **2.44 xG**.

## Arsenal's Attacking Advantage

Arsenal produced more shots and created more chances, but the biggest distinction was the quality of the opportunities generated.

The 16–13 shot advantage was relatively modest.

The **2.87–0.43 xG advantage** was not.

This indicates that Arsenal's attacking structure produced considerably more dangerous scoring opportunities.

## Chelsea's Defensive Competitiveness

Chelsea's numbers reveal a different story.

They recorded:

* 21 defensive actions
* 45 recoveries
* 50 duels won

Arsenal recorded 17 defensive actions, 35 recoveries and 35 duels won.

Chelsea therefore demonstrated considerable defensive activity and physical competitiveness.

However, that defensive activity did not translate into an equivalent attacking threat.

## Individual Performance

The player-rating model produced an interesting result.

Chelsea's Ezri Konsa was the highest-rated player in the match at **83.51**, followed by Wesley Fofana at **82.02**.

Arsenal's highest-rated player was Martin Ødegaard at **80.53**.

The top five were:

1. Ezri Konsa — 83.51
2. Wesley Fofana — 82.02
3. Martin Ødegaard — 80.53
4. Kai Havertz — 71.77
5. David Raya — 69.36

This demonstrates an important analytical principle:

**The highest-rated individual player does not necessarily belong to the winning team.**

## Team-Level Rating Profile

Although Chelsea produced the two highest individual ratings, Arsenal had the stronger aggregate calibrated profile.

**Arsenal: 58.10**

**Chelsea: 54.76**

The resulting +3.34 rating advantage for Arsenal provides another layer of evidence, but it should not be interpreted independently from the match statistics.

The rating model is designed to complement — rather than replace — the underlying tactical and statistical evidence.

## The Finishing Paradox

One of the most interesting findings came from finishing relative to expected goals.

Arsenal:

**2 goals − 2.87 xG = -0.87**

Chelsea:

**1 goal − 0.43 xG = +0.57**

Chelsea therefore finished above their expected output, while Arsenal finished below theirs.

Yet Arsenal won.

This highlights why finishing efficiency alone cannot explain a match.

Arsenal created a substantially larger underlying scoring opportunity profile, giving them a much stronger platform from which to win the game.

## Tactical Interpretation

The combined evidence suggests a clear contrast.

**Arsenal won the attacking battle.**

They produced more shots, created more chances and generated dramatically more xG.

**Chelsea won much of the defensive battle.**

They recorded more defensive actions, recoveries and duels won.

**The decisive difference was attacking threat.**

Chelsea's defensive competitiveness and strong individual performances kept them in the game, but Arsenal's superior chance creation and opportunity quality ultimately provided the foundation for the 2–1 victory.

## Methodological Note

The player-rating component is match-specific.

It should not be interpreted as a definitive measure of long-term player ability.

The rating system incorporates role-based dimensions and calibration intended to reduce the influence of normalization and sample-size effects. Players with fewer than 60 minutes were excluded from the official rating leaderboard.

The strongest conclusions therefore come from combining the calibrated player ratings with the underlying match statistics.

## Conclusion

Arsenal's 2–1 victory was not simply a story of finishing or individual brilliance.

It was a story of **attacking opportunity creation**.

Chelsea produced stronger defensive numbers and the two highest individual player ratings, but Arsenal generated the substantially greater attacking threat.

The key lesson from the match is therefore:

> **Individual performance can explain who stood out. Team-level data explains why the match was won.**

This analysis demonstrates how football analytics can connect player-level performance, team statistics and tactical storytelling into one coherent match narrative.
