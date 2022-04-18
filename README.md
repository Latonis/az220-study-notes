# az220-study-notes
This repository contains all of my notes and study material while preparing for [AZ-220: Azure IoT Developer Specialty](https://docs.microsoft.com/en-us/learn/certifications/azure-iot-developer-specialty/)

# Labs
- [Microsoft Learning AZ-220 Labs | Github](https://microsoftlearning.github.io/AZ-220-Microsoft-Azure-IoT-Developer/)
# Videos
- [Az-220 Exam Cram](https://www.youtube.com/watch?v=BD3vSVQqjVQ)
- [Azure IoT Hub device SDK for Python](https://www.youtube.com/watch?v=vDaP9t-TTs8)
# Modules
- [x] [Create Azure IoT services in the Azure portal](https://docs.microsoft.com/en-us/learn/paths/create-azure-iot-services-azure-portal/)
- [ ] [Implement IoT device communication by using the Azure IoT SDKs](https://docs.microsoft.com/en-us/learn/paths/implement-iot-device-communication-by-using-azure-iot-sdks/)
- [ ] [Provision IoT devices at scale by using the Device Provisioning Service](https://docs.microsoft.com/en-us/learn/paths/provision-iot-devices-scale-use-device)
- [ ] [Implement device message processing and data analytics](https://docs.microsoft.com/en-us/learn/paths/implement-device-message-processing-data-analytics/)
- [ ] [Develop data insights and business integrations](https://docs.microsoft.com/en-us/learn/paths/develop-data-insights-business-integrations/)
- [ ] [Deploy Azure IoT Edge devices and modules](https://docs.microsoft.com/en-us/learn/paths/deploy-azure-iot-edge-devices-modules/)
- [ ] [Develop and deploy custom IoT Edge modules](https://docs.microsoft.com/en-us/learn/paths/develop-deploy-custom-iot-edge-modules/)
- [ ] [Manage IoT devices by using IoT Hub and apps](https://docs.microsoft.com/en-us/learn/paths/use-iot-hub-apps-manage-iot-devices/)
- [ ] [Monitor and troubleshoot an IoT solution by using Azure Monitor](https://docs.microsoft.com/en-us/learn/paths/monitor-troubleshoot-iot-solution-by-using-azure-monitor/)
- [ ] [Enhance IoT solution security by using Azure Defender for IoT](https://docs.microsoft.com/en-us/learn/paths/enhance-iot-solution-security-by-using-azure-defender/)
- [ ] [Extend IoT solutions by using Azure Digital Twins](https://docs.microsoft.com/en-us/learn/paths/extend-iot-solutions-by-using-azure-digital-twins/)
- [ ] [Build low touch IoT solutions by using Azure IoT Central](https://docs.microsoft.com/en-us/learn/paths/build-low-touch-iot-solutions-by-using-azure-iot-central/)

# Notes

## Monitor and troubleshoot an IoT solution by using Azure Monitor
### Examine Azure IoT solution monitoring and logging
#### Azure Monitor Support
Azure IoT Hub service uses Azure Monitor and Log Analytics to support IoT solution diagnostics and troubleshooting.
- Azure Monitor allows for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

##### Examples
- Detect and diagnose issues across applications and dependencies with Application Insights.
- Correlate infrastructure issues with Azure Monitor for VMs and Azure Monitor for Containers.
- Drill into your monitoring data with Log Analytics for troubleshooting and deep diagnostics.
- Support operations at scale with smart alerts and automated actions.
- Create visualizations with Azure dashboards and workbooks.

##### Tiers
There are multiple tiers of data used in Azure Monitor:
- Application monitoring data
- Guest OS monitoring data
- Azure resource monitoring data
- Azure subscription monitoring data
- Azure tenant monitoring data

##### Alerts 
You can alert on metrics and logs:
- Metric values
- Log search queries
- Activity log events
- Health of the underlying Azure platform
- Tests for website availability

##### Key Alert Attributes
- Target Resource
- Signal
- Criteria
- Alert Name
- Alert Description
- Severity
  - Sev 0 = Critical
  - Sev 1 = Error
  - Sev 2 = Warning
  - Sev 3 = Informational
  - Sev 4 = Verbose
- Action