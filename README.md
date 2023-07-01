# iDrac temperature monitor

I am in the process to migrate the https://github.com/Breina/idrac_power_monitor script to show temperature and fan speed.

This integration will grab the temperature and fan speed from your Dell servers' iDrac system.

For this to work, the Redfish service must be running on it.

## Installation

1. Install this integration with HACS, or copy the contents of this
repository into the `custom_components/idrac_temperature` directory
2. Restart HA
3. Go to `Configuration` -> `Integrations` and click the `+ Add Integration` 
button
4. Select `iDrac temperature monitor` from the list
5. Enter the IP address or hostname (NO `http://` !) of your iDrac instance, its username (`root` by default) and its password (`calvin` by default).
