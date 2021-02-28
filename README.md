# Metis-Project-Four

### Natural Language Processing
This projected attempted to organize the 1890 edition of Emily Dickinson's poetry using NMF machine learning 'clustering'. The poety was editted and organized by the late poet's brother, William Austin Dickinson's mistress Mabel Loomes Todd who worked as a publisher and Thomas Wentworth Higginson both of whom had extensive correspondence with Emily Dickinson over the course of her life. The former had never met with Emily in person and had the work published without the support of Emily's sister Lavinia and her sister-in law Susan Dickinson, William Austin's wife, both of whom wanted to the poetry to be published with less editing and more emphasis on Emily's personal insights on life. The complete edition of Emily Dickinson's poetry was not released until 1955 as a direct result of the famliy feud between Todd and the Dickinson's each believeing they had the sole right to the work. NLP is an approach that could test the clustering of the poems by examining works and measuring the relationships between works within a topic. This could help future publications of her work look at differences or similiarities of descriptors as centriods for the peoms clustering. 

#### Files

#### - Building NLP Project Database : 
- Data was pulled from Project Gutenberg from three books comprising the first release of the 1890 edition of Emily Dickinson's poetry. The books were availabe as txt. files. Each file was cleaned and processed for analysis removing superfluous information using Stopwords and lemantizing the corpus for feature reduction. 

#### - Topic Modeling : 
- Topic Modeling was conducted using Non-Negative Matrix Factorization that yielded five topics for the poetry. The topics pulled upon the descriptions used in the poems rather than the topic/subject. As a result of the descriptions used, many poems about Nature and Love were clustered into the Spirituality topic. Additionally, the topic modeling utilized bigrams to split the topics which allowed for Love and Communication to emerge as separate topics where as without bigrams, the topics don't appear as clearly with love, heart, tell, thou, thee all muddled amongst the all five topics. 
    
### Conclusions

- Topic modeling offers an alternative way of categorizing the Dickinson poetry body by emphasising the descriptions used in the poems rather than the subject of the poem, allowing readers to examine the writing style and choice of the author rather than interpreting the meaning of the poetry in a topics or theme. 
