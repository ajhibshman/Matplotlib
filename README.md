# Matplotlib
This Repository looks at a study of cancer treatments and their efficacy of reducing tumor size amongst a population of mice.

249 Unique mice began treatment on one of 10 drug regimens
1 mouse was found to have duplicate values in the reuslts and is dropped from further analysis below

Summary Table:

![sample](https://github.com/ajhibshman/Matplotlib/blob/main/images/summary.png)

Initial mouse distribution was fairly even amongst the various regimens:

![sample](https://github.com/ajhibshman/Matplotlib/blob/main/images/unique_mice_per_regimen.png)

As the study progressed, due to nonspecified reasons, data points collected per regimen vairied from the initial distribution.  We can assume that regimens with lower dat point counts were due to morbidity amongst the mouse set:

![data_points](https://github.com/ajhibshman/Matplotlib/blob/main/images/data_points_per_regimen.png)

Gender of the mice was evenly distributed:

![gender](https://github.com/ajhibshman/Matplotlib/blob/main/images/data_points_by_gender.png)

Key Treatments:
a subset of 4 ket drug regimens was selected 

Outliers:
One outlier was found via the boxplot below for Infubinol

Final Tumor sizes were plotted for the Key Treatments:

![box](https://github.com/ajhibshman/Matplotlib/blob/main/images/box_plot.png)

A single mouse undergoing treatment with Capomulin was selected and examined:

![u364](https://github.com/ajhibshman/Matplotlib/blob/main/images/mouse_u364.png)

Average mouse weight vs average Tumor size was also examined for the Capomulin treatment:

![scatter](https://github.com/ajhibshman/Matplotlib/blob/main/images/capomuloin_scatter.png)



Conclusions:

1) Only two regimens, Capomulin and Ramicane were found to reduce tumor size on average vs intital size
        
2) Amongst the Capomulin set, heavier mice were found to have larger tumor volumes

3) Initial distribution of the mice shows that the drugs shown most successful began with significantly lighter mice.  It is therefore unclear if efficacy of these treatments is due only to the treatment as heavier mice with Capomulin did not fare as well.
Inital Weight vs Tumor Volume:

![scatter](https://github.com/ajhibshman/Matplotlib/blob/main/images/initial.png)

Final Weight vs Tumor Volume:

![scatter](https://github.com/ajhibshman/Matplotlib/blob/main/images/final.png)














Conclusions



    







