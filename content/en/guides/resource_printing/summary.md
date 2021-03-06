---
title: "Summaries / Raw"
linkTitle: "Summaries / Raw"
weight: 1
type: docs
description: >
    Prints Summary or Raw info of currently working resources and their states
---



{{< alert color="success" title="TL;DR" >}}
- Get a Summary of Resources Running in the Cluster
- Get or List Raw Resources in a cluster as Yaml or Json
{{< /alert >}}

# Summarizing Resources

## Motivation

Quickly summarizing a collection of Resources and their state.

Summarizing Resource State using a columnar format is the most common way to view cluster
state when developing applications or triaging issues.  The **columnar view gives a compact
summary of the most relevant information** for a collection of Resources.

## Get

The `kubectl get` reads Resources from the cluster and formats them as output.  The examples in
this chapter will query for Resources by providing Get the *Resource Type* as an argument.
For more query options see [Queries and Options]().

{{< alert color="success" title="Note" >}}
Check out the [References](../../../references) to learn how to print Summary of Resources Running in the Cluster
{{< /alert >}}


