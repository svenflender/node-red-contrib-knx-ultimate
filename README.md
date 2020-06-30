![Logo](img/logo-big.png)

<br/>

[![NPM version][npm-version-image]][npm-url]
[![NPM downloads per month][npm-downloads-month-image]][npm-url]
[![NPM downloads total][npm-downloads-total-image]][npm-url]
[![MIT License][license-image]][license-url]
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

![Sample Node](img/readmemain.png)

**You can use it immediately!**
```javascript
node.send{payload:true} // Turn light on
node.send{payload:{red:255, green:200, blue:30}} // Put some colors in our life
```

## DESCRIPTION

* **KNX-ULTIMATE node** [here](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/2.-Node-Configuration), allow you to control your *KNX installation* via Node-Red. You can control all your KNX devices as well as create a *Virtual Device* in Node-Red, to link external *non KNX* devices, and make it compatible with your KNX installation. I'ts very SIMPLE TO USE thus very customizable.  
* **SCENE CONTROLLER node** [here](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/SceneController-Configuration), The scene controller node can act as a real scene controller, with recall and save of the current scene.
* **WATCHDOG node** [here](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/7.-WatchDog-Configuration), allows notification (Email, Twitter, Telegram, Alexa, Siri, Sonos -with sonospollytts node- and so on) of KNX Bus connection errors, automatic or manual switchover to a backup KNX/IP router if the primary fails and allows you to programmatically change the config-node directly from a msg flow.
* **LOGGER node** [here](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/Logger-Configuration), creates an XML diagnostic file, compatible with ETS. You can open it with ETS for diagnostic pourposes.

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg?style=flat-square)](https://www.paypal.me/techtoday) and <a href="http://eepurl.com/gJm095" target="_blank">subscribe to my channel.</a> Only news about my nodes, no spam, no ads.

## CHANGELOG
* See <a href="https://github.com/Supergiovane/node-red-contrib-knx-ultimate/blob/master/CHANGELOG.md">here the changelog</a>

## INTERNATIONALIZATION
<img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/wiki/flags/europe.png"/><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/wiki/flags/uk.png"/><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/wiki/flags/usa-today.png"/><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/wiki/flags/germany.png"/><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/wiki/flags/italy.png"/><br/>
*I'm internationalizing the node **(Deutsch, Italiano, English)** with the foundamental help of **@svenflender**, so please be patient if some parts are still only in english. Internationalization is working with node-red version 1.0.3 and above. Versions below, does have issues in the i18n module, so knx-ultimate falls back to english. Please upgrade node-red.*

## TROUBLESHOOT, WIKI, FAQ, BEST PRACTICES AND SAMPLES
* [Youtube video](https://www.youtube.com/channel/UCA9RsLps1IthT7fDSeUbRZw)
* [Overview](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki)
* [Changelog](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/blob/master/CHANGELOG.md)
* [FAQ + Troubleshoot](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/5.-FAQ-Troubleshoot)
* [Security best practices](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/blob/master/SECURITY.md)
* *SAMPLES*
  * [Sample Switch Light](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Switch-light)
  * [Sample Dimming](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Dimming)
  * [Sample RGB color](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---RGB-Color)
  * [Sample Command a scene actuator](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Control-a-scene-actuator)
  * [Sample Datetime to BUS](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---DateTime-to-BUS)
  * [Sample Read Status](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Read-value-from-Device)
  * [Sample Virtual Device](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Virtual-Device)
  * [Sample Subtype decoded](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Subtype)
  * [Sample Scene Controller](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/Sample-Scene-Node)
  * [Sample WatchDog](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---WatchDog)
<table>
  <tr>
    <td>Sample code for use with </td>
    <td valign="center" height="60"><a href="https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Apple-Homekit"><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/homekit.png" ></a></td>
    <td valign="center" height="60"><a href="https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Alexa"><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/alexa.png" ></a></td> 
    <td valign="center" height="60"><a href="https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---Google-Assistant"><img src="https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/googleassistant.png" ></a></td> 
  </tr>
 </table>


## Highlights

If you're here, you probably already have tried other knx nodes from npm. I hope you enjoy this one, because i've put big effort to do what i really needed, a copy/paste friendly node, with many functions and the possibility to use the ETS csv exported Group Addresses.<br />

<details><summary>Stand alone or with ETS exported file</summary>

You can set you own group address, datapoint and device name, or you can import the ETS Group Address list and have datapoint and device name auto populated while typing in the group address.

</details>
<details><summary>Filling helpers</summary>

If you import your ETS CSV or ESF file, just begin typing the group address or the device name in the Group Address textbox and a list of possible matches will appear. Just select an item in the list it and have datapoint and device name auto populated. You can then accept the auto populated fields or change it.

</details>
<details><summary>Automatic encoding/deconding of KNX datagrams</summary>

Just pass a normal payload to the node (true, false, a string or any nymber) and just receive a normal payload (true, false, a string or any nymber) to use in your flow.

</details>
<details><summary>Double Personality</summary>

The node can act as a single device (for example having Group Address 0/0/1), or can be used as universal node, catching all messages coming from KNX Bus (in this case the node will output a comprehensive msg to the flow, containing group address, device name, automatic decoded payload and other useful infos). The node can act as universal KNX sender as well (you can pass a message to the node, containing the destination group address, the datapont type and the payload).

</details>
<details><summary>Emulate real KNX device</summary>

You can use the node to emulate a phisically non existent KNX device. The node will behave exactly as a normal KNX Device and will also respond to read requests coming from the KNX bus, by sending the current payload value to the KNX bus.

</details>
<details><summary>Customizable status display</summary>

You can select what to see in the status (the row below the node). For example, you can select to see the current payload value and the last time changed, or the device name as well.

</details>
<details><summary>Self protection</summary>

The Node protects you, from youself. [Node Protections](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Protections)

</details>
<details><summary>Built in RBE input/output filter</summary>

You can select to activate or deactivate it. If active, the node reacts only if payload from KNX Bus or from input msg is changed.

</details>
<details><summary>Automatic KNX interface type</summary>

Full support for IP Interfaces as well for IP Routers. It's recommended the use of IP Routers because of simple setup and stability in a large environment.

</details>
<details><summary>Old interfaces friendly</summary>

The "Suppress ACK" option, helps compatibility with old IP Interfaces, like the Siemens SWG1 148-1AB22 IP Interface firmware etc...

</details>
<details><summary>Granular options</summary>

The node is very simple to use "out of the box", but you can plasmate it to achieve any goal you want.

</details>
<details><summary>WATCHDOG</summary>

You can [check the healty](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/-Sample---WatchDog) of your KNX Bus connection and switch over to anoter KNX/IP Router if the primary fails. It can programmatically change the IP, Port etc... of the KNX/IP Interface or router, via msg as well.

</details>
<details><summary>SCENE CONTROLLER</summary>

The [scene controller node](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki/Sample-Scene-Node) can act as a real scene controller, with recall and save of the current scene.

</details>
<details><summary>ACTIVE DEVELOPED</summary>

I personally use my node at home, so i put a lot of effort to develop it and i respond to your "github issues" very quickly

</details>

## WORKING WITH THE ETS CSV FILE OR WITH ESF FILE

Instead of create a knx-ultimate node for each Group Address to control, you can import your ETS csv or esf group addresses file.  
Thanks to that, the knx-ultimate node where you selected **Universal mode (listen to all Group Addresses)**, becomes an universal input/output node, aware of all Datapoints, Group Addresses and Device's name (ex: Living Room Lamp). Just send the payload to the knx-ultimate node, and it'll encode it with the right datapoint and send it to the bus. Likewise, when the knx-ultimate node receives a telegram from the bus, it outputs a right decoded payload using the datapoint specified in the ETS file.

<details><summary>Sample ETS csv file to paste into the ETS field of your config node.</summary>

> Copy/Paste this into your configuration node.

```javascript
"Group name"	"Address"	"Central"	"Unfiltered"	"Description"	"DatapointType"	"Security"
"Attuatori luci"	"0/-/-"	""	""	"Attuatori luci"	""	"Auto"
"Luci primo piano"	"0/0/-"	""	""	"Luci primo piano"	""	"Auto"
"Camera da letto luce"	"0/0/1"	""	""	"Camera da letto luce"	"DPST-1-8"	"Auto"
"Loggia camera da letto"	"0/0/2"	""	""	"Loggia camera da letto"	"DPST-1-1"	"Auto"
"Camera armadi luce"	"0/0/3"	""	""	"Camera armadi luce"	"DPST-1-1"	"Auto"
"Bagno grande luce"	"0/0/4"	""	""	"Bagno grande luce"	"DPST-1-1"	"Auto"
"Loggia bagno grande"	"0/0/5"	""	""	"Loggia bagno grande"	"DPST-1-1"	"Auto"
"Bagno grande specchio (switch)"	"0/0/6"	""	""	"Bagno grande specchio switch"	"DPST-1-1"	"Auto"
"Lavanderia luce"	"0/0/7"	""	""	"Lavanderia luce"	"DPST-1-1"	"Auto"
"Lavanderia specchio (switch)"	"0/0/8"	""	""	"Lavanderia specchio switch"	"DPST-1-1"	"Auto"
"Studio luce"	"0/0/9"	""	""	"Studio luce"	"DPST-1-1"	"Auto"
"Soggiorno luce (switch)"	"0/0/10"	""	""	"Soggiorno luce switch"	"DPST-1-1"	"Auto"
"Soggiorno aplique (switch)"	"0/0/11"	""	""	"Soggiorno aplique switch"	"DPST-1-1"	"Auto"
"Loggia soggiorno cucina"	"0/0/12"	""	""	"Loggia soggiorno-cucina"	"DPST-1-1"	"Auto"
"Cucina luce"	"0/0/13"	""	""	"Cucina luce"	"DPT-1"	"Auto"
"Cucina luce pensili"	"0/0/14"	""	""	"Cucina luce pensili"	"DPT-1"	"Auto"
"Corridoio luce"	"0/0/15"	""	""	"Corridoio luce"	"DPST-1-1"	"Auto"
"Scala LED"	"0/0/16"	""	""	"Scala LED"	"DPST-1-1"	"Auto"
"Soggiorno aplique brighness value"	"0/0/17"	""	""	""	"DPST-5-1"	"Auto"
"Bagno grande specchio (dim)"	"0/0/18"	""	""	"Bagno grande specchio dim"	"DPST-3-7"	"Auto"
"Soggiorno luce brighness value"	"0/0/19"	""	""	""	"DPST-5-1"	"Auto"
"Lavanderia specchio (dim)"	"0/0/20"	""	""	"Lavanderia specchio dim"	"DPST-3-7"	"Auto"
"Scala LED cambiacolori RGB"	"0/0/21"	""	""	""	"DPST-1-1"	"Auto"
"Bagno grande specchio brightness value"	"0/0/22"	""	""	""	"DPST-5-1"	"Auto"
"Soggiorno luce (dim)"	"0/0/23"	""	""	"Soggiorno luce dim"	"DPST-3-7"	"Auto"
```

</details>


<details><summary>Sample ETS esf file to paste into the ETS field of your config node.</summary>

> Copy/Paste this into your configuration node.

```javascript
My beautiful home
Attuatori luci.Luci primo piano.0/0/1	Luce camera da letto	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/2	Luce loggia camera da letto	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/3	Luce camera armadi	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/4	Luce bagno grande	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/5	Luce loggia bagno grande	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/6	Luce specchio bagno grande (switch)	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/7	Luce lavanderia	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/8	Luce specchio lavanderia (switch)	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/9	Luce studio	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/10	Plafoniera soggiorno (switch)	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/11	Applique soggiorno (switch)	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/12	Luce loggia soggiorno cucina	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/13	Luce cucina	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/14	Pensili cucina	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/15	Luce corridoio	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/16	LED scala	EIS 1 'Switching' (1 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/18	Luce specchio bagno grande(dim)	EIS 2 'Dimming - control' (4 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/20	Luce specchio lavanderia (dim)	EIS 2 'Dimming - control' (4 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/23	Plafoniera soggiorno (dim)	EIS 2 'Dimming - control' (4 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/24	Applique soggiorno (dim)	EIS 2 'Dimming - control' (4 Bit)	Low	
Attuatori luci.Luci primo piano.0/0/17	Applique soggiorno brighness value	Uncertain (1 Byte)	Low	
Attuatori luci.Luci primo piano.0/0/19	Plafoniera soggiorno brighness value	Uncertain (1 Byte)	Low	
Attuatori luci.Luci primo piano.0/0/21	LED cambiacolori RGB scala	EIS 1 'Switching' (1 Bit)	Low	
```

</details>

> You can work with a mix of knx-ultimate nodes, some with **Universal mode (listen to all Group Addresses)** checked and some not. You are absolutely free! See this youtube video,

<a href="https://youtu.be/I32_qG7yhFc" target="_blank"><img src='https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/yt.png' width='60%'></a>

<br/>


# <a href="https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki">Click here for comprehensive samples</a>
**Turn on/off a Lamp**
```javascript
return {payload:true}
```
```javascript
return {payload:false}
```

**Increase the light/open blind**
```javascript
// The parameter "data" indicates the relative amount of the dimming commmand (how much to dim).
// The parameter "data" can be any integer value from 0 to 7
// The parameter decr_incr:1 increases the light
// The parameter decr_incr:0 decreases the light
msg.payload={decr_incr: 1, data: 5};
return msg;
```

**Set RGB color**
```javascript
// Each color in a range between 0 and 255
msg.payload={red:255, green:200, blue:30};
return msg;
```

[MORE Samples and documentation....](https://github.com/Supergiovane/node-red-contrib-knx-ultimate/wiki)

![Logo](https://raw.githubusercontent.com/Supergiovane/node-red-contrib-knx-ultimate/master/img/wiki/flags/madeinitaly.png)

[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license-url]: https://github.com/Supergiovane/node-red-contrib-knx-ultimate/master/LICENSE
[npm-url]: https://npmjs.org/package/node-red-contrib-knx-ultimate
[npm-version-image]: https://img.shields.io/npm/v/node-red-contrib-knx-ultimate.svg
[npm-downloads-month-image]: https://img.shields.io/npm/dm/node-red-contrib-knx-ultimate.svg
[npm-downloads-total-image]: https://img.shields.io/npm/dt/node-red-contrib-knx-ultimate.svg
