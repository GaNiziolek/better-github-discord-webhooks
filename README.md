# Better GitHub Discord Webhooks
Discord doesn't recognize all the GitHub webhook events, let's change this.

# Why?
For those who use Discord to communicate with team members, is very helpful to receive GitHub notifications about all the things that occur on a repo.
The [webhook functionality on Github](https://docs.github.com/en/webhooks) can send requests for many events, these webhooks can be sent to a Discord room, as [shown in this gist](https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22).

But Discord handles only a few GitHub events, [and is not planned to support more than these](https://github.com/discord/discord-api-docs/issues/6203#issuecomment-1608151265). So we need some middleware that receives GitHub events and formats them into a beautiful Discord message.

This is what this project is about.

# How?
To be defined.
