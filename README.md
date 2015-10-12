# HockeyStats

This repository contains a notebook which looks at the shot patterns of
Daniel Sedin. It is meant as a bit of fun and a learning resource, not
as any sort of serious statistical analysis. The notebook was inspired
by an excellent [blog
post](http://savvastjortjoglou.com/nba-shot-sharts.html) by [Savvas Tjortjoglou](http://savvastjortjoglou.com/). His site has numerous other interesting examples using python and is well worth a visit.

The data in the notebook comes from another excellent site:

 * http://www.sportingcharts.com/nhl/icetrack

They have some excellent interactive statistical descritions and
visualizations of NHL, MLB, NBA and NFL data.

### Requirements
I developed my notebook in jupyter, and used the following modules

 * [requests](https://pypi.python.org/pypi/requests/) &
   [json](https://docs.python.org/2/library/json.html): for making
requests and handling JSON responses
 * [pandas](http://pandas.pydata.org/): For data manupulation and
   transformation
 * [matplotlib](http://matplotlib.org/) and
   [seaborne](http://stanford.edu/~mwaskom/software/seaborn/): For
plotting
