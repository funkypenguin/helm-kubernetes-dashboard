![Lint and Test Charts](https://github.com/funkypenguin/helm-kubernetes-dashboard/workflows/Lint%20and%20Test%20Charts/badge.svg?branch=master)

[cookbookurl]: https://geek-cookbook.funkypenguin.co.nz
[kitchenurl]: https://discourse.geek-kitchen.funkypenguin.co.nz
[discordurl]: http://chat.funkypenguin.co.nz
[patreonurl]: https://patreon.com/funkypenguin
[blogurl]: https://www.funkypenguin.co.nz
[githuburl]: https://github.com/funkypenguin
[sponsorurl]: https://github.com/sponsors/funkypenguin

[![geek-cookbook](https://raw.githubusercontent.com/funkypenguin/www.funkypenguin.co.nz/master/images/geek-kitchen-banner.png)][cookbookurl]

- [What is funkypenguin/helm-kubernetes-dashboard?](#what-is-funkypenguinhelm-kubernetes-dashboard)
- [How do I use funkypenguin/helm-kubernetes-dashboard?](#how-do-i-use-funkypenguinhelm-kubernetes-dashboard)
- [Where to get help?](#where-to-get-help)


---

This helm chart is maintained with ❤️ by [@funkypenguin][githuburl], internet-famous for creating [Funky Penguin's Geek Cookbook][cookbookurl].

[Funky Penguin's Geek Cookbook][cookbookurl] is a collection of "recipes" to run popular applications
on Docker Swarm or Kubernetes, in a cheeky, geeky format.

Got more details at:
* ![Discourse with us!](https://img.shields.io/discourse/https/discourse.geek-kitchen.funkypenguin.co.nz/topics.svg) [Forums][kitchenurl]
* ![Chat with us!](https://img.shields.io/discord/396055506072109067.svg) [Friendly Discord Chat][discordurl]
* ![Geek out with us!](https://img.shields.io/badge/recipies-37+-brightgreen.svg) [Funky Penguin's Geek Cookbook][cookbookurl]
* ![Thank YOU](https://img.shields.io/badge/thank-you-brightgreen.svg) [Patreon][patreonurl]
* ![Read blog!](https://img.shields.io/badge/read-blog-brightgreen.svg) [Blog][blogurl]

# What is funkypenguin/helm-kubernetes-dashboard?

This helm chart is an adaption of the original https://github.com/helm/charts/tree/master/stable/kubernetes-dashboard to support [Kubernetes Dashboard](https://github.com/kubernetes/dashboard) version 2. There are some significant differences between version 1 and version 2, one of which being that Heapser is no longer required, but metrics-server is.

![Kubernetes Dashboard v2 screenshot](https://static.funkypenguin.co.nz/Kubernetes_Dashboard_2020-03-25_19-39-11.png)

# How do I use funkypenguin/helm-kubernetes-dashboard?

Add the repo to helm, like this:

`helm repo add funkypenguin-kubernetes-dashboard https://funkypenguin.github.io/helm-kubernetes-dashboard/`

Create a namespace (e.g. `kubectl create namespace kubernetes-dashboard`)

And then install kubernetes-dashboard with something like:

`helm install -n kubernetes-dashboard kubernetes-dashboard kubernetes-dashboard`

# Where to get help?

There are hot, sweaty geeks ready to help you out, at:

* ![Discourse with us!](https://img.shields.io/discourse/https/discourse.geek-kitchen.funkypenguin.co.nz/topics.svg) [Forums][kitchenurl]
* ![Chat with us!](https://img.shields.io/discord/396055506072109067.svg) [Friendly Discord Chat][discordurl]

