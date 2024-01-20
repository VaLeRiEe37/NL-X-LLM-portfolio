| [home page](https://valeriee37.github.io/NLXLLM-portfolio/) | [Quizzes](https://tbd.html) | [Individual Assignments](https://tbd.html) | [Group Project](https://tbd.html) |

# HW#1 Report - Text Classification Task

## A. Tools or Frameworks Used

1. NLTK: Leveraged for sentiment analysis using the VADER tool, which is tailored for social media text sentiment assessment.

2. spaCy: Utilized for efficient and accurate Named Entity Recognition (NER), categorizing entities within our texts.

3. TextBlob: Simple yet effective tool for sentiment analysis, offering an additional perspective on the sentiment expressed in our documents.

4. Matplotlib & Seaborn: These libraries created visualizations to illustrate our findings effectively, from entity distributions to sentiment analysis comparisons.

## B. Results Obtained
The analysis yielded three main types of results:

1. Entity Distribution:

The entity type counts showed a varied distribution across different categories. For instance, certain types of entities like DATE, ORG (organizations), and PERSON were more prevalent in specific categories, reflecting the thematic focus of each category.

2. Sentiment Analysis:

Both TextBlob and VADER were used to analyze sentiment. While the trend in sentiment (positive, neutral, or negative) was generally consistent across both methods, there was a noticeable discrepancy in the scores assigned by each tool. The bar plots illustrated these differences in sentiment distribution.

3. Average Sentiment Scores:

The comparison of average sentiment scores between TextBlob and VADER highlighted the variance in sentiment assessment. While one method might give a more moderate score, the other could show a more extreme sentiment for the same text.

## C. Analysis/Reflection on the Results

1. NER Analysis:

The entity distribution across categories indicated the concentration of specific themes and subjects within each category. For example, the business category may contain more ORG and MONEY entities, which aligns with the expectations for such content.

2. Sentiment Analysis Discrepancies:

The differing sentiment scores between TextBlob and VADER can be attributed to their underlying methodologies. VADER, with its emphasis on social media language, may interpret sentiment intensity differently than TextBlob, which uses a more general approach. This distinction can cause similar texts to receive varying sentiment scores from each tool, as observed in the visualizations.

3. Average Sentiment Score Comparison:

When we compare the average sentiment scores, we notice that some categories show a larger gap between the two tools than others. This variation could be influenced by the linguistic characteristics of the texts in each category. For example, texts with more nuanced language or ambiguous sentiment expressions might be scored differently by the two methods.