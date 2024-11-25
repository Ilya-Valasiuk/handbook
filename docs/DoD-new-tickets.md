### Definition of Done for New Features/Bug Fixes

1. **Review Ticket Information**  
   - Thoroughly read all details related to the ticket.
   - Clarify any unclear aspects with relevant stakeholders.

2. **Implementation**  
   - Implement the ticket based on the established acceptance criteria.

3. **Local Testing Against Acceptance Criteria**  
   - **Web**: Test across all supported browsers for the project.
   - **Mobile**: Test on a variety of devices and versions for both iOS and Android.
   - **Backend**: Test endpoints with various payloads.

   *Note*: During the testing phase, employ critical thinking and also test negative scenarios.

4. **Prepare Pull Request (PR)**  
   - Complete the PR template and assign it to reviewers.
   - If necessary, notify the reviewers about the PR.

5. **PR Approval and Merging**  
   - After PR approval, merge it and monitor the deployment pipeline until completion. 
   - If the pipeline fails, notify the team leader and begin troubleshooting the issues.

6. **Post-Deployment Testing**  
   - Once changes are deployed to the development environment, retest all acceptance criteria.

7. **Documentation of Testing Outcomes**  
   - After all acceptance criteria have passed, comment on the ticket with detailed test results. 

   **Example Format:**

   **Web:**
   ```
   Tested on:
   - Chrome (130.0.6723.119)
   - Safari (version)
   - Firefox (version)

   Link to test: https://dev.env/new-feature-url
   ```

   **Mobile:**
   ```
   Tested on:
   - iPhone 14 Pro (iOS 17)
   - Android Galaxy 10 (v.15)

   TestFlight build: 3.0.5 (4)
   Google Play build: 3.0.5 (180)
   ```

   **Backend:**
   ```
   List of endpoints tested:
   - GET: link to dev endpoint
   - POST: link to dev endpoint

   Swagger documentation: [link to updated swagger]
   ```

8. **Ticket Transition**  
   - Move the ticket to the "Testing" column and assign it to the designated tester.
