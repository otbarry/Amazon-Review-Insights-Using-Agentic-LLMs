# **Decoding Amazon Reviews: Innovative Insights with Agentic Language Models**

## **Data**
- The data is from Datafini.
- It lists over 34,000 consumer reviews for Amazon products like the Kindle, Fire TV Stick, and more
provided by Datafiniti's Product Database. The dataset includes each product's basic product information,
rating, review text, and more.

## **ML Techniques used**
- Used a multi agent framework to perform various unsupervised ML tasks on the dataset: Review Topic Modeling Agent, Sentiment Analysis Agent, Review Classification Agent, Clustering Agent, Visualization Agent:
- 1st approach: Single agent completes all steps. Single agent using LangChain with OpenAI GPT-3.5, Enhanced single agent with coding tools and specific instructions
- 2nd approach: Specialized approach with individual agents for each task. Python classes and Multi-agent LangChain model with GPT-3.5 Turbo.

## **Key Insights**
- Interpreted results from  LangChain multi-agent framework because it provided better insights about the reviews.

**Sentiment Analysis:**
- 88.7% positive sentiment overall
- 7.67% negative sentiment, indicating areas for improvement
  
**Topic Modeling:**
- Main product focus: tablets, likely Amazon Kindle Fire
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
