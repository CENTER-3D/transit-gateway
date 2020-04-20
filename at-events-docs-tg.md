---

copyright:
  years: 2020
lastupdated: "2020-04-16"

keywords: transit gateway, activity tracker, LogDNA, event, security

subcollection: transit-gateway

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank_"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:download: .download}
{:term: .term}

# Activity Tracker events for {{site.data.keyword.tg_full_notm}}
{: #at_events}

As a security officer, auditor, or manager, you can use the Activity Tracker service to track how users and applications interact with the {{site.data.keyword.tg_full}} service in {{site.data.keyword.cloud_notm}}.
{: shortdesc}

{{site.data.keyword.at_full_notm}} records user-initiated activities that change the state of a service in {{site.data.keyword.cloud_notm}}. You can use this service to investigate abnormal activity and critical actions and to comply with regulatory audit requirements. In addition, you can be alerted about actions as they happen. The events that are collected comply with the Cloud Auditing Data Federation (CADF) standard. For more information, see the [getting started tutorial for {{site.data.keyword.at_full_notm}}](/docs/Activity-Tracker-with-LogDNA?topic=logdnaat-getting-started#getting-started).

## List of events: Gateway resources
{: #at_events_list}

The following actions generate events for IBM Cloud Transit Gateway:

| Action             | Description      |
|:-------------------|:-----------------|
| transit.gateway.create | Create a transit gateway     |
| transit.gateway.delete | Delete a transit gateway     |
| transit.gateway.update | Update a transit gateway     |
| transit.connection.create | Create a transit gateway connection   |
| transit.connection.delete | Delete a transit gateway connection   |
| transit.connection.update | Update a transit gateway connection   |
{: caption="Table 1. Actions that generate events for transit gateways" caption-side="top"}

## Viewing events
{: #at_ui}

Events are available in the **Dallas** location (`us-south`) region only. {{site.data.keyword.at_full_notm}} can have only one instance per location.

You can view events by accessing the web UI of the {{site.data.keyword.at_full_notm}} service in the `us-south` region. For more information, see [Launching the web UI through the IBM Cloud UI](/docs/Activity-Tracker-with-LogDNA?topic=logdnaat-launch#launch_step2).
