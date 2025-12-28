# Rf vital sign sensing under free body movement

## Project Structure
```
mmWave-VitalSign/  
│  
├── CGU/  
│   └── src/  
│       ├── configs/  
│       ├── data_process/  
│       └── model/  
│  
└── datas/  
    ├── RobustVSDataset_anonymous/  
    └── cgu/  
```

## Datasets
The dataset for 'Rf vital sign sensing under free body movement' is self-collected. Detailed movement setup information is presented in the table below.  


|   Age  |                19-23 (4), 24-28 (7), 28-30 (3)                |
|:------:|:-------------------------------------------------------------:|
| Height |           1.60-1.70m (3), 1.70-1.80m (8), >1.80m (3)          |
| Gender |                     Male (13), Female (1)                     |
| Weight | 48-60kg (4), 60-70kg (3), 70-80kg (4), 80-90kg (2), >90kg (1) |


And related movement setup descriptions are presented in the table below.


| Motion Type |                      Subcategory                     |
|:-----------:|:----------------------------------------------------:|
|   Periodic  |                      1m, 2m, 3m                      |
|    Random   |                      1m, 2m, 3m                      |
|   Ambulant  | Front-back (fb), left-right (lr), comprehensive(com) |

