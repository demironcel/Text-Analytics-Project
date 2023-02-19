This is the analysis and review of Amazon application reviews on Android, conducted as a final assignment of Advanced Data Modelling course. The project consists of business report and source code that is used in analyses.

Introduction
--------------
Millions of users use the Amazon UK app for Android to shop online, and the app receives thousands of reviews. The reviews are full of useful information for the company, but they must first be preprocessed. As Amazon e-commerce business analysts, we monitor customer feedback and identify quality issues to improve customer experience. Managers will use customer feedback and complaints to take appropriate action. The mini-report includes the following sections: methodology, research questions and concepts, results of analyses with plots and tables, and conclusion with management
recommendations and suggestions for further research.

Methodology
------------
The main purpose for analyzing the customer feedbacks are determining the key issues and improve overall customer experience. In detail, three questions were determined:
• Based on the inspection of the most relevant negative (1 & 2 star) reviews, what are the issues
customers complained most?
• Based on the inspection of the newest negative (1&2 star) reviews, are the issues detected in
the first question still mentioned?
• Research Question 3: Based on the inspection of the most relevant (1-5 stars) reviews, what are the overall view on issues detected in the first question?
Tokenization and removing unnecessary words are applied to the reviews, then the most common tokens and bigrams are determined. This process is necessary for finding the most reported issues. Next, the review sentences that include issues as a keyword are inspected with concordance function and tokenization to get some valuable information about the details of the issues. Next, regular expressions are used to find the occurrences of the issues as keywords in the most relevant and newest reviews to compare whether customers have recently been affected by the said issue. Finally,
sentiment analysis is performed on the most relevant reviews better to understand the customers' opinions on the issues.

Results
--------
Looking at the most relevant negative reviews, it can be seen that the most frequent tokens are
“time”, “update”, “prime”, “search”, “order”, “phone”. For the same reviews, searching for the most frequent bigrams can help the company uncover some
additional complaints that may be hidden in two words. Based on the most frequent bigrams and tokens, the most complained issues are Amazon Prime
Membership, Search Results, Dark Mode, Customer Service, Home Screen, and Wish List. The next step will be the analysis of the sentences which contain these most occurred complaints. First, dark mode complaints are based on the fact that the feature does not exist; therefore, no additional analysis
is needed. From the sentences that contain “Amazon Prime”, “Customer Service”, “Search Results”, “Wish List,” and “Home Screen,” the most frequent tokens and bigrams are shown in the appendix. The tokens and bigrams for the analyzed sentences indicate that for Amazon Prime, customers complained about the day delivery, free trial, and cancellation of the membership. For Customer Service, the most reported issues are long waiting times, unresponsive call center, and unsatisfactory service experience. The main issues about the Search Results center around filtering and sorting the search results. Customers demand the added drag and drop feature for adding items to the Wish List to be included in the app. They also report some issues such as appearing and disappearing items in the wish list and editing the list. Finally, Regarding Home Screen, customers complained about not having a feature to go back to the home screen after clicking the back button and random crashes on the home screen.

The second question requires the analysis of the newest negative reviews and the most relevant negative reviews. Regular Expressions were used to see whether the complaints regarding the reported issues increased or decreased from the most relevant to the newest reviews. Comparing the first and the second result, only the mentions about the Dark Mode increased from the most relevant reviews to the newest reviews. The rest of the issues saw decline, most notably the complaints about Search Results.

Finally for the last question, the most relevant reviews for all the ratings are analysed with sentiment analysis. To achieve this analysis, sentences containing the keywords are found with Regular Expression. Based on the manual review of sentences, the sentiment analysis is not hundred percent accurate, yet it can still be concluded that customers are less happy with Search Results and Home Screen than the other issues.

Conclusions and Future Work
---------------------------
Text analytics tools are used to analyse Android customer reviews for the Amazon App. Amazon Prime, Dark Mode, Customer Service, Wish List, Search Results, and Home Screen are the most frequently complained issues. The issues are then analysed in the sentences that include them. The report then compared the occurrence of issues between the most recent and the most relevant reviews. On average, the newest reviews have more “Dark Mode” than the most relevant reviews. Finally, sentiment analysis scores showed that customers are more negative about “Home Screen” and “Search Results” than the other issues. Increasing customer satisfaction may be possible for app developers through some recommendations. Dark mode feature is relatively easy to add as a feature, and it helps with some disabled users, so it should be a priority. Second, even though “Customer Service” scored well on sentiment analysis, it occurred more than any other issues in the negative reviews, so it should be considered for enhancement, particularly in the call center branch. Home Screen scored worst on sentiment analysis; however, the complaints about the issue centered around the app’s bugs, like having a blank page when clicking an item. It can be resolved relatively more straightforwardly than the other issues, like Amazon Prime issues, which need some managerial decision making and inference. Future work recommendations for the analysis are inspecting the reviews from some time period to see how some issues are resolved over time, and others do not. This analysis requires the analyst to access reviews from a defined time horizon, which was impossible with the created dataset. The second analysis recommendation would be the analysis of the most used emojis, as the reviews contain a lot of them.
