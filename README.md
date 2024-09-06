# **Decoding Amazon Reviews: Innovative Insights with Agentic Language Models**

## **Data**
- The data is from Datafini.
- It lists over 34,000 consumer reviews for Amazon products like the Kindle, Fire TV Stick, and more
provided by Datafiniti's Product Database. The dataset includes each product's basic product information,
rating, review text, and more.

## **ML Techniques used**
- Used a multi agent framework to perform various unsupervised ML tasks on the dataset
- Topic Modeling Agent: identify and extract key topics from the text data, helping
businesses understand the main themes and issues discussed by their customers.
- Sentiment Analysis Agent: determine the sentiment expressed in the text, enabling
businesses to gauge customer satisfaction and identify areas of concern.
- Classification Agent: categorize the text data into predefined classes, such as product
categories or types of customer feedback, allowing for more organized and targeted analysis.
- Clustering Agent: group similar text entries together, uncovering patterns and
relationships within the data that might not be immediately apparent.
- Visualization Agent: results from each agent will be integrated and visualized in a dasboard.
- 1st approach: Single agent completes all steps. Single agent using LangChain with OpenAI GPT-3.5, Enhanced single agent with coding tools and specific instructions
- 2nd approach: Specialized approach with individual agents for each task. Python classes and Multi-agent LangChain model with GPT-3.5 Turbo.

## **Key Insights**
- Interpreted results from  LangChain multi-agent framework because it provided better insights about the reviews.
- 
**Sentiment Analysis:**
- 88.7% positive sentiment overall
- 7.67% negative sentiment, indicating areas for improvement
- All topics show positive average sentiment scores, with variations
  
**Topic Modeling:**
- Main product focus: tablets, likely Amazon Kindle Fire
- Key uses: reading, apps
- Frequently mentioned as a gift item
  
**Review Classification:**
- High number of reviews classified as complaints
- Significant number of inquiries, suggesting need for more information/support
  
**Clustering:**
- Most reviews fall in 3-5 star range
- Helpful votes don't directly correlate with high ratings
  
**Business Recommendations:**
- Gift-giving potential for targeted campaigns
- Focus on maintaining/improving reading experience, app functionality, and user interface on Kindle due to its popularity
- Address sources of complaints and negative sentiment
- Enhance product documentation and support resources
