# ProductReviewProjectG2
Project: Automated Customers Reviews

Group 2: Sohail Hiraj and Rodrigo Torralba

Project objective:
    Obtaining summarize reviews of products out of real customers products reviews.

Repository structure:
    Every line of code is written wiyh Pithon.

    The order of the execution of every notebook is defined in its name:
        01_PRP_G2: data analyse and merge of the DDBB is done.

        02_distilBertWithFineTuning: sentiment analyse of the reviews. Used to replace the reviews.rating column to avoid mismatches between text and ratings.

        02bis_Cluster_Task: new definitions of products categories based on more sensible affinities among the products themselves.

        03_GenerativeAI: summarize genuine reviews for the top 3 products of each category. 

    "Results" folder:
        All the valuable outputs from the GenerativeAI notebook
    
    "The_road_so_far" folder:
        Some results and notebooks which has been generated or abandoned trhough the project.

Deployment:
    https://review-spark-compare.lovable.app/
    A web where the meaningfullest result was deployed.



    


