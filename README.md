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
- by common name `=XLOOKUP("France",Name2Flag[Name],Name2Flag[Image])`
- by ISO code `=XLOOKUP("France",Name2Flag[ISO A-2],Name2Flag[Image])`
- using a dropdown menu 

**You can fetch flag**
- of every country flag 🇺🇸🇫🇷🇬🇧🇨🇭🇯🇵🇨🇳...
- of country set like European Union 🇪🇺
- worldwide symbol 🌐

![image](https://github.com/user-attachments/assets/c6b3ee33-4564-49b5-8be4-a6b81902ba28)

## Dropdown menu

**Select *Dropdown (from a range)***

**Use a constant range from any sheet of your file**
- `=Name_to_flag[SORTED name]` for common names
- `=ISO_to_flag[SORTED ISO]` for ISO codes

**If you want a customized country order, like *United States* on top of the dropdown list**
1. Reorder the rows of the table [Name_to_flag] as you desire
2. Uses this formula from any other sheet `=VLOOKUP(A1,Name_to_flag,3,FALSE)`, where A1 is the cell of your dropdown list

<img src="https://github.com/user-attachments/assets/989e0c71-b1c2-49e1-9f4d-b276be11a0e0" width="250">

![image](https://github.com/user-attachments/assets/2822c3ff-d642-4348-bf0f-42592a5ae833)
