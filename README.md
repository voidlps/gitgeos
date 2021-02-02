# gitgeos
A git-based Geo-service

### Why git-based

Most of Geo-data spatial datasets are in fact almost static.  Due to the relatively high-cost of survey, either gauging or remote sensing, it's common to update the dataset on yearly basis or even less frequent.  It makes the idea not so bad to store the data directly in some file format, and can be tracked under version control to improve the data quality.

### Track the history of each feature

It's still common we may update only a part of some spatial dataset - still the consideration of cost.  In that case, it's much better to know the detail of each feature, when it's updated, how the survey of those features are taken, and so on.

The snapshot idea (the "commit") in the git provides good practice to group some features to be updated with the same metadata description.  And we can still easily to track the history of each feature (data "file" of the feature)


