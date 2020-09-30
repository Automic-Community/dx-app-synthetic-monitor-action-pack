About action pack:
	
	CA App Synthetic Monitor (CA ASM) monitors internet facing applications. With CA ASM, you monitor your applications from the end-users perspective and from several locations around the globe.
	During the release of a new application version, it may be expected that application response times are a little longer than in normal operating conditions. You hence want to avoid monitoring incidents to be created when you are rolling-out an upgrade.
	With this Action Pack for CA ASM, you can have your application upgrade procedures to automatically stop the monitoring of the application before the deployment, start it again once the upgrade is finished, and finally, validate the upgrade by confirming the application is still reachable after the upgrade.
	This Action Pack works together with the Action Pack for CA Application Performance Management, to facilitate the troubleshooting of potential performance degradations after the upgrade.

Available Actions:

	1. Activate Monitor
	2. Deactivate Monitor
	3. Get Endpoint Status
	
Supported Platforms:

	1. The Agent should be able to access CA ASM rest API endpoint URL in order to make HTTP requests.


Docker Action pack depends on

	- Automation.Engine » AutomationEngine (minimum version Automation.Engine 11.2)
	- Package.Filesystem » PCK.AUTOMIC_FILESYSTEM (minimum version Package.Filesystem 1.1)
	- Package.ITPA.Shared » PCK.ITPA_SHARED (minimum version Package.ITPA.Shared 1.1)
