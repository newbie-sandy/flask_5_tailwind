# Video hosting, GCP Cloud CDN, Tailwind

Azure student account is disabled

- Create GCP storage bucket and Cloud CDN
  - Challenges met:
    - Public access

- Steps for setting up and using the CDN with your Flask app： https://cloud.google.com/media-cdn/docs/quickstart
  - Challenges:
    - Step: Create an EdgeCacheService resource
      
      There's no services tab under the Cloud CDN
      ![image](https://github.com/newbie-sandy/flask_5_tailwind/assets/143536852/4cbeb6eb-c198-4bb1-814b-2627ec2d3f47)

- Video hosting
  - In cloud CDN
    copy endpoint hostname - paste in search bar
  - In Storage bucket
    copy the url (after the domain) - paste after entering / behind the cdn endpoint hostname
      
- Steps for deploying your Flask app to the chosen cloud platform.







Tip: Performance matters! The more optimized your assets are and the better they're served (e.g., via CDN), the better the user experience.
