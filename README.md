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

## Performance Metrics
Since this is not a predictive ML model but an analytical ranking system, we adapt standard ML metrics to our context:

- Metric	Adapted Meaning	Value
- Test Accuracy	% of top-ranked influencers with engagement rate ≥ 5%	73.3% (11 out of 15)
- Test Loss	Mean absolute difference between ideal ROI (max ROI in dataset) and each influencer’s ROI, normalized	0.0173
- Precision (Fake Detection)	% of flagged influencers that truly have very low engagement	100% (4/4)
- Recall (Fake Detection)	% of low-engagement influencers correctly flagged	80% (4 out of 5)
