# Example Helm Values

## Prerequisites

* Follow Ping's [Getting Started](https://helm.pingidentity.com/getting-started/) guide.

## How to use

Edit values.yaml and enable services that you're interested in

```
helm upgrade --install <RELEASE_NAME> pingidentity/ping-devops -f values.yaml
```

## I want the vanilla helm chart values

```
helm show values pingidentity/ping-devops > values.yaml
```

## How is this example different than vanilla?

It's quite similar.  However, PingFederate and PingAccess clustering is disabled in this version.