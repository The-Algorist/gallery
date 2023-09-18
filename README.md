# gallery app jenkins pipeline build
# Milestone 1: Set up

- Forked and cloned the repo, an already working application that will be translated into a cloud-based application.
- The application uses a database that must be considered. For deployment on Render with MongoDB, MongoDB Atlas, a cloud-hosted MongoDB service, is used.
- Followed a short video tutorial to set up MongoDB Atlas.
- Created a cluster and database user on MongoDB Atlas, then updated the `_config.js` file with the username and password for the user.

# Milestone 2: Basic pipeline

- Noticed that the repository lacks tests but built a pipeline.
- Created a JenkinsFile with required instructions.
- Configured the pipeline to trigger automatically on new changes.
- Ensured the pipeline installs necessary software and dependencies using `npm install`.
- Made changes to the landing page, adding a prominent "MILESTONE 2."
- Pushed changes and confirmed the Render site displayed "MILESTONE 2."

# Milestone 3: Tests

- Discovered tests in a different branch named "test."
- Switched to the "test" branch and ran tests using `npm test`.
- Merged the "test" branch with the main branch.
- Updated the JenkinsFile to include test execution.
- Configured the pipeline to send an email on test failure.
- Made changes to the landing page, adding a noticeable "MILESTONE 3."
- Pushed changes and confirmed the Render site displayed both "MILESTONE 2" and "MILESTONE 3."

# Milestone 4: Slack integration

- Explored integrating Jenkins with Slack.
- Created a Slack channel named `[MyFirstName]_IP1` and invited the team member.
- Updated the pipeline to send a Slack message on successful deployment, including build ID and Render link (using environment variables).
- Made changes to the landing page, adding a visible "MILESTONE 4."
- Pushed changes and confirmed the Render site displayed "MILESTONE 2," "MILESTONE 3," and "MILESTONE 4."

- 
![Instructions](https://github.com/The-Algorist/gallery/assets/83602292/3c843933-4a22-43df-81d6-f8d4510b2cbd)

# Conclusion

Excited to have completed the first IP! Learned about building pipelines, integrating Jenkins with other tools, and deploying applications to the cloud. Looking forward to more software engineering challenges and projects in the future.
