# Webhook-based Github private repository release asset downloader

A webhook program that downloads release asset files from a private Github repository.

You can build the source code into an executable file, then use it as a web hook to download release assets.

Then, when almost building step finished, you can call this webhook URL using the Github Actions like below to deploy it.

https://github.com/marketplace/actions/workflow-webhook-action

Currently, just implemented to download release file step.

If add some additional code to extract asset zip file, it would be better.

There may be some bugs, but if it's a non-mission-critical system, wouldn't it be okay?

Anyway, I'll update it soon.

- Made with Go Lang + Fiber
