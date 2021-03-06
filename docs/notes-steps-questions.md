Question:
1. What exact information of users should be displayed on the home page
1. We will need a wireframe of the homepage.. Just an idea, we can come up with the rest of the information.
1. Are we paying attention to the GitHub API limitations listed here https://github.com/cncf/devstats/blob/master/ARCHITECTURE.md#github-archives ?
1. What is the best data to display to show users that the project is popular and "hot"?


Next Steps:
1. Create a sketch of the views to use as a basline for wireframing
1. Find a designer to help with better wireframes
1. Gather API specs for all the data we want to display
1. Create a user journey
1. Ige & Rosalind do a short meeting to discuss backend next steps
1. Test consuming API calls on the events in the events list, and compare results to what we see in DevStats, and determine whether the results will meet our needs
1. Based on API output/testing, Ige will begin creating the database schema
1. Vishal will be working on React JS, pairing with Nikema, so he can begin once the API spec is done
1. Kuti & Nikema create HTML/CSS wireframe
1. Rosalind will check for CDF brand guide and give Kuti guidance on branding
1. Ige will re-add collaborators to calendar invite
1. Kuti will create a basic brand guide if needed
1. All will connect to collaborate async on Slack in [our Slack channel](https://spinnakerteam.slack.com/archives/C019EV8HA7Q)
1. Test API behavior in cases where users make commits that are components of Pull Requests submitted by other users. Can we reliably count commits and present an all-time total of merged and/or submitted commits?

Notes:
What APIs can we start consuming? Once you have the token set up it's pretty easy. Ige is going to check out DevStats and see what we can borrow. At this point, the plan is to use APIs where possible and githubarchive where not possible.

2 options:


Here is the usage information from Lukaz on how he pulls and processes the data for DevStats https://github.com/cncf/devstats/blob/master/USAGE.md
