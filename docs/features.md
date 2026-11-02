# Features and page access

Utopia is a quiz-gated social media platform. This page lists the main pages and whether a visitor needs to log in.

## Accounts

| Page | URL | Login needed |
|---|---|---|
| Home | `/` | No |
| Quiz | `/accounts/quiz/` | No |
| Register (after passing the quiz) | `/accounts/register/` | No |
| Login | `/accounts/login/` | No |
| My profile | `/accounts/profile/` | Yes |
| People list | `/accounts/people/` | Yes |

## Posts

| Page | URL | Login needed |
|---|---|---|
| Feed | `/posts/feed/` | Yes |
| Create post | `/posts/create/` | Yes |
| Post detail | `/posts/post/<id>/` | No |
| Comment, like, edit, delete | `/posts/post/<id>/...` | Yes |
| Follow a user | `/posts/profile/<id>/follow/` | Yes |
| A user's posts | `/posts/profile/<id>/` | No |
| Emergency feed | `/posts/emergency/` | No |
| Search | `/posts/search/` | No |
| Ask a question | `/posts/ask/` | Yes |
| Question list and detail | `/posts/questions/` | Yes |

## FundMe (funding)

| Page | URL | Login needed |
|---|---|---|
| Campaign list | `/funding/` | No |
| Campaign detail | `/funding/<id>/` | No (donating needs login) |
| Create, edit, delete a campaign | `/funding/create/`, `/funding/<id>/edit/`, `/funding/<id>/delete/` | Yes |

## How it fits together

- A visitor takes the quiz first. A score of 60% or more unlocks registration.
- Posts marked as emergencies appear in the emergency feed.
- Every donation updates the campaign's collected amount and progress.