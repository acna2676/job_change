fields @timestamp, @message
| sort @timestamp desc
| filter @message like /takashi.ishikawa/
