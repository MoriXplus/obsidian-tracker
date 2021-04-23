# Test Date Formats

Change the default dateFomat on Tracker settings panel and then check these trackers in the preview mode. Only the one fit dateFomat settings will get rendered.

## dateFomat: YYYY-MM-DD

``` tracker
searchType: tag
searchTarget: weight
folder: diary
startDate: 2021-01-01
endDate: 2021-01-05
line:
    title: Weight Log
    yAxisLabel: Weight
    yAxisUnit: kg
    lineColor: yellow
```

## dateFormat: D-YYYYMMDD

``` tracker
searchType: tag
searchTarget: weight
folder: diary
startDate: 1-20210101
endDate: 5-20210105
line:
    title: Weight Log
    yAxisLabel: Weight
    yAxisUnit: kg
    lineColor: yellow
```

## dateFormat: YYYY-MM-DD-dddd

``` tracker
searchType: tag
searchTarget: weight
folder: diary
startDate: 2021-01-01-Friday
endDate: 2021-01-05-Tuesday
line:
    title: Weight Log
    yAxisLabel: Weight
    yAxisUnit: kg
    lineColor: yellow
```
