## 2024-02
-----------

download data from: XXXX
extract files to a suitable directory

Download skyline from https://skyline.ms/project/home/software/Skyline/begin.view
You'll need to make an account. 
There are two versions of skyline. Skyline - 32 bit and Skyline-daily (beta)
Skyline-daily will have new features. Updated pretty regularly. 
Excellent written and video tutorials:  https://skyline.ms/wiki/home/software/Skyline/page.view?name=tutorialshttps://skyline.ms/wiki/home/software/Skyline/page.view?name=tutorials

### Steps for targeted analysis in Skyline
#### transition list
Skyline is hypothesis driven => need a list of targets before you begin.
Can create from a PCDL, Lipidannotater export etc
It's a csv file. I've prepared a transition list for this tutorial in  
assets/transition_list_ion_pairing.csv
when including heavy isotopes the ' notion is used eg  C5H11NO2S [M+H] and C5H8H'3NO2S [M+H] for methionine and d3-methionine
alternatively C5H11NO2S [M+H] and C5H11NO2S [M3H2+H] can be used
settings->Default
make sure you have *molecule interface* selected from the top right
Import -> transition list
Clicking the arrow in the headers show all the headers available (there are a lot!)
##### adding samples
import-results
#### grouping
this is a cumbersome part of skyline. 
settings -> document settings
annotations -> add -> name -> text  
OR  
annotations -> add -> name -> value list -> enter group names
view -> doument grid -> replicates -> annoations
##### tips
On replicate areas or retetion times:
right click -> order by grouping

sync integration

