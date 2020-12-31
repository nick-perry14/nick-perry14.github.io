# EUP Guide


Follow the steps below to create outfits for EUP

Download and install eup-stream and eup-ui

Navigate to the eup-ui folder

Open the eup-ui.lua file

The file should contain entries that look like this:

<br>
```lua
	['Male LSPD Class A'] = {
		category = 'LSPD - Male',
		ped = 'mp_m_freemode_01',
		props = {
			{ 0, 47, 1},
			{ 1, 0, 0 },
			{ 2, 0, 0 },
			{ 6, 0, 0 },
		},
		components = {
			{ 1, 1, 1 },
			{ 11, 201, 1 },
			{ 3, 5, 1 },
			{ 10, 1, 1 },
			{ 8, 57, 1 },
			{ 4, 36, 1 },
			{ 6, 52, 1 },
			{ 7, 9, 1 },
			{ 9, 1, 1 },
			{ 5, 53, 1 },
		}
	},
```

<br>
Modify line "Male LSPD Class A" to whatever name of the outfit you would like

Assign the category that the outfit should show under

Assign the props as necessarry

For Props:  The template is as followed:

<br>
```
props = {
{propNumber, propSelection, propColor},
}
```

<br>
For propNumber, reference the following table

<br>

|Prop Type|Prop Number|
|:-:|:-:|
|**Hat**|**0**|
|**Glasses**|**1**|
|**Ear (Misc)**|**2**|
|**Watch**|**6**|

<br>
Set the propSelection to the variation number (Hat #5, for example)

Set the propColor to the color of the prop (starting from 1)

Assign components as necessary

For Components: The template is as follows:

<br>
```
components = {
{compNumber,compSelection,compColor},
}
```


For compNumber, reference the following table

<br>

|Component Type|Component Number|
|:-:|:-:|
|**Mask**|**1**|
|**Hands**|**3**|
|**Pants**|**4**|
|**Bags // Parachute**|**5**|
|**Shoes**|**6**|
|**Neck//Scarf**|**7**|
|**Shirt//Accessory**|**8**|
|**Body Armor**|**9**|
|**Badges//Logos**|**10**|
|**Jackey//Overlay**|**11**|

<br>
Set the compSelection to the variationNumber (Jacket #5)

Set the compColor to the jacket color (starting from 1)

Repeat for multiple props/components

Upload file/restart eup-ui