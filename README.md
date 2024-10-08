# TikTok '24 TechJam

**Team: MyHackathon**

## TikTok Product Swiping Discovery Feature

### Overview
This repository contains our prototype aimed at personalizing user shopping experiences through an innovative "For You Page" card. By integrating swipeable shopping cards similar to Tinder's interface, we collect user preferences and utilize machine learning to dynamically tailor product recommendations.

## Features
- **Swipeable Shopping Cards**: Implement swipeable card interfaces within the TikTok feed. These cards appear intermittently between standard content cards (videos) and link directly to the product detail in TikTok Shop.
- **Dynamic Content Generation**: Each card's content is generated based on the user’s previous interactions and preferences, providing a unique and personalized shopping experience.
- **Image Recognition Algorithm**: Our image recognition algorithm identifies spotlight items in user videos (e.g., a red handbag). Based on these detected spotlight items, the shopping card recommends similar items available on TikTok Shop.


### Technology Stack

- **Frontend**: React.js
- **Machine Learning**: YOLOv5x, OpenCV
- **APIs**: Google Custom Search API
- **Web Scraping**: Requests, BeautifulSoup

## Summary
The proposed enhancements to TikTok Shop are designed to transform the shopping experience by integrating personalized, actionable shopping opportunities directly into the user's social feed. This approach is expected to increase engagement and conversion rates by leveraging sophisticated machine learning techniques to cater to individual preferences.

## Installation and Usage:
1. Clone the repository or download the source code.
2. Install the necessary dependencies for the frontend:
    ```
    npm install
    ```
3. Start the development server:
    ```
    npm run start
    ```
4. Open your browser and navigate to `http://localhost:5173` to access the app.
5. Install the required Python packages:
    ```
    pip install -r requirements.txt
    ```
    **Note**: If an error page appears, simply close it, and the app will start working.

###

## Credits
The TikTok UI Clone was created by [s-shemmee](https://github.com/s-shemmee).