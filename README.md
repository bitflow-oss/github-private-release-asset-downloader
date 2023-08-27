# Webhook-based Github private repository release asset downloader

A webhook program that downloads release asset files from a private Github repository.

You can build the source code into an executable file, then use it as a web hook to download release assets.

Then, when almost building step finished, you can call this webhook URL using the Github Actions like below to deploy it.

https://github.com/marketplace/actions/workflow-webhook-action

Currently, it has been implemented to the release file download phase.

It would be better if someone uncompresses the downloaded zip file and adds the code to extract the assets...? :)

- Made with Go Lang + Fiber
