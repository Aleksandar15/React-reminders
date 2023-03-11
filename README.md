# React-reminders
##### This is not a project but rather my React best practices &amp; examples of solutions for problems I've encountered.
##### Each note may or may not be related to rest of the notes.

- `Navigate` component from React Router v6 replaces `Redirect` from previous versions, and provides more flexibility
  - `replace` prop is used to replace the current history entry instead of adding a new one. For ex.: when the user clicks the *back button* in the browser, they will be taken to the *previous page before the redirect happened* instead of going back to the page that *triggered the redirect* -> this means that the page/"*path*" where *redirect* happened will not be added to the browser history.
