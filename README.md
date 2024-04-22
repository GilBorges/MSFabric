# MSFabric
My own MS Fabric projects and tests

#Understand Fabric concepts: tenant, capacity, domain, workspace, and item
A Fabric tenant is a dedicated space for organizations to create, store, and manage Fabric items. There's often a single instance of Fabric for an organization, and it's aligned with Microsoft Entra ID. The Fabric tenant maps to the root of OneLake and is at the top level of the hierarchy.

Capacity is a dedicated set of resources that is available at a given time to be used. A tenant can have one or more capacities associated with it. Capacity defines the ability of a resource to perform an activity or to produce output. Different items consume different capacity at a certain time. Fabric offers capacity through the Fabric SKU and Trials.

A domain is a logical grouping of workspaces. Domains are used to organize items in a way that makes sense for your organization. You can group things together in a way that makes it easier for the right people to have access to the right workspaces. For example, you might have a domain for sales, another for marketing, and another for finance.

A workspace is a collection of items that brings together different functionality in a single tenant. It acts as a container that leverages capacity for the work that is executed, and provides controls for who can access the items in it. For example, in a sales workspace, users associated with the sales organization can create a data warehouse, run notebooks, create semantic models, create reports, etc.

Fabric items are the building blocks of the Fabric platform. They're the objects that you create and manage in Fabric. There are different types of items, such as data warehouses, data pipelines, semantic models, reports, and dashboards.

Understanding Fabric concepts is important for you as an admin, because it helps you understand how to manage the Fabric environment.

#Create a Dataflow (Gen2) in Microsoft Fabric
https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/05-dataflows-gen2.html
