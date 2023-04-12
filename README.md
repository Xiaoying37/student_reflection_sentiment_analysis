# student_reflection_sentiment_analysis

## Sentences break down
Read a txt file (a post that a student wrote), extract sentences which are separated by period, exclamation point or question mark while keeping the punctuations in the sentence, remove any new line, and save sentences in a list called "sentences"

## Extract keyword sentences
Find out sentences in sentences list which contain any keyword in keyword list and save those sentences in a list called "keyword_sentences"

## Sentiment Analysis
Use the multilingual XLM-roBERTa-base model trained on ~198M tweets to run sentiment analysis for each post

## Save results
Save the results into a csv file for each post. There're two columns: sentences (that contain knowledge keyword) and sentiment label.
