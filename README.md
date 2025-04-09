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

![image](https://github.com/user-attachments/assets/c6b3ee33-4564-49b5-8be4-a6b81902ba28)

## Fetch HD flag by name or by ISO code

**You can retrieve the HD image of your flag**
- by common name `=XLOOKUP("France",Name2Flag[Name],Name2Flag[Image])`
- by ISO code `=XLOOKUP("France",Name2Flag[ISO A-2],Name2Flag[Image])`
- using a dropdown menu 

**You can fetch flag**
- of every country flag 🇺🇸🇫🇷🇬🇧🇨🇭🇯🇵🇨🇳...
- of country set like European Union 🇪🇺
- worldwide symbol 🌐

![image](https://github.com/user-attachments/assets/6e9a6f6a-b332-4aab-8d22-87ce0c0268f4)


## Dropdown menu

**Select *Dropdown (from a range)***

**Use a constant range from any sheet of your file**
- `=Name2Flag[Name]` for common names
- `=Name2Flag[ISO A-2]` for ISO codes

**You can customize the country order**
- like *United States* and tech countries on the top of the dropdown list**

<img src="https://github.com/user-attachments/assets/f18453da-a5e8-428d-a926-edd5590e7b06" width="250">
