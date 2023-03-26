  <details> <summary> Unit Test Cases S2</summary>
  <p>
    
    
| Test Case ID# | Test case description | Test steps | Expected result | Prerequisites | Executed by | Tested by | Pass/Fail | Path for Result |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | User must signup with valid username and password. | Fillup the details for signup and next page will be login page. | Successfully signup and landing to login page. | https://newsapi.org/ and valid URL| Cristofer | Zal | Fail | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/signup_test.png |
| 2 | User must signup with valid username and password. | Fillup the details for signup and next page will be login page. | Successfully signup and landing to login page. | https://newsapi.org/ and valid URL| Cristofer | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/signin_test.png |
| 3 | Default landing page should display the news article from the General Category. | Run your project and it should land you on articles page without login | News article fetch from the API from general category. | https://newsapi.org/ and valid URL| Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/app_test.png  |
| 4 | Categories preferences should be displayed in the Dashboard when a users with preferences is signed in. | Run the project with a signed in users which has a preference category Technology| Should display news articles are from the technology. | https://newsapi.org/ and valid URL | Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/dashboard_test.png |
| 5 |  Signin and click and display general category news. | Run the project and sign in with a user shpowing news of general category. | News from the general category should be displayed. | Valid URL for setting pages| Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/general_test.png |    
| 6 | Updating preferences should allow users to change their preference of news articles being displayed. | Run the project and sign into a user with the category preference and then update it to another preference. | After selecting the new category user should be seeing the news articles from the new category. | Valid URL for setting pages| Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/setting_test.png |   
| 7 | Updating preferences should not show the old category. | Run the project and sign into a user with the category preference and then update it to another preference. | After selecting the new category user should no longer be seeing the news articles from the old category. | Valid URL for setting pages| Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/removeoldsetting_test.png | 
| 8 | User changes the category and only that category should display. | Run the project and sign into a user change category and display particular news of category. | After selecting the new category user should see the news articles that selected. | Valid URL for setting pages| Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/setting_test.png |
| 9 |  Sign out should return the default General category on news articles to be displayed| Run the project and sign in with a user that has a preference category that does not include general. And then sign out from that user. | News from the general category should be displayed. | Valid URL for setting pages| Joshua | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/signout_test.png | 
| 10 | User must signup with valid username and password. | Fillup the details for signup and next page will be login page. | Successfully signup and landing to login page. | https://newsapi.org/ and valid URL| Cristofer | Zal | Pass | https://github.com/CC862/CS684_Team404/blob/8b61aa665f0a8ad1e1e0a2c86c00a62f1b81b466/public/Images/signup_test.png |


  </p> 
  </details>