# Comments-Analysis
This project scraps the comments of a particular instagram post whose url will be provided by the user, and then it analyzes the types of comments and visually represents them through pie chart and bar plot with the respective percentages of the emotions.

- Important files are comments_scrap.ipynb and comment_analysis.ipynb .
- The file "comments.csv" was created during the testing of the program based on a example instagram post link. This file will be automatically created during the execution of comments_scrap.ipynb, and it will store all the comments.
- The file "emotions_csv" was also created during the testing of the program. It will be automatically created during the execution of comment_analysis.ipynb. It will store the comments and their respective emotions.
- Selenium webdriver is used for the scraping of data.
- Transformer pipeline "roberta-base-go_emotions" is used for getting the emotions of the sentences. Other models can also be used. 

[![Watch the video](assets/CA_thumbnail.png)](assets/CA.mp4)
