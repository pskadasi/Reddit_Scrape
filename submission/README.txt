This folder contains following files:

1. eda.ipynb: IPython notebook file which has EDA and data preprocessing for the data scraped. Use all the metadata
                and show the creativity to get insights from the data scraped with respect to
                sentiment of the comments for the post.
              - you can also add the link to colab file in the results.pdf document incase you dont
                want to add eda.ipynb in this folder

2. results.pdf: this document has all the write-up for the assignment.
3. word_cloud.pdf: This is the word cloud for the entire corpus (of all 100 posts) extracted.
4. kripp.py: This file is optional, if you are finding the inter-annotator agreement and are
            doing this task for BONUS points, then add this file in submission folder.
5. human_eval.csv: csv file with human annotaion (3 human annotator labels) and theie majority labels
                    corresponding to a 100 randomly sampled sentences (comments), it should also have 
                    one of the columns as comment_id.
6. posts.csv: csv file for 100 posts extracted and their metadata (no need to add comment text to this file).
7. comments/: This directory has 100 csv files which has comments and their metadata for all the top
                100 posts.
                - Name the individual csv file as {post_id}.csv
