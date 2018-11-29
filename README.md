# Fall of Rome
CSV data for Professor Teverson's class on mapping the fall of the Roman Empire

## Intro
As we go through the semester, you will need to update your group csv files here. At moments were we want to see what our class map looks like, we will merge the group branches back into the master branch.

The data we will create together will become complicated, and spread across multiple files and comptuers. Using github will help keep the versions organized, and will make it much less likely that you will wipe your own--or your colleagues'--hard-won data.

Another advantage of github is that it will only accept csv files--the format you need your spreadsheet data to be in for Carto to accept it.

I recommend that you download the github desktop client, as that makes uploading files to github from a folder on your computer easier.

## How to organize your files in this repository

* __File types__\
We're a csv or bust shop for the data. If you see .xls, .numbers, .txt, the center cannot hold.
* __Naming__
    * Please call your csv files:
        * NameTopicWorking
        * NameTopicClean\
It's up to you if you need a working and an import-ready clean file, or just one file.
    * Please call your working branch by a shortened version of your topic, e.g
        * battles
        * sculpture
        * inscriptions

* __Repository organization__
    * It's time to clean up the repository. Decide which branch you will work in if a suitable one already exists, if not, create one. Please delete any branches you have created so far, we no longer need them. I have removed all extraneous files from master, so new branches will be clean. 
    * As you work, think of your topic-name branch as your final draft. Once your final draft is complete, you can pull-request the final draft of your data into master. This will be the 'published' version, exported into Carto where it will form part of our final project as a class
    * In order to make changes to your ongoing final draft, you may want to make one or more branches off your topic branch, for example 'Churchbuilding'---> 'Churchbuildingworking' ----> 'Churchbuildingworkingnewtry

## How to organize your csv data columns
[(Shawn Hill's talk slides on this)](https://docs.google.com/presentation/d/1COLhUwmg57cayIbF__4e5RfH5JhtJNlbxIyOKIoRKv6Q/edit?usp=sharing)

We will use a common 'core' set of columns for all our data, which will be the same across all your projects. Alongside those, you will each use the topic-specific headings you have come up with.

A commented csv file is available here. What follows is a list of the core columns, and notes explaining their use.

* __NameModern__\
Either the commonly-known name/title in English, or, if not previously named, the name you assign
* __NameAncient__\
If not known, null if known, name in antiquity
* __LocationAncient1__
* __LocationAncient2__
* __LocationAncient3__
Use these three to give ancient location if known from most specific to least, nul if not, or if not needed. 

* __LocationModern__\
Use these three to give modern location if known from most specific to least, nul if not, or if not needed. 
* __LocationModern2__
* __LocationModern3__
* __Lat__ \
Decimal latitude (no degree symbols º)
* __Long__\
Decimal longitude (no degree symbols º)
* __GeolocationSource__ How do we know the location? Use the following terms:
    - Extant (still standing)

    - Archaeological excavation (scientific excavation)

    - modern discovery (found, by a looter, lucky farmer, Renaissance collector, etc)

    - Documentary evidence (a primary source or sources describe the location)

    - Hypothesis (a published scholar has plausible thesis)

    - Conjecture (a reasonable guess by you, or by another)

* __GeolocationCitation__\
 (where did you get the coordinated from; eg. google maps, wikipedia, etc.
* __GeolocationCertainty__\
 (% certainty that the location on the map is the original location of the item)
* __Date__\
(date as given in your research source, eg 4th century, 1152, etc.)
* __DateLow__\
lowest likely date
* __DateHigh__\
highest likely date
* __DateDecision__\
a plausible point in this range. You can either calculate this as the mathematical mean, or cheat the number if that is more accurate.

* __...subject-specific columns go here...__

* __Notes1__\
Any notes on the above, eg on the dating decision, or how the location can be argued for
* __Notes2__\
Any notes on the above, eg on the dating decision, or how the location can be argued for
* __Notes3__\
Any notes on the above, eg on the dating decision, or how the location can be argued for
* __Citation1__\
Scholarly source where you found the information here
* __Citation2__\
Scholarly source where you found the information here

## Scholarly Resources.

Data in this repository has been drawn from a range of scholarly sources, including the following online databases.

* Cities: [Hanson, J. W. (2016b). An Urban Geography of the Roman World, 100 B.C. to A.D. 300. Oxford: Archaeopress.(<http://oxrep.classics.ox.ac.uk/databases/cities/>. DOI: <https://doi.org/10.5287/bodleian:eqapevAn8>)


