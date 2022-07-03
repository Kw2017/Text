# Text

![](https://raw.githubusercontent.com/Kw2017/Text/main/chart.png)

Increases in the batch size from 2 to 64 when testing with 10 epochs resulted in diminishing reductions in training time,
while increasing the batch size to an amount greater than 64 had an inconclsuive impact on the training time.

| Batch Size | Time 1 | Time 2 | Time 3 | Average Time |
|------------|--------|--------|--------|--------------|
|2           |5:49    |5:44    |5:54    |5:49          |
|4           |4:30    |4:21    |4:14    |4:22          |
|8           |3:11    |3:11    |3:11    |3:11          |
|16          |2:51    |2:50    |2:50    |2:51          |
|32          |2:38    |2:38    |2:38    |2:38          |
|64          |2:33    |2:31    |2:31    |2:32          |
|128         |2:33    |2:39    |2:39    |2:36          |
|256         |2:24    |2:28    |2:28    |2:26          |
|512         |2:29    |2:32    |2:32    |2:30          |
|1024        |2:31    |2:31    |2:31    |2:31          |
