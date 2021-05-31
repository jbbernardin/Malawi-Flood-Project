# Malawi-Flood-Project
Using predictive modeling, determine flooding in Malawi using 2015 data to train and 2019 data to test

First commit notes:
So far all that I have this doing is reading in the data and splitting it between the train set, aka 2014/2015,
and the test set, aka 2019. I have a profile to look through things, but I don't really know how to determine if any
points are outliers. Otherwise, the data is clean, but not sorted in any fashion. We will probably want to sort it
by ID, perhaps even make it the index, since the deliverable is a csv file with the IDs with corresponding 2019 target 
values. 

In terms of modeling, we just learned how to use regression so it shouldn't be too difficult to apply what we learned
to that.