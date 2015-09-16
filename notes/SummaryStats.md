Summary stats from unstructured run
2015-09-15 

> Desc(deaths[,c("id","age","raceethnicity","state","cause","armed","binmaj")], plotit=TRUE)

------------------------------------------------------------------------------------------------------------------------------------
'data.frame':	674 obs. of  7 variables:
 1 $ id           : Factor w/ 441 levels "0101","0102",..: 1 2 2 3 4 5 6 6 7 7 ...
 2 $ age          : Factor w/ 65 levels "15","16","17",..: 40 2 15 32 25 22 39 26 61 21 ...
 3 $ raceethnicity: Factor w/ 7 levels "Arab-American",..: 7 3 6 7 7 3 7 7 3 3 ...
 4 $ state        : Factor w/ 48 levels "AK","AL","AR",..: 2 2 2 2 2 2 2 2 2 2 ...
 5 $ cause        : Factor w/ 5 levels "Death in custody",..: 2 2 2 2 2 2 2 2 2 1 ...
 6 $ armed        : Factor w/ 8 levels "Disputed","Firearm",..: 2 2 2 2 6 3 2 2 2 7 ...
 7 $ binmaj       : num  0.7 0.6 0.6 0.7 0.8 0.7 0.8 0.8 0.3 0.3 ...

------------------------------------------------------------------------------------------------------------------------------------ 
1 - id (factor)

  length      n    NAs levels unique  dupes
     674    674      0    441    305      y

   level freq  perc cumfreq cumperc
1   0634   12  .018      12    .018
2   4005   11  .016      23    .034
3   0407    9  .013      32    .047
4   4818    9  .013      41    .061
5   0401    8  .012      49    .073
6   2202    7  .010      56    .083
7   4001    7  .010      63    .093
8   4002    7  .010      70    .104
9   4812    7  .010      77    .114
10  0612    6  .009      83    .123
11  0623    6  .009      89    .132
12  0635    6  .009      95    .141
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
2 - age (factor)

  length      n    NAs levels unique  dupes
     674    674      0     65     65      y

   level freq  perc cumfreq cumperc
1     35   31  .046      31    .046
2     24   25  .037      56    .083
3     26   23  .034      79    .117
4     23   22  .033     101    .150
5     28   22  .033     123    .182
6     29   22  .033     145    .215
7     31   22  .033     167    .248
8     34   21  .031     188    .279
9     33   20  .030     208    .309
10    36   20  .030     228    .338
11    27   19  .028     247    .366
12    39   19  .028     266    .395
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
3 - raceethnicity (factor)

  length      n    NAs levels unique  dupes
     674    674      0      7      7      y

                   level freq  perc cumfreq cumperc
1                  White  331  .491     331    .491
2                  Black  176  .261     507    .752
3        Hispanic/Latino  100  .148     607    .901
4                Unknown   43  .064     650    .964
5 Asian/Pacific Islander   13  .019     663    .984
6        Native American    8  .012     671    .996
7          Arab-American    3  .004     674   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
4 - state (factor)

  length      n    NAs levels unique  dupes
     674    674      0     48     48      y

   level freq  perc cumfreq cumperc
1     CA  110  .163     110    .163
2     TX   68  .101     178    .264
3     FL   46  .068     224    .332
4     AZ   31  .046     255    .378
5     OK   29  .043     284    .421
6     GA   23  .034     307    .455
7     NY   19  .028     326    .484
8     OH   19  .028     345    .512
9     CO   17  .025     362    .537
10    NJ   17  .025     379    .562
11    NC   16  .024     395    .586
12    LA   15  .022     410    .608
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
5 - cause (factor)

  length      n    NAs levels unique  dupes
     674    674      0      5      5      y

              level freq  perc cumfreq cumperc
1           Gunshot  586  .869     586    .869
2             Taser   34  .050     620    .920
3  Death in custody   28  .042     648    .961
4 Struck by vehicle   23  .034     671    .996
5           Unknown    3  .004     674   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
6 - armed (factor)

  length      n    NAs levels unique  dupes
     674    674      0      8      8      y

               level freq  perc cumfreq cumperc
1            Firearm  324  .481     324    .481
2                 No  146  .217     470    .697
3              Knife   97  .144     567    .841
4              Other   38  .056     605    .898
5            Vehicle   24  .036     629    .933
6 Non-lethal firearm   22  .033     651    .966
7            Unknown   21  .031     672    .997
8           Disputed    2  .003     674   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
7 - binmaj (numeric)

  length      n    NAs unique     0s   mean meanSE
     674    674      0     10      0  0.585  0.009

     .05    .10    .25 median    .75    .90    .95
   0.200  0.200  0.400  0.600  0.800  0.900  0.900

     rng     sd  vcoef    mad    IQR   skew   kurt
   0.900  0.227  0.389  0.297  0.400 -0.448 -0.792
 
lowest : 0.1 (21), 0.2 (58), 0.3 (57), 0.4 (55), 0.5 (51)
highest: 0.6 (124), 0.7 (135), 0.8 (94), 0.9 (74), 1 (5)

Shapiro-Wilks normality test  p.value : < 2.22e-16 



> Desc(wdeaths[,c("id","age","raceethnicity","state","cause","armed","binmaj")])

------------------------------------------------------------------------------------------------------------------------------------
'data.frame':	331 obs. of  7 variables:
 1 $ id           : Factor w/ 441 levels "0101","0102",..: 1 3 4 6 6 9 9 9 9 9 ...
 2 $ age          : num  54 46 39 53 40 56 35 40 29 32 ...
 3 $ raceethnicity: Factor w/ 7 levels "Arab-American",..: 7 7 7 7 7 7 7 7 7 7 ...
 4 $ state        : Factor w/ 48 levels "AK","AL","AR",..: 2 2 2 2 2 4 4 4 4 4 ...
 5 $ cause        : Factor w/ 5 levels "Death in custody",..: 2 2 2 2 2 2 2 2 2 2 ...
 6 $ armed        : Factor w/ 8 levels "Disputed","Firearm",..: 2 2 6 2 2 2 6 2 2 2 ...
 7 $ binmaj       : num  0.7 0.7 0.8 0.8 0.8 0.5 0.5 0.5 0.5 0.5 ...

------------------------------------------------------------------------------------------------------------------------------------ 
1 - id (factor)

  length      n    NAs levels unique  dupes
     331    331      0    441    208      y

   level freq  perc cumfreq cumperc
1   0407    6  .018       6    .018
2   4002    6  .018      12    .036
3   4821    6  .018      18    .054
4   0401    5  .015      23    .069
5   2105    5  .015      28    .085
6   4005    5  .015      33    .100
7   0404    4  .012      37    .112
8   4901    4  .012      41    .124
9   0601    3  .009      44    .133
10  0608    3  .009      47    .142
11  0612    3  .009      50    .151
12  0803    3  .009      53    .160
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
2 - age (numeric)

  length      n    NAs unique     0s   mean meanSE
     331    331      0     61      0 40.631  0.761

     .05    .10    .25 median    .75    .90    .95
      20     24     30     39     50     59 63.500

     rng     sd  vcoef    mad    IQR   skew   kurt
      72 13.844  0.341 14.826     20  0.438 -0.263
 
lowest : 15, 16, 17 (6), 18 (5), 19 (3)
highest: 75, 76, 77, 83, 87

Shapiro-Wilks normality test  p.value : 6.6548e-05 

------------------------------------------------------------------------------------------------------------------------------------ 
3 - raceethnicity (factor)

  length      n    NAs levels unique  dupes
     331    331      0      7      1      y

                   level freq perc cumfreq cumperc
1                  White  331    1     331       1
2          Arab-American    0    0     331       1
3 Asian/Pacific Islander    0    0     331       1
4                  Black    0    0     331       1
5        Hispanic/Latino    0    0     331       1
6        Native American    0    0     331       1
7                Unknown    0    0     331       1

------------------------------------------------------------------------------------------------------------------------------------ 
4 - state (factor)

  length      n    NAs levels unique  dupes
     331    331      0     48     45      y

   level freq  perc cumfreq cumperc
1     CA   39  .118      39    .118
2     TX   27  .082      66    .199
3     FL   20  .060      86    .260
4     AZ   19  .057     105    .317
5     OK   18  .054     123    .372
6     NC   11  .033     134    .405
7     NY   10  .030     144    .435
8     OR   10  .030     154    .465
9     OH    9  .027     163    .492
10    SC    9  .027     172    .520
11    WA    9  .027     181    .547
12    IN    8  .024     189    .571
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
5 - cause (factor)

  length      n    NAs levels unique  dupes
     331    331      0      5      5      y

              level freq  perc cumfreq cumperc
1           Gunshot  296  .894     296    .894
2 Struck by vehicle   14  .042     310    .937
3             Taser   11  .033     321    .970
4  Death in custody    9  .027     330    .997
5           Unknown    1  .003     331   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
6 - armed (factor)

  length      n    NAs levels unique  dupes
     331    331      0      8      8      y

               level freq  perc cumfreq cumperc
1            Firearm  174  .526     174    .526
2                 No   58  .175     232    .701
3              Knife   43  .130     275    .831
4              Other   15  .045     290    .876
5 Non-lethal firearm   14  .042     304    .918
6            Unknown   13  .039     317    .958
7            Vehicle   13  .039     330    .997
8           Disputed    1  .003     331   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
7 - binmaj (numeric)

  length      n    NAs unique     0s   mean meanSE
     331    331      0     10      0  0.663  0.011

     .05    .10    .25 median    .75    .90    .95
   0.200  0.400  0.600  0.700  0.800  0.900  0.900

     rng     sd  vcoef    mad    IQR   skew   kurt
   0.900  0.201  0.303  0.148  0.200 -0.796  0.035
 
lowest : 0.1 (3), 0.2 (16), 0.3 (12), 0.4 (22), 0.5 (24)
highest: 0.6 (52), 0.7 (77), 0.8 (66), 0.9 (54), 1 (5)

Shapiro-Wilks normality test  p.value : 1.6761e-12 


> Desc(mdeaths[,c("id","age","raceethnicity","state","cause","armed","binmaj")])

------------------------------------------------------------------------------------------------------------------------------------
'data.frame':	343 obs. of  7 variables:
 1 $ id           : Factor w/ 441 levels "0101","0102",..: 2 2 5 7 7 7 8 8 9 9 ...
 2 $ age          : Factor w/ 65 levels "15","16","17",..: 2 15 22 61 21 24 19 19 23 10 ...
 3 $ raceethnicity: Factor w/ 7 levels "Arab-American",..: 3 6 3 3 3 3 4 5 4 5 ...
 4 $ state        : Factor w/ 48 levels "AK","AL","AR",..: 2 2 2 2 2 2 1 1 4 4 ...
 5 $ cause        : Factor w/ 5 levels "Death in custody",..: 2 2 2 2 1 2 2 1 2 2 ...
 6 $ armed        : Factor w/ 8 levels "Disputed","Firearm",..: 2 2 3 2 7 2 2 4 3 2 ...
 7 $ binmaj       : num  0.6 0.6 0.7 0.3 0.3 0.3 0.6 0.6 0.5 0.5 ...

------------------------------------------------------------------------------------------------------------------------------------ 
1 - id (factor)

  length      n    NAs levels unique  dupes
     343    343      0    441    186      y

   level freq  perc cumfreq cumperc
1   0634   11  .032      11    .032
2   4818    8  .023      19    .055
3   2202    6  .017      25    .073
4   4005    6  .017      31    .090
5   0646    5  .015      36    .105
6   3610    5  .015      41    .120
7   4812    5  .015      46    .134
8   0609    4  .012      50    .146
9   0621    4  .012      54    .157
10  0623    4  .012      58    .169
11  0635    4  .012      62    .181
12  0804    4  .012      66    .192
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
2 - age (factor)

  length      n    NAs levels unique  dupes
     343    343      0     65     53      y

   level freq  perc cumfreq cumperc
1     24   16  .047      16    .047
2     26   16  .047      32    .093
3     29   16  .047      48    .140
4     35   16  .047      64    .187
5     23   15  .044      79    .230
6     28   13  .038      92    .268
7     33   13  .038     105    .306
8     22   12  .035     117    .341
9     27   12  .035     129    .376
10    25   11  .032     140    .408
11    36   11  .032     151    .440
12    37   11  .032     162    .472
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
3 - raceethnicity (factor)

  length      n    NAs levels unique  dupes
     343    343      0      7      6      y

                   level freq  perc cumfreq cumperc
1                  Black  176  .513     176    .513
2        Hispanic/Latino  100  .292     276    .805
3                Unknown   43  .125     319    .930
4 Asian/Pacific Islander   13  .038     332    .968
5        Native American    8  .023     340    .991
6          Arab-American    3  .009     343   1.000
7                  White    0  .000     343   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
4 - state (factor)

  length      n    NAs levels unique  dupes
     343    343      0     48     42      y

   level freq  perc cumfreq cumperc
1     CA   71  .207      71    .207
2     TX   41  .120     112    .327
3     FL   26  .076     138    .402
4     GA   16  .047     154    .449
5     AZ   12  .035     166    .484
6     CO   11  .032     177    .516
7     NJ   11  .032     188    .548
8     OK   11  .032     199    .580
9     MD   10  .029     209    .609
10    OH   10  .029     219    .638
11    IL    9  .026     228    .665
12    NY    9  .026     237    .691
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
5 - cause (factor)

  length      n    NAs levels unique  dupes
     343    343      0      5      5      y

              level freq  perc cumfreq cumperc
1           Gunshot  290  .845     290    .845
2             Taser   23  .067     313    .913
3  Death in custody   19  .055     332    .968
4 Struck by vehicle    9  .026     341    .994
5           Unknown    2  .006     343   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
6 - armed (factor)

  length      n    NAs levels unique  dupes
     343    343      0      8      8      y

               level freq  perc cumfreq cumperc
1            Firearm  150  .437     150    .437
2                 No   88  .257     238    .694
3              Knife   54  .157     292    .851
4              Other   23  .067     315    .918
5            Vehicle   11  .032     326    .950
6 Non-lethal firearm    8  .023     334    .974
7            Unknown    8  .023     342    .997
8           Disputed    1  .003     343   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
7 - binmaj (numeric)

  length      n    NAs unique     0s   mean meanSE
     343    343      0      9      0  0.509  0.012

     .05    .10    .25 median    .75    .90    .95
   0.110  0.200  0.300  0.600  0.700  0.800  0.900

     rng     sd  vcoef    mad    IQR   skew   kurt
   0.800  0.226  0.445  0.297  0.400 -0.146 -1.081
 
lowest : 0.1 (18), 0.2 (42), 0.3 (45), 0.4 (33), 0.5 (27)
highest: 0.5 (27), 0.6 (72), 0.7 (58), 0.8 (28), 0.9 (20)

Shapiro-Wilks normality test  p.value : 1.7687e-10 


> Desc(bdeaths[,c("id","age","raceethnicity","state","cause","armed","binmaj")])

------------------------------------------------------------------------------------------------------------------------------------
'data.frame':	176 obs. of  7 variables:
 1 $ id           : Factor w/ 441 levels "0101","0102",..: 2 5 7 7 7 14 21 25 30 31 ...
 2 $ age          : num  16 36 77 35 38 42 36 22 29 29 ...
 3 $ raceethnicity: Factor w/ 7 levels "Arab-American",..: 3 3 3 3 3 3 3 3 3 3 ...
 4 $ state        : Factor w/ 48 levels "AK","AL","AR",..: 2 2 2 2 2 4 3 5 5 5 ...
 5 $ cause        : Factor w/ 5 levels "Death in custody",..: 2 2 2 1 2 2 2 2 2 2 ...
 6 $ armed        : Factor w/ 8 levels "Disputed","Firearm",..: 2 3 2 7 2 8 4 4 3 5 ...
 7 $ binmaj       : num  0.6 0.7 0.3 0.3 0.3 0.8 0.7 0.8 0.4 0.5 ...

------------------------------------------------------------------------------------------------------------------------------------ 
1 - id (factor)

  length      n    NAs levels unique  dupes
     176    176      0    441    116      y

   level freq  perc cumfreq cumperc
1   2202    6  .034       6    .034
2   4005    5  .028      11    .062
3   1205    4  .023      15    .085
4   2901    4  .023      19    .108
5   0107    3  .017      22    .125
6   0634    3  .017      25    .142
7   1222    3  .017      28    .159
8   1227    3  .017      31    .176
9   1305    3  .017      34    .193
10  2402    3  .017      37    .210
11  3409    3  .017      40    .227
12  3610    3  .017      43    .244
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
2 - age (numeric)

  length      n    NAs unique     0s   mean meanSE
     176    176      0     45      0 33.347  0.841

     .05    .10    .25 median    .75    .90    .95
      19 20.500     25     32     40 47.500 52.250

     rng     sd  vcoef    mad    IQR   skew   kurt
      61 11.164  0.335 10.378     15  1.017  1.409
 
lowest : 16 (2), 17, 18 (4), 19 (4), 20 (7)
highest: 62, 63, 64, 74, 77

Shapiro-Wilks normality test  p.value : 6.3907e-07 

------------------------------------------------------------------------------------------------------------------------------------ 
3 - raceethnicity (factor)

  length      n    NAs levels unique  dupes
     176    176      0      7      1      y

                   level freq perc cumfreq cumperc
1                  Black  176    1     176       1
2          Arab-American    0    0     176       1
3 Asian/Pacific Islander    0    0     176       1
4        Hispanic/Latino    0    0     176       1
5        Native American    0    0     176       1
6                Unknown    0    0     176       1
7                  White    0    0     176       1

------------------------------------------------------------------------------------------------------------------------------------ 
4 - state (factor)

  length      n    NAs levels unique  dupes
     176    176      0     48     33      y

   level freq  perc cumfreq cumperc
1     FL   21  .119      21    .119
2     CA   16  .091      37    .210
3     TX   13  .074      50    .284
4     GA   10  .057      60    .341
5     MD   10  .057      70    .398
6     OH    9  .051      79    .449
7     OK    9  .051      88    .500
8     LA    8  .045      96    .545
9     VA    8  .045     104    .591
10    NY    7  .040     111    .631
11    IL    6  .034     117    .665
12    PA    6  .034     123    .699
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
5 - cause (factor)

  length      n    NAs levels unique  dupes
     176    176      0      5      5      y

              level freq  perc cumfreq cumperc
1           Gunshot  142  .807     142    .807
2             Taser   16  .091     158    .898
3  Death in custody   11  .062     169    .960
4 Struck by vehicle    6  .034     175    .994
5           Unknown    1  .006     176   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
6 - armed (factor)

  length      n    NAs levels unique  dupes
     176    176      0      8      8      y

               level freq  perc cumfreq cumperc
1            Firearm   77  .438      77    .438
2                 No   55  .312     132    .750
3              Knife   20  .114     152    .864
4              Other    7  .040     159    .903
5            Vehicle    7  .040     166    .943
6 Non-lethal firearm    5  .028     171    .972
7            Unknown    4  .023     175    .994
8           Disputed    1  .006     176   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
7 - binmaj (numeric)

  length      n    NAs unique     0s   mean meanSE
     176    176      0      9      0  0.517  0.016

     .05    .10    .25 median    .75    .90    .95
   0.200  0.250  0.300  0.600  0.700  0.800  0.800

     rng     sd  vcoef    mad    IQR   skew   kurt
   0.800  0.209  0.403  0.297  0.400 -0.117 -1.116
 
lowest : 0.1 (4), 0.2 (14), 0.3 (36), 0.4 (17), 0.5 (12)
highest: 0.5 (12), 0.6 (37), 0.7 (35), 0.8 (14), 0.9 (7)

Shapiro-Wilks normality test  p.value : 3.8371e-07 


> Desc(hdeaths[,c("id","age","raceethnicity","state","cause","armed","binmaj")])

------------------------------------------------------------------------------------------------------------------------------------
'data.frame':	100 obs. of  7 variables:
 1 $ id           : Factor w/ 441 levels "0101","0102",..: 8 9 10 15 15 17 17 22 24 24 ...
 2 $ age          : Factor w/ 65 levels "15","16","17",..: 19 23 37 14 14 8 14 7 22 8 ...
 3 $ raceethnicity: Factor w/ 7 levels "Arab-American",..: 4 4 4 4 4 4 4 4 4 4 ...
 4 $ state        : Factor w/ 48 levels "AK","AL","AR",..: 1 4 4 4 4 4 4 5 5 5 ...
 5 $ cause        : Factor w/ 5 levels "Death in custody",..: 2 2 2 2 2 2 2 2 2 2 ...
 6 $ armed        : Factor w/ 8 levels "Disputed","Firearm",..: 2 3 3 4 2 2 2 3 3 4 ...
 7 $ binmaj       : num  0.6 0.5 0.6 0.2 0.2 0.6 0.6 0.8 0.5 0.5 ...

------------------------------------------------------------------------------------------------------------------------------------ 
1 - id (factor)

  length      n    NAs levels unique  dupes
     100    100      0    441     67      y

   level freq perc cumfreq cumperc
1   4818    6  .06       6     .06
2   0634    5  .05      11     .11
3   0621    4  .04      15     .15
4   0635    4  .04      19     .19
5   0644    3  .03      22     .22
6   0646    3  .03      25     .25
7   4816    3  .03      28     .28
8   4835    3  .03      31     .31
9   0407    2  .02      33     .33
10  0409    2  .02      35     .35
11  0603    2  .02      37     .37
12  0632    2  .02      39     .39
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
2 - age (factor)

  length      n    NAs levels unique  dupes
     100    100      0     65     34      y

   level freq perc cumfreq cumperc
1     24    7  .07       7     .07
2     27    7  .07      14     .14
3     28    7  .07      21     .21
4     22    6  .06      27     .27
5     33    6  .06      33     .33
6     23    5  .05      38     .38
7     35    5  .05      43     .43
8     39    5  .05      48     .48
9     21    4  .04      52     .52
10    29    4  .04      56     .56
11    37    4  .04      60     .60
12    25    3  .03      63     .63
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
3 - raceethnicity (factor)

  length      n    NAs levels unique  dupes
     100    100      0      7      1      y

                   level freq perc cumfreq cumperc
1        Hispanic/Latino  100    1     100       1
2          Arab-American    0    0     100       1
3 Asian/Pacific Islander    0    0     100       1
4                  Black    0    0     100       1
5        Native American    0    0     100       1
6                Unknown    0    0     100       1
7                  White    0    0     100       1

------------------------------------------------------------------------------------------------------------------------------------ 
4 - state (factor)

  length      n    NAs levels unique  dupes
     100    100      0     48     20      y

   level freq perc cumfreq cumperc
1     CA   38  .38      38     .38
2     TX   24  .24      62     .62
3     AZ    6  .06      68     .68
4     CO    4  .04      72     .72
5     FL    4  .04      76     .76
6     MA    3  .03      79     .79
7     NJ    3  .03      82     .82
8     NM    3  .03      85     .85
9     KS    2  .02      87     .87
10    NY    2  .02      89     .89
11    WA    2  .02      91     .91
12    AK    1  .01      92     .92
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
5 - cause (factor)

  length      n    NAs levels unique  dupes
     100    100      0      5      4      y

              level freq perc cumfreq cumperc
1           Gunshot   92  .92      92     .92
2  Death in custody    4  .04      96     .96
3             Taser    3  .03      99     .99
4           Unknown    1  .01     100    1.00
5 Struck by vehicle    0  .00     100    1.00

------------------------------------------------------------------------------------------------------------------------------------ 
6 - armed (factor)

  length      n    NAs levels unique  dupes
     100    100      0      8      7      y

               level freq perc cumfreq cumperc
1            Firearm   42  .42      42     .42
2                 No   21  .21      63     .63
3              Knife   19  .19      82     .82
4              Other    9  .09      91     .91
5 Non-lethal firearm    3  .03      94     .94
6            Unknown    3  .03      97     .97
7            Vehicle    3  .03     100    1.00
8           Disputed    0  .00     100    1.00

------------------------------------------------------------------------------------------------------------------------------------ 
7 - binmaj (numeric)

  length      n    NAs unique     0s   mean meanSE
     100    100      0      9      0  0.462  0.025

     .05    .10    .25 median    .75    .90    .95
   0.100  0.100  0.200  0.500  0.600  0.800  0.805

     rng     sd  vcoef    mad    IQR   skew   kurt
   0.800  0.247  0.534  0.297  0.400 -0.004 -1.294
 
lowest : 0.1 (11), 0.2 (23), 0.3, 0.4 (11), 0.5 (8)
highest: 0.5 (8), 0.6 (22), 0.7 (11), 0.8 (8), 0.9 (5)

Shapiro-Wilks normality test  p.value : 6.4669e-06 


> Desc(odeaths[,c("id","age","raceethnicity","state","cause","armed","binmaj")])

------------------------------------------------------------------------------------------------------------------------------------
'data.frame':	67 obs. of  7 variables:
 1 $ id           : Factor w/ 441 levels "0101","0102",..: 2 8 9 9 10 15 17 18 18 24 ...
 2 $ age          : Factor w/ 65 levels "15","16","17",..: 15 19 10 4 14 12 19 56 27 17 ...
 3 $ raceethnicity: Factor w/ 7 levels "Arab-American",..: 6 5 5 6 6 5 5 6 6 6 ...
 4 $ state        : Factor w/ 48 levels "AK","AL","AR",..: 2 1 4 4 4 4 4 3 3 5 ...
 5 $ cause        : Factor w/ 5 levels "Death in custody",..: 2 1 2 3 2 2 2 2 2 2 ...
 6 $ armed        : Factor w/ 8 levels "Disputed","Firearm",..: 2 4 2 4 3 8 2 2 3 2 ...
 7 $ binmaj       : num  0.6 0.6 0.5 0.5 0.6 0.2 0.6 0.8 0.8 0.5 ...

------------------------------------------------------------------------------------------------------------------------------------ 
1 - id (factor)

  length      n    NAs levels unique  dupes
      67     67      0    441     55      y

   level freq  perc cumfreq cumperc
1   0623    3  .045       3    .045
2   0634    3  .045       6    .090
3   0401    2  .030       8    .119
4   0501    2  .030      10    .149
5   0609    2  .030      12    .179
6   0617    2  .030      14    .209
7   1304    2  .030      16    .239
8   1501    2  .030      18    .269
9   1707    2  .030      20    .299
10  4812    2  .030      22    .328
11  0102    1  .015      23    .343
12  0200    1  .015      24    .358
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
2 - age (factor)

  length      n    NAs levels unique  dupes
      67     67      0     65     38      y

     level freq  perc cumfreq cumperc
1       35    5  .075       5    .075
2  Unknown    5  .075      10    .149
3       24    4  .060      14    .209
4       28    3  .045      17    .254
5       33    3  .045      20    .299
6       57    3  .045      23    .343
7       20    2  .030      25    .373
8       23    2  .030      27    .403
9       26    2  .030      29    .433
10      29    2  .030      31    .463
11      31    2  .030      33    .493
12      38    2  .030      35    .522
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
3 - raceethnicity (factor)

  length      n    NAs levels unique  dupes
      67     67      0      7      4      y

                   level freq  perc cumfreq cumperc
1                Unknown   43  .642      43    .642
2 Asian/Pacific Islander   13  .194      56    .836
3        Native American    8  .119      64    .955
4          Arab-American    3  .045      67   1.000
5                  Black    0  .000      67   1.000
6        Hispanic/Latino    0  .000      67   1.000
7                  White    0  .000      67   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
4 - state (factor)

  length      n    NAs levels unique  dupes
      67     67      0     48     29      y

   level freq  perc cumfreq cumperc
1     CA   17  .254      17    .254
2     AZ    5  .075      22    .328
3     GA    5  .075      27    .403
4     TX    4  .060      31    .463
5     CO    3  .045      34    .507
6     NJ    3  .045      37    .552
7     AR    2  .030      39    .582
8     HI    2  .030      41    .612
9     IL    2  .030      43    .642
10    NC    2  .030      45    .672
11    NV    2  .030      47    .701
12    TN    2  .030      49    .731
... etc.
 [list output truncated]

------------------------------------------------------------------------------------------------------------------------------------ 
5 - cause (factor)

  length      n    NAs levels unique  dupes
      67     67      0      5      4      y

              level freq  perc cumfreq cumperc
1           Gunshot   56  .836      56    .836
2  Death in custody    4  .060      60    .896
3             Taser    4  .060      64    .955
4 Struck by vehicle    3  .045      67   1.000
5           Unknown    0  .000      67   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
6 - armed (factor)

  length      n    NAs levels unique  dupes
      67     67      0      8      6      y

               level freq  perc cumfreq cumperc
1            Firearm   31  .463      31    .463
2              Knife   15  .224      46    .687
3                 No   12  .179      58    .866
4              Other    7  .104      65    .970
5            Unknown    1  .015      66    .985
6            Vehicle    1  .015      67   1.000
7           Disputed    0  .000      67   1.000
8 Non-lethal firearm    0  .000      67   1.000

------------------------------------------------------------------------------------------------------------------------------------ 
7 - binmaj (numeric)

  length      n    NAs unique     0s   mean meanSE
      67     67      0      9      0  0.558  0.028

     .05    .10    .25 median    .75    .90    .95
   0.200  0.200  0.400  0.600  0.700  0.900  0.900

     rng     sd  vcoef    mad    IQR   skew   kurt
   0.800  0.230  0.413  0.297  0.300 -0.290 -0.945
 
lowest : 0.1 (3), 0.2 (5), 0.3 (8), 0.4 (5), 0.5 (7)
highest: 0.5 (7), 0.6 (13), 0.7 (12), 0.8 (6), 0.9 (8)

Shapiro-Wilks normality test  p.value : 0.0036777 


> 