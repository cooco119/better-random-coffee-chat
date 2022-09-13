# better-random-coffee-chat

Better Random Coffee Chat is a slack app for a better random coffee chat for a small to mid sized team!

## Features

I tried to improve inconvenient experience while using conventional random free coffee chat slack app by follwings.

- Better random matching

  - Match coffee chat pair who were rarely matched past.

  - Try pick the greatest scored pair, and the score is calculated by

    - Match history counts, lower the count, higher the score.
    - Teams (different team == more score)
    -

- Matching history report

- Random coffee chat reminder

  - When you are assigned a pair, slackbot DMs to you about your pair
  - (Nice To Have) Schedule a random time: reads your calender and pick available time for both and make an schedule
  - If not done, remind everyday 12 o'clock.
  - If done, you can click `done` button to let the app know you finished your coffeechat.
  - If you're not available, you can click `skip` button to send your pair that you are not available this week and set

- slash commands

  - `/mix`: re-pick all coffee chat pairs
  - `/delete userA groupOne`: delete userA from groupOne
  - `/add userA groupTwo`: add userA to groupTwo
  - `/move userA groupThree`: move userA from original group to groupThree
  - `/coffee-was-yummy`: Set that you have done coffee chat, same as clicking `done` button on DM
  - `/not-this-week`: Skip this week's coffee chat, same as clicking `skip` button on DM
