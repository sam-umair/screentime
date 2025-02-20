# screentime
# Screen Time Analysis and Prediction

# Introduction

In this project, we analyze screen time data to understand usage patterns, identify key influencing factors, and predict screen time based on app engagement metrics. The study focuses on:

The impact of notifications and app openings on screen time.

Daily and weekly usage trends.

Modeling screen time prediction using machine learning.

# Data Overview

The dataset consists of user screen time data, including:

Date: The day of usage.

App: The application used.

Usage (minutes): The total time spent on an app per session.

Notifications: The number of notifications received from the app.

Times Opened: How many times the app was launched.
. Key Findings

# Impact of Notifications & Times Opened on Screen Time

✅ Confirmed: Strong Correlation

WhatsApp (1706 opens) and Instagram (1039 opens) have the highest number of times opened.

Instagram has high screen time (110-119 mins per session) and receives many notifications (33-69 per session) → More notifications = More usage!

Netflix has low notifications (0-1) and very few times opened (2-5 times) → Less engagement despite long sessions.
# Which Days Have the Highest Screen Time?

✅ Confirmed: Weekends & Mondays have high usage!

Monday (1605 mins), Saturday (1409 mins), and Friday (948 mins) have high screen time.

Sunday (715 mins) is lower than expected but still significant.

Weekdays like Tuesday (877 mins) and Thursday (973 mins) show moderate usage.

Productivity apps (Gmail, LinkedIn) are used more on weekdays, while entertainment apps dominate weekends.
# Limitations

⚠️ Data was based on a specific group of users.

The dataset may not represent different demographics (e.g., students vs. professionals).

Users with different lifestyles or occupations might show different patterns.

⚠️ Other factors were not considered.

Social media engagement (likes, comments) might increase app usage but was not included.

Screen brightness or night mode usage might affect screen time but was not available in our dataset.

App type & content (e.g., watching a movie vs. scrolling Instagram) could provide deeper insights.
# Conclusion & Future Work

✅ Final Takeaways:

Notifications & times opened significantly impact screen time.

Weekends and Mondays show higher screen time.

WhatsApp & Instagram dominate engagement, while Netflix has long but infrequent sessions.

Random Forest was the best predictive model.

🚀 Future Improvements:

Consider additional behavioral data (e.g., social media interactions, screen brightness).

Test more advanced models like Deep Learning for better predictions.

Expand the dataset to a diverse user group for broader insights.
