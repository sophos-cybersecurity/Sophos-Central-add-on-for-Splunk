# Sophos-Central-add-on-for-Splunk

This splunk add-on helps you to add/override a [website category](https://docs.sophos.com/central/Partner/help/en-us/central/common/tasks/ConfigureWebsiteList.html) into central tenants from splunk using Sophos Central API. 

Add-on supports an adaptive response action item in Splunk Enterprise Security that you can configure in your corelation search or you can run it as an ad-hoc on any notable that gets triggered in Splunk. It does the same job as if you add a website in sophos central after login. 

This add-on is really helpful if you have policies defined in your central tenant based on website category. e.g Blocking website that are categorized as **Hacking** which will block all the websites that are categorzied as Hacking in Central.

![image](https://user-images.githubusercontent.com/65529349/125061700-3b220400-e0cb-11eb-9d35-34e845403ee6.png)
  
# Configuration

To configure this add-on to work, you will need API credentials : Client ID and Client Secret from Sophos Central. Please refer below link on how to generate API credentials for your central account:

https://developer.sophos.com/getting-started-tenant

![image](https://user-images.githubusercontent.com/65529349/125064442-4d517180-e0ce-11eb-91fb-1838f832009d.png)

Sophos Central API has three different type of accoun : Partners, organizations and tenants.  

* Partners :  A partner is a business entity, typically a Distributor, a Value Added Reseller (VAR) or a Managed Service Provider (MSP) that operates within the Sophos sales channel. A partner manages multiple "tenants" and may sell Sophos software and services to multiple "organizations".
    * API : https://developer.sophos.com/getting-started
* organizations : https://developer.sophos.com/getting-started-organization
* tenants : https://developer.sophos.com/getting-started-tenant

For Partners and Organ
