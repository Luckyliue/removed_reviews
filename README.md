# removed reviews dataset

This repo contains the following files:

1. app_info.csv: It contains all the top-ranked apps we studied, covering 25 categories.

In this file, we list the detailed information about each app, including the following columns:

    id, ranking, app_name, appid, category, app_price, developer


2. deleted reviews:

The directory contains all the deleted reviews of each app, which are packaged in chunks.

The detailed information of each review includes:

    appid, id, rating, author, comment_title, comment_content, delStatus, user_review_id, comment_date


3. undeleted reviews:

The directory contains all the undeleted reviews (that had not been captured as deleted) of each app.

The detailed information of each review includes:

    appid, id, rating, author, comment_title, comment_content, delStatus, user_review_id, comment_date
