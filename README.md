# A collection of useful Python scripts
## Humanize Time
A function that makes time intervals more human-readable
*Usage*
```
>>> humanize_time(173, 'hours')
[(1, 'week'), (5, 'hours')]
>>> humanize_time(17313, 'seconds')
[(4, 'hours'), (48, 'minutes'), (33, 'seconds')]
>>> humanize_time(90, 'weeks')
[(1, 'year'), (10, 'months'), (2, 'weeks')]
>>> humanize_time(42, 'months')
[(3, 'years'), (6, 'months')]
>>> humanize_time(500, 'days')
[(1, 'year'), (5, 'months'), (3, 'weeks'), (3, 'days')]
```