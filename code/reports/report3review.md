# Report 3 Review
##### for David Papp
##### by William Lu

1. What is the primary motivating question of this report?
  
   What clustering algorithm produces clusters most consistent with NBA positions? This is clearly stated in the report, along with a brief explanation about motivations for pursuing this question. The report itself, however, implies that you haven't tried different clustering algorithms, but tuned a single algorithm's parameters. You might want to modify your motivating question to better reflect this approach.

2. What dataset(s) does it use?  What person or agency produced the data?

   While the report states that it uses a third-party API to download data from the NBA, it'd be nice to link to the API (a GitHub repository or website). Other than that, it is clear that official data from the NBA is used.

3. What analyses did the author perform?

   David and Willem apply a K-means cluster model with different numbers of clusters to shot location data for Stephen Curry. They tune the model in order to identify different clusters.

4. Does the analysis provide an answer to the motivating question?

   Yes, David and Willem seem to end up with a plot that resembles typical NBA player positions (not that I know enough about basketball to be able to tell).

5. Does the report achieve a good balance between clarity (so the reader understands the analysis) and engagement (so the article is interesting and enjoyable for the reader)?

   I think the report could be a lot more accessible to non-data scientists. Many people don't really know what a "K-means cluster model" is, and even if someone has that knowledge, figuring out what "connectivity" and "ward linkage" are in context is difficult. The entire report would benefit from a brief breakdown of what a "K-means cluster model" and its parameters mean in the context of Stephen Curry's shot location data.   

6. Is the quality of presentation professional, including details of spelling, grammar, and formatting?

   I don't see any obvious spelling, grammar, and formatting errors.
