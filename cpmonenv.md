---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: IBM Cloud infrastructure, audit logs, mobile application, system events, monitoring your environment 

subcollectiom: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Monitoring your environment and system events
{: #cp_environment-events}

Monitoring your environment means that you have the ability to check on devices at any time and you're automatically notified if one of your devices goes down. You can also monitor system events to keep your systems running smoothly.  
{: shortdesc}

## Monitoring your environment
{: #cp-monitorenvi}

At a minimum, use basic ping monitoring but you can customize your monitoring options in a way that best suits your business needs.

### Staying informed of network maintenance and unplanned events
{: #cp-informedmaintenance}

From time to time, scheduled and emergency network maintenance is unavoidable. {{site.data.keyword.BluSoftlayer_full}} infrastructure maintains many channels to keep you informed of all scheduled and emergency maintenance events. Additionally, you can [subscribe to email notifications](/docs/customer-portal?topic=customer-portal-cp_bpnotifications#cp_bpnotifications) from the Event Management System. This complimentary service automatically emails subscribed users regarding unplanned events, which might impact services.

### Using {{site.data.keyword.BluSoftlayer_notm}} infrastructure mobile
{: #cp_bmxinframobile}

Use {{site.data.keyword.BluSoftlayer_notm}} infrastructure mobile to manage your {{site.data.keyword.BluSoftlayer_notm}} infrastructure devices on the go by using your iOS or Android mobile device. Functionality within {{site.data.keyword.BluSoftlayer_notm}} infrastructure mobile includes ticket support, basic device control, and bandwidth monitoring.

The {{site.data.keyword.BluSoftlayer_notm}} infrastructure mobile application compliments the functionality of the customer portal because you can monitor critical information about your infrastructure from anywhere using your network-connected mobile device. The application evolves quickly and new functionality is added regularly, but you can use the mobile application to perform tasks like the following:
  * View, create and update Support tickets
  * Monitor device status, including bandwidth and alarms
  * Shut down and restart Bare Metal Servers and virtual servers
  * View account invoices and make one-time payments
  * Access and examine content that is stored in Object Storage

The {{site.data.keyword.BluSoftlayer_notm}} infrastructure mobile application is available on several popular mobile device platforms and is available free from the related application stores for each platform.

## Monitoring servers
{: #cp_monservers}

Set up monitoring to check the status of your server and to know when to scale. You can use either standard monitoring or Nimsoft monitoring services. You can use standard, or basic, monitoring in the ping-and-respond method by using either a slow or service ping from the {{site.data.keyword.BluSoftlayer_notm}} infrastructure customer portal. You can also use Nimsoft, or advanced, monitoring from the customer portal or in 1 of 3 tiers: basic, advanced, and premium. For more information about Bare Metal servers, specifically, see [Getting started with Bare Metal servers](/docs/bare-metal?topic=bare-metal-getting-started#getting-started).

## Monitoring system events
{: #cp_monevent}

You can monitor system events by viewing audit logs and access logs.

### Viewing an audit log for an account
{: #cp_viewacctauditlog}

Each customer portal account comes with an audit log that tracks the interactions of each user within the customer portal. The following interactions, for example, are tracked:
  * Login attempts (success and failures)
  * Port speed updates
  * Power on or off and restarts
  * Interactions made by {{site.data.keyword.BluSoftlayer_notm}} infrastructure support staff.

Use the following steps to view an audit log for a user account.

1. Access the [Customer Portal ![External link icon](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window} by using your unique credentials.
2. Select **Account** > **Manage** > **Audit Log** from the navigation bar to access the audit log.

The audit log initially displays the last 25 interactions that were taken by users on the account. You can view up to 200 interactions at any time. Update the number of results that are shown from the **Display** drop-down list. If settings were changed, the **Action** column for the interaction contains a link. Click any link to view the setting that is impacted by the action and details on the change. Clicking the device name or user name for any interaction redirects you to either the device details screen or user profile screen.

### Viewing a user's access logs
{: #cp_viewuserlogs}

Access Logs display data for each access attempt that is made by a specific customer portal user. The logs display a date and time stamp and IP address for each access attempt. Use the following steps to view a user's Access Logs.

1. Access the [customer portal ![External link icon](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window} by using your unique credentials.
2. Select **Account** > **Users** from the menu bar to access the Users window.
3. From **Actions** drop-down list, select **View Audit Log** to view the user's access log.

The access log for each user displays the access attempts that were made by that user by date, along with the IP address from which the access attempt was made. Information within the access log is read-only, so edits to the content can't be made at any time. You can view the access logs again at any time by repeating the previous steps. To exit the logs and return to the Users screen, click the **View All Users** link.
