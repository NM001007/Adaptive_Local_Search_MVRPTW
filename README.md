# ALS_MVRPTW
The python implementation for the paper "An adaptive large neighborhood search for the multi-depot dynamic vehicle routing problem with time windows" [[1]](#1)


# Results on Real-World Datasets
## Cordeau 
The following demonstrates the results obtained by applying the implemented algorithm on the cordeau-2001 dataset.
| Instance | Total Distance | Number of Vehicles | Computation Time |
|----------|----------------|--------------------|------------------|
| pr01     | 7.60           | 19                 | 1190.83          |
| pr02     | 19.11          | 42                 | 2228.56          |
| pr03     | 31.32          | 62                 | 2959.75          |
| pr04     | 37.93          | 95                 | 3269.61          |
| pr05     | 44.37          | 114                | 2221.50          |
| pr06     | 51.04          | 137                | 6154.87          |
| pr07     | 15.39          | 31                 | 3152.89          |
| pr08     | 26.17          | 59                 | 1911.45          |
| pr09     | 43.54          | 98                 | 6002.02          |
| pr10     | 57.09          | 142                | 6604.08          |
| pr11     | 8.55           | 14                 | 2865.59          |
| pr12     | 19.63          | 41                 | 2877.52          |
| pr13     | 31.44          | 62                 | 1762.72          |
| pr14     | 39.17          | 90                 | 3388.81          |
| pr15     | 46.83          | 119                | 5617.36          |
| pr16     | 50.99          | 133                | 6071.86          |
| pr17     | 15.02          | 30                 | 4227.66          |
| pr18     | 27.14          | 66                 | 4990.00          |
| pr19     | 42.66          | 96                 | 2518.38          |
| pr20     | 54.43          | 135                | 2471.23          |
| AVERAGE  | 33.47          | 79.25              | 3624.33          |


## Vidal
The table below illustrates the total distance, number of vehicles, and computation on both groups (a and b) of Vidal 2013 datasets.
| Instance (a) | Total Distance | Number of Vehicles | Computation Time | Instance (b) | Total Distance | Number of Vehicles | Computation Time |
|--------------|----------------|--------------------|------------------|--------------|----------------|--------------------|------------------|
| pr11a        | 132.69         | 163                | 2443.19          | pr11b        | 125.35         | 167                | 2734.19          |
| pr12a        | 183.03         | 230                | 7256.64          | pr12b        | 155.77         | 222                | 7439.75          |
| pr13a        | 218.40         | 279                | 7709.00          | pr13b        | 195.36         | 269                | 5786.86          |
| pr14a        | 263.71         | 343                | 8083.16          | pr14b        | 249.69         | 339                | 3709.62          |
| pr15a        | 294.95         | 393                | 8480.17          | pr15b        | 291.80         | 406                | 5682.55          |
| pr16a        | 330.15         | 442                | 4339.50          | pr16b        | 300.84         | 432                | 9291.50          |
| pr17a        | 129.46         | 169                | 2694.58          | pr17b        | 118.37         | 165                | 3541.98          |
| pr18a        | 187.71         | 249                | 5747.19          | pr18b        | 167.93         | 246                | 8597.22          |
| pr19a        | 241.19         | 330                | 5886.77          | pr19b        | 217.92         | 321                | 9224.67          |
| pr20a        | 256.92         | 397                | 4326.69          | pr20b        | 251.91         | 388                | 4098.66          |
| pr21a        | 127.93         | 192                | 9766.02          | pr21b        | 126.67         | 191                | 9861.22          |
| pr22a        | 175.55         | 276                | 4760.64          | pr22b        | 172.73         | 276                | 10325.28         |
| pr23a        | 228.02         | 361                | 11102.03         | pr23b        | 231.04         | 363                | 11833.41         |
| pr24a        | 278.59         | 447                | 4940.95          | pr24b        | 278.05         | 449                | 5404.69          |
| Average      | 217.74         | 305.07             | 6252.61          | Average on B | 205.96         | 302.43             | 6966.54          |


## Reference
<a id="1">[1]</a> 
Wang, Sihan, Wei Sun, and Min Huang. 
"An adaptive large neighborhood search for the multi-depot dynamic vehicle routing problem with time windows." 
Computers & Industrial Engineering 191 (2024): 110122.
