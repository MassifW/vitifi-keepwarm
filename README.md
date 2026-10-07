# vitifi-keepwarm

One scheduled job that asks VITIFI's public `/api/ping` a question every
5 minutes through the New Zealand working day, so its server is rarely
asleep when someone opens the app. Nothing secret is in here. Why it
lives in its own repository is in the workflow's header.

GitHub switches scheduled jobs off after 60 days without any activity in
a public repository; if the first request of the morning is slow again,
open the Actions tab and re-enable it.
