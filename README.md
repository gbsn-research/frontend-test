# **GBSN Test Requirements and Analysis**

### Set-Up Instructions

Clone this repository and use a local hosting service like Node, Nginx or Apache.

### Project info

| Start Date | Finish Date | Project Name |
| --- | --- | --- |
| 2019 | 2019 | Front-End |

### Project Summary

In this application assessment test for GBSN Research, we ask you to fill out a project with information from the following API @ https://adcaller.com

### Project Description Q&A

Q: What does this Project entail?  
A: It is related to another Project being developed. Its main purpose is to display metrics from a Brand.

Q: How big is the Project?  
A: The project is only composed by a single page.

Q: What is the goal of this page?  
A: This page should display Brand Mentioned Social Posts to a Brand user. It should also provide details on the mentioned posts and some insight on the users who most tag the Brand.

Q: What are Brand Mentioned Social Posts?  
A: On this project iteration there are two types of users, standard Users and Brands. After connecting their social media accounts like Facebook or Instagram, Users get their social posts from the Facebook Graph API and are able to mention Brands in each post, inside the app. Brands can then see the social media posts they were tagged in, and by whom were they tagged.

Q: What are the Brand Top Mentioners?  
A: The Brand top 5 Mentioners are the standard Users who most tagged a brand in their posts.

Q: What technologies are required?  
A: We like to be open minded and give the opportunity of working in what you think is best. That being said, we also value usability, technologies that are more up-to-date and popular are more valued, i.e., React.

### Project Description Tasks

| Task | Task info | Notes | Points   (0-200)
| --- | --- | --- | --- |
| Posts | Fill Brand Mentioned Social Posts. | There is a specific API call for this*.| 60 |
| Post Metrics | Fill Brand Mentioned Social Posts Metrics. | Include the social metrics of said Posts. | 5 |
| User Metrics | Fill the User metrics | Include the User Social Metrics, reach and engagement. | 15 |
| Other Mentions | Inside the Metrics Show other mentioned Brands. | Include Other brands who also mentioned this post. | 30 |
| Sort | Sort Posts by post created date and by user who created (displayname). | Use API Sort parameters to Sort the Results. | 10 |
| Filter | Filter posts by all, Facebook and Instagram. | Use API social parameter to Filter the results. | 10 |
| Search | Search User who created (displayname) | Use API search parameters to filter the results. | 10 |
| Scroll | Use Pagination to achieve a scroll Load. 4 each load| Use API pagination for this task. | 20 |
| Top Mentioners  | Show top 5 mentioners of the brand by most mentions. | Use API mentions for the specific /brand/me and calculate in Front-End.** | 40 |

*https://adcaller.com/brands/me/mentioned_social_posts    
**https://adcaller.com/brand/me/mentions


### Notes

- Documentation: [https://adcaller.com](https://adcaller.com)
- /brands/me  will return the Brand used for Testing (same as /brand/Z2EfoOUFQJVs39lg)
- Relation List are in the Documentation Schemas at the end of the documentation
- Scroll Load Pagination: 4 Posts with load when the Scroll reaches the Bottom load the next 4 and so on.
- Share Button should redirect to the Social URL of the User.

### Contact Info

Feel free to contact us at anytime, we are usually avaiable from 8:00 to 18:00 GMT+1 monday to friday.

Skype & Email: david.cruz@gbsnresearch.com or info@gbsnresearch.com

### Delivery

The Project must have instructions on how to execute, along with a small Functional Specification File describing how the code works.

When you finish, you can deliver your Project by sending an email to [david.cruz@gbsnresearch.com](mailto:david.cruz@gbsnresearch.com) with either a .zip of the project or a git repository. We will contact you soon after.
