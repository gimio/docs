## leaderboard

leader board store users scores and show best result.  

developer can define below items to a leaderboard:

- a key for access to leaderboard
- format type [more](#format-types)
- can set lower score is better
- min and max value of score
- is summable [more](#is-summable)

## format types

- number base
- time base

## is summable

with this option new score will be sum with old score

## output type

`daily`, `week`, `month`, `overall`

# score item

every score item, have a relation to a user and a leaderboard.  
we have this items:

- score value
- create time
- update time