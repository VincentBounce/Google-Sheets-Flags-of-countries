# 🌎Google Sheets: 257 HD flags of all countries 

## Open the sheet from this link

**https://docs.google.com/spreadsheets/d/1uazDIHQxew4WJWd_lhYgIPeBIvMke89q6384BCxpJjg/**

Then click **File > Make a copy**

## Fetchable fields

- Flag: PNG HD | Emoji (⚠️*Emojis are displayed as a country code on Windows 11*)
- Phone prefixe
- Domain names
- Area of country
- Population 2024
- Country ISO 3166-1 codes: A-2 (2 letters) | A-3 (3 letters) | numeric
- Country names: Common name | ISO 3166 name | Official state name
- Wikipedia article links: country | SVG flag | ISO | domain name

## Fetch HD flag by name or by ISO code

**You can retrieve the HD image of your flag**
- by common name `=VLOOKUP("France",Name_to_flag,3,FALSE)`
- by ISO code `=VLOOKUP("FR",ISO_to_flag,3,FALSE)`
- using a dropdown menu 

**You can fetch flag**
- of every country flag 🇺🇸🇫🇷🇬🇧🇨🇭🇯🇵🇨🇳...
- of country set like European Union 🇪🇺
- worldwide symbol 🌐

![image](https://github.com/user-attachments/assets/2822c3ff-d642-4348-bf0f-42592a5ae833)

## Fetch by name

![image](https://github.com/user-attachments/assets/5bb14fa7-ba1a-48b2-9e9b-e7403a56ecb3)

## Fetch by ISO 2-letter code

![image](https://github.com/user-attachments/assets/150247ab-b792-4174-9d37-235054139a26)

## Dropdown menu

**Select *Dropdown (from a range)***

**Use a constant range from any sheet of your file**
- `=Name_to_flag[SORTED name]` for common names
- `=ISO_to_flag[SORTED ISO]` for ISO codes

**If you want a customized country order, like *United States* on top of the dropdown list**
1. Reorder the rows of the table [Name_to_flag] as you desire
2. Uses this formula from any other sheet `=VLOOKUP(A1,Name_to_flag,3,FALSE)`, where A1 is the cell of your dropdown list

<img src="https://github.com/user-attachments/assets/989e0c71-b1c2-49e1-9f4d-b276be11a0e0" width="250">
