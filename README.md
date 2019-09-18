# **GBSN Test Requirements and Analysis**

### Setup Instructions

Simply Clone this repository and use a local hosting service like Node, Nginx or Apache.

### Project info

| Start Date | Finish Date | Project Name |
| --- | --- | --- |
| 2019 | 2019 | Front-End |

### Project Summary

As an application test to GBSN Research, we require you to fill a project with information from an API @ https://adcaller.com

### Project Description Q&A

Q: What is the Project about?  
A: It is related to another Project being developed. Its main focus is displaying metrics from Brands.

Q: How big is the Project?  
A: The project is composed only by a single page.

Q: What is the goal of this page?  
A: This page should display Brand Mentioned Social Posts to a Brand user. It should also provide details on the mentioned posts and some insight on the users who most tag the Brand.

Q: What are the Brand Mentioned Social Posts?  
A: On this project iteration there are two types of users, standard Users and Brands. After connecting their social media accounts like Facebook and Instagram, Users get their social posts retrieved from the Facebook Graph API and are able to mention Brands in each post, inside the app. Brands can then see the social media posts they were tagged in and whom were they tagged by.

Q: What are the Brand Top Mentioners?  
A: The Brand top 5 Mentioners are the standard Users who most tagged a brand in their posts.

Q: What technologies are required?  
A: We like to be open minded and give the opportunity of working in what you think is best. That being said, we also value usability, technologies that are more up-to-date and popular are more valuable. Technologies like React are highly regarded.

### Project Description Tasks

| Task | Task info | Notes |
| --- | --- | --- |
| Posts | Fill Brand Mentioned Social Posts. | There is a specific API call for this*.|
| Post Metrics | Fill Brand Mentioned Social Posts Metrics. | Include the social metrics of said Posts. |
| Other Mentions | Inside the Metrics Show other mentioned Brands. | Include Other brands who also mentioned this post. |
| Sort | Sort Posts by post created date and by user who created (displayname). | Use API Sort parameters to Sort the Results. |
| Filter | Filter posts by all, Facebook and Instagram. | Use API social parameter to Filter the results. |
| Search | Search User who created (displayname) | Use API search parameters to filter the results. |
| Scroll | After being logged in, show a page with a message. | Use API pagination for this task. |
| Top Mentioners  | Show top 5 mentioners of a brand by most mentions. | Use API mentions for the specific brand and calculate in Front-End. |

*https://adcaller.com/brand/me/mentioned_social_posts 


### Notes

- Documentation: [https://adcaller.com](https://adcaller.com)
- /brands/me  will return the Brand used for Testing (same as /brand/Z2EfoOUFQJVs39lg)
- Relation List are in the Documentation Schemas at the end of the documentation

### Delivery

The Project must have instructions on how to execute and a small Functional Specification File describing the code works.

When you are finished you can deliver by sending an email to [david.cruz@gbsnresearch.com](mailto:david.cruz@gbsnresearch.com) with either a .zip of the project or a git repository. We will contact you soon after.