# BBB Learning Analytics Dashboard Notifier

A BigBlueButton post-script to send the learning analytics dashboard URL to a callback

## Installation

1. Move `post_events_analytics_url_callback.rb` to `/usr/local/bigbluebutton/core/scripts/post_events` directory.
2. Run `sudo bbb-conf --restart`

You should set `analytics-callback-url` metadata value for your meetings to let the script work.
