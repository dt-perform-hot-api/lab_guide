## Preparation

During this hands on section, we will cover:
1. Web Application API
2. App detection rules API
3. Auto Tagging rules API


Projects used for this session
- [NodeJS](https://nodejs.org/)
- [Dynatrace API ](https://www.dynatrace.com/support/help/dynatrace-api)


Access your Dynatrace environment at www.dynatrace.com and click 'SaaS login'.

Use your HOT session credentials to login to your tenant.

### Setup
#### Management Zone
- We need to create a management zone that we can use later as an SLO filter criteria.
- For this scenario, we will use a very simple management zone that simply checks if a service name exists. 
1. In your tenant, navigate to Settings > Preferences > Management Zones
2. Click the button 'Add new management zone'
3. Name this management zone 'Services' and leave the optional description field blank. 
4. Click the 'Add a new rule' button.
5. Under conditions, click the drop-down and select 'Service name'. Next, select the drop-down menu to the right of Service Name and select 'exists'.
6. Apply to both underlying hosts and process groups of the matching services.
7. Finally, preview your changes and make sure services and hosts show up in the preview section. Your final rule should look like the example image below.
</br></br>

![Example Management Zone](../../assets/simple_management_zone.png)