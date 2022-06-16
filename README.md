# Examples on the practical use of PIDINST
Here we collect some ideas and discussions on how to implement practical linkage of globally unique persistent identifiers instrument instances to improve scientific documentation.

## Connect PIDINST with dataset level metadata
Linking sensor information at the dataset level is a tricky task since most generic metadata schemas such as [schema.org](schema.org/Dataset) or [DCAT](https://www.w3.org/TR/vocab-dcat-2/) do not provide native properties for doing this. 

At this place, possible solutions will be collected, linked to specific github-issues where these proposals can be discussed.

### Schema.org/Dataset

* [Option 1: using a linked schema.Event via schema:recordedAt](../../issues/1)
### DCAT
