# Influencer Marketing ROI Analysis

This Python tool analyzes influencer marketing data to help brands choose the best influencers for campaigns.

## Features
- Calculates **engagement rate** from followers, likes, and comments.
- Flags **potential fake followers** (low engagement, high followers).
- Computes **ROI score** to compare influencers by cost efficiency.
- Outputs results to CSV and displays them in console.

## Framework Used:
- Language: Python 3

- Libraries: Pandas (data processing, statistical calculations)

- Model Used:Type: Rule-based Statistical Model

- Core Logic:

Engagement Rate Calculation

Fake Follower Detection Rule (followers > 100k & engagement rate < 2%)

ROI Score = Engagement Rate ÷ Cost per Post

