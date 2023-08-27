# Webhook-based Github private repository release asset downloader
The release asset downloader in the Github private repository. 

You may build this to native excutable then use this as asset download Web Hook API, 

then call this Web Hook URL from some of Github Actions like below.

https://github.com/marketplace/actions/workflow-webhook-action

Currently, just implemented to download release file step.

If add some additional code to extract asset zip file, it would be better.

- Made with Go Lang + Fiber.
