# A flow builder for prefect 2

## Motivation
Simplify deployment of flows on prefect by using flow-builder.

Given most folks on a team are not prefect deployment experts, it is useful to have a simple way to deploy flows. 

This library makes use of the builder pattern to simplify the deployment of flows. It also provides a sample implementation of the flow builder for deploying flows to an EKS kubernetes cluster. This makes deployment of flows as simple as the interface provided by the flow builder avoid a relatively steep learning curve of prefect deployment concepts.

The flow builder also provides a simple CLI tool to deploy flows.

## How to setup

Using pip:

```bash
pip install flow_builder
```

## How to use

Create your custom flow builder by implementing the `FlowBuilderInterface` class, or use one of the implementations provided by the library.

