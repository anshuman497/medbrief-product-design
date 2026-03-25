# Edge Cases – MedBrief (along with solutions)

## 1. Authentication

* Incorrect email/password → Show error message
* OTP expired → Allow resend OTP
* Multiple failed login attempts → Temporary account lock
* Social login failure → Fallback to email login
* Network failure during login → Retry option

## 2. Onboarding

* User skips onboarding → Assign default preferences
* No specialty selected → Prompt mandatory selection
* No interests selected → Show generic content feed
* Notification permission denied → Show reminder later

## 3. Home Dashboard

* No data available → Show "No updates available" state
* Audio not loading → Show retry option
* Slow internet → Show loading skeleton

## 4. Research Search

* No results found → Suggest alternative queries
* Filters too restrictive → Show "Clear Filters" option
* Search typo → Show auto-suggestions
* API failure → Show error + retry

## 5. Study Detail

* Missing study data → Show partial content with warning
* Audio unavailable → Disable audio button
* Broken DOI link → Show fallback message

## 6. Notifications

* Notification clicked but content deleted → Show "Content no longer available"
* Duplicate notifications → Merge or suppress
* User disables notifications → Stop push but keep in-app alerts

## 7. Bookmark

* Duplicate bookmark → Prevent duplication
* Offline save → Sync when online
* Removed study → Remove from bookmarks automatically

## 8. Audio Player

* Audio download fails → Retry option
* Playback interrupted → Resume from last position
* Speed not supported → Fallback to default speed

## 9. General

* App crash → Show graceful restart option
* No internet → Show offline mode (limited functionality)
* Data sync issue → Retry mechanism
