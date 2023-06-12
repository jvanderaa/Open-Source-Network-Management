# Open Source Network Management

This is the code components used throughout the book - [Open Source Network Management](https://leanpub.com/opensourcenetworkmanagement/). The book is all about getting up and started using _open source_ projects and tools to manage your network. Get your copy of the book today walking through the rest of it!

This at the moment is a very raw source of files. It is what was used to build out the environments. I will look to fix and organize the environment to make it easier to consume.

## Tools Covered in the Book

* Nautobot
* Hashicorp Vault
* Prometheus
* Alertmanager
* Telegraf
* Grafana

## Loading the Environment

There is a `setenv.sh` command that has been loaded. It loops over the environment files (`.env`) that are in the directory and loads these. The files have `export` in them to be used with the script itself.