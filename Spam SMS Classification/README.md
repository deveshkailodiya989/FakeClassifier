![SSMS](readme-resources/spam-sms-banner.png)


## Feature Engineering
• Handling imbalanced dataset using Oversampling<br/>
![SpamVsHam](readme-resources/svh.png)<br/>
• **Creating new features** from existing features e.g. **word_count, contains_currency_symbol, contains_numbers**, etc.<br/>
![word_count](readme-resources/word_count.png)<br/>
![currency_numbers](readme-resources/currency_numbers.png)



## Model Building and Evaluation
**Metric: F1-Score**<br/>
• Multinomial Naive Bayes: 0.943<br/>
• Decision Tree: 0.98<br/>
• **Random Forest: 0.994**<br/>
• Voting (Decision Tree + Multinomial Naive Bayes): 0.98<br/>
![matrix](readme-resources/cm.png)<br/>
_**Note: Evaluation scores are obtained using cross validation.**_



