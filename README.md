# Text-mining
BIO OIL REVIEW 
For Text Mining assignment TWO:

1) Extract reviews of any product from ecommerce website like amazon Perform emotion mining

I extract the reviews of amazon product named "Bio-Oil Original Face & Body Oil Suitable for Scar Removal | Uneven Skin Tone|Stretch Marks & Ageing Signs for Glowing Skin with Vitamin A & E | All Skin Types |" from one app called 'PARSEHUB'.
WIth the help of this app i paste the link of this product and download all the reviews related information in csv. format and used to make a sentimental analysis of the same.
we have a data of various reviews given by the users of the product "BIO OIL"on  which we have to do a sentimental analysis. we process the text (reviews) by removing unwanted column also Removed the NAN rows and blank space from the reviews. Then we join all the reviews by(' ')and do some normal steps which are tokenization, remove punctuation and stopwords,normalizing, steming and lematization.Then we convert reviews into dockblock so we can edit the text.Then we tokenize the each word in the reviews by tokenization and tag tokenized words by its part of speech by POS tagging. So that we get all the nouns and verbs from the text.After that By count vectorization we get the number of words which are repeated in text various time. we plot them on barchart according to the highest frequency of word in the reviews. 

for sentinment analysis,

we tokenize the each reviews as a one sentence and then check the sentiment of each sentence to find overall sentimental value of reviews on bio oil product are posetive ,negative or neutral. For that we use one library alled 'AFFINN' which consist of words and their sentiment value which tells us that the word having sentiment on posetive, negative or neutral side.

we pass the each review through if else loop and get the sentiment  and sentiment value of the each tweet by then this value is stored in front of each review in the dataframe. Then we plot the distribution plot and linechart to visualize the score for the all reviews and seen that most of the score are towards posetive side and few of thems are on negative and neutral side. Hence we can say that 'Reviews on bio oil product are with posetive sentiment.
