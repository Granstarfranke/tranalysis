# tranalysis - tree ring series truncating
I do have rwl object imported to dplR

kleckeprnik<-read.rwl("klec_keprnik.rwl")
#this object contains 32 series with different cambial age. 

#Regarding my problem:
#- I need subset the first 40 rings from the pith for each series in this rwl object. But the rwl object includes series with different #cambial age.
#- I do not want to get the certain time slice from all series. I need to have different time slice for each series depending to its #cambial age.




