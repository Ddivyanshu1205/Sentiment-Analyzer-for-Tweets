# Twitter Sentiment Analysis Project
*Created By [@Ddivyanshu1205](https://github.com/Ddivyanshu1205)*  

## 🔗 Project Links
- GitHub Repository: https://github.com/Ddivyanshu1205/twitter-sentiment-analysis
- Google Colab Notebook: [Open in Colab](https://colab.research.google.com/drive/1iOWyYQGD2qodlS9e1SJhyNROTB_EVWg-#scrollTo=04t-aFPqaPcA)

---

## 📋 Project Overview

This project analyzes Twitter sentiments using Python in Google Colab, demonstrating practical coding ability and problem-solving approach. The application fetches tweets, performs sentiment analysis, and visualizes the results.

---

## 🚀 Instructions on How to Run the App in Google Colab

### 1. Open the Notebook
- Click the "Open in Colab" link above
- Or upload the `.ipynb` file to your Google Drive and open with Colab

### 2. Install Required Packages
Run this cell first:
```python
!pip install tweepy textblob matplotlib
```

### 3. Configure Twitter API
- Get your Bearer Token from [developer.x.com](https://developer.x.com/)
- In the authentication function, replace the token:
  ```python
  def authenticate_twitter_v2():
      BEARER_TOKEN = 'YOUR_BEARER_TOKEN'  # Replace this
      client = tweepy.Client(bearer_token=BEARER_TOKEN)
      return client
  ```

### 4. Run All Cells
- Click "Runtime" → "Run all"
- Or run cells one by one using Shift+Enter

### 5. View Results
- A bar chart will display in the notebook
- Results are saved to `tweet_sentiment_results.csv`
- Example tweets are shown in the output

---

## 📊 Example Output

```
Fetching 50 tweets for query: war

Example Positive Tweets:
- @khaliphaXhood: Created a group called Crypt...
- @DalrympleWill: Everyone must watch this rem...
- @shivangitwt Do tell us if u like it...I've wan...

Example Negative Tweets:
- @CalumB60835284 I think even the most hawkish K...
- @CNNEE Disappointed with Trump ❗❗❗🤬\nht...
- @NickOnRipple: I'm seething. I'm 35 and I've...

Example Neutral Tweets:
- @ShaykhSulaiman: “ALL ISRAELI SOLDIERS ARE W...
- @gbponz: Velina, Europe is not a power. It's...
- @ricwe123: We are constantly told how the wa...

Sentiment analysis complete!
Total Tweets Analyzed: 36
Results saved to 'tweet_sentiment_results.csv'
```

---

## 📁 Project Files

- `Sentiment-Analyzer-for-tweets.ipynb` - Google Colab notebook
- `README.md` - Project documentation (this file)

---

## ⚙️ Requirements

- Google Account (for Colab access)
- Twitter Developer Account
- Required packages (automatically installed in Colab):
  - tweepy
  - pandas
  - textblob
  - matplotlib

---

## 📝 Evaluation Note

It helps us to understand:
- Practical coding ability
- Problem-solving approach
- Code organization and documentation
- API integration skills
- Data analysis and visualization capabilities

---

##  Security Note

When sharing your notebook:
- **NEVER** share your Bearer Token
- Create a copy of the notebook with the token removed
- Use environment variables or secure methods to store sensitive data

---

*Thank you for reviewing this project!*
