---

copyright:
  years: 2020
lastupdated: "2020-01-28"

keywords: transit, gateway, iam, permissions

subcollection: transit-gateway

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:download: .download}
{:term: .term}

# Using IAM permissions with IBM Cloud Transit Gateway
{: #iam}

{{site.data.keyword.tg_full}} uses IBM Cloud Identity and Access Management (IAM) platform access roles to manage access to the service's resources. IAM access roles allow account administrators to assign different levels of permission for using the service. The following tables provide the list of actions that you can take against the {{site.data.keyword.tg_full_notm}} service and its resources depending on a user's assigned roles.

## Platform-access roles
{: #platform-access-roles}

{{site.data.keyword.tg_full_notm}} supports Viewer, Operator, Editor, and Administrator platform-access roles.

| Role | Description of Actions |  Actions |
|---|---|---|
| Viewer and Operator | Performs actions that don't change the state of resources. |<ul><li>List gateways</li><li>Get gateways</li><li>List a gateway's connections</li><li>View a gateway's connections</li></ul>
| Editor | Performs all actions, including managing gateways and connections. |<ul><li>Create gateways</li><li>Delete gateways</li><li>Edit gateways</li><li>Add or remove gateway connections &#10045; </li><li>Edit gateway connections
| Administrator | Performs all actions, including managing gateways and connections. Allows a user to assign {{site.data.keyword.tg_full_notm}} IAM access policies to other users. | <ul><li>Create gateways</li><li>Delete gateways</li><li>Edit gateways</li><li>Add or remove gateway connections &#10045; </li><li>Edit gateway connections</li><li>Update user access policies for the service |                     |
{: caption="Table 1. IAM platform-access user roles and actions" caption-side="top"}

&#10045; To add or remove connections to VPCs, the user must have Editor or Administrator platform-access role permissions on the VPC. See [VPC: Getting started with IAM](/docs/vpc?topic=vpc-iam-getting-started) for more information.
