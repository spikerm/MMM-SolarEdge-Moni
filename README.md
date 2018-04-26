# MMM-SolarEdge
A Solar Module for MagicMirror2 designed to integrate with an SolarEdge inverter 

## Dependencies
  * A [MagicMirror<sup>2</sup>](https://github.com/MichMich/MagicMirror) installation

## Installation
  1. Clone repo into MagicMirror/modules directory
  2. Get an SolarEdge API key and authorize your application 
  3. Create an entry in 'config/config.js' with your API Key, UserId, SystemID, and any config options.

 **Example:**
```
 {
    module: 'MMM-SolarEdge',
	position: 'bottom_left',
	config: {
		apiKey: "################################", //Requires your own API Key
		userId: "4d7a45774e6a41320a", //Enphase example user
		systemId: "67", //Enphase example system
	}
 },
```
**Note:** Only enter your API Key in the `config.js` file. Your API Key is yours alone, _do not_ post or use it elsewhere.

## Sample
![alt text](https://github.com/spikerm/MMM-SolarEdge-Moni/blob/master/AppSample.PNG "Example")

## Optional Config
| **Option** | **Description** |
| --- | --- |
| `basicHeader` | Set to `true` to substitute the 'Solar PV' text and graphic for the default MagicMirror header |

## API Key
Use of this module requires
  1. An API Key, which you can obtain from installer 
  2. The User Id of the User whose system you wish to integrate. This can be found in your Monitoring Portal(https://monitoring.solaredge.com).
  3. The System ID of the solar system you wish to monitor, which can also be found in the Monitoring Portal.

## Attribution

