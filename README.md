## StackExchange Remake

This application is a remake of a Stack Exchange Network site, using Ruby, Rails, Materialize, Devise, Redcarpet, and other Rails plugins.

Things that this will include soon:
- Questions
  - Writing in Markdown
  - Answering
  - Vote up, down
  - Deleting while remaining in DB
  - Undeleting
- Answers
  - Writing in Markdown
  - Vote up, down
  - Accepting
  - Commenting on
  - Deleting while remaining in DB
  - Undeleting
- Comments
  - Voting up only
  - No editing
  - Deleting
- Voting (once, then it's locked in)
- Users
  - Reputation
  - Profile
  - List of questions posted
 
Things that this will include eventually:
- Categories
- Flagging
- Editing questions/answers
- Reputation thresholds for actions (probably using `cancancan`)
- Full edit history?
  - How to implement?

Things that this will probably never include:
- Winter bash
- Chat
- Meta site (just run a second instance?)
- Automated spam detection
- Review queues
- Badges
- Image hosting/uploads