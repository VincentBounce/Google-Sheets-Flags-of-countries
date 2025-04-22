# 𓊁Google Sheets 🇺🇳 257 vectorial flags of all countries 

## 👌To fork & use this spreadsheet

Open **https://docs.google.com/spreadsheets/d/1uazDIHQxew4WJWd_lhYgIPeBIvMke89q6384BCxpJjg**

Then click **File > Make a copy**

## 🗂️Fetchable fields

- **Flag** Vectorial SVG | PNG | Emoji *⚠️Emojis are displayed as a country code on Windows 11*
- **Phone prefix**
- **Language ISO 639-1 code(s)**
- **Top-level domain(s)**
- **Currencies**
- **Groups** UN | EU | BRICS | G20 | G7 | GCC | AU | ASEAN | NATO | Mercosur
- **Continent | Region**
- **Capital**
- **Sovereignity**
- **Area of the country**
- **Population**
- **Country ISO 3166-1 codes** A-2 (2 letters) | A-3 (3 letters) | numeric
- **Country name** Short name | ISO 3166 name | Official state name
- **Wikipedia article links** Country | Flag | ISO | Domain name
- **Country FIPS 10-04 code**

![image](https://github.com/user-attachments/assets/cd8e5d79-5d8c-4f9d-b546-e1d5309f7784)

![image](https://github.com/user-attachments/assets/357bb8cb-fb2c-4d1b-ba5a-0a19d36cd6d8)


## 🏁Fetch SVG flag by name or by ISO code

**You can retrieve the HD image of your flag**
- by common name `=XLOOKUP("France",Flags[Short name],Flags[Image])`
- by ISO code `=XLOOKUP("France",Flags[ISO A-2],Flags[Image])`
- using a dropdown menu 

**You can fetch flag**
- of every country flag 🇺🇸🇫🇷🇬🇧🇨🇭🇯🇵🇨🇳...
- of country set like European Union 🇪🇺
- worldwide symbol 🌐

![image](https://github.com/user-attachments/assets/03de2b2c-c8cb-4d11-8294-8a1ab19c0cf8)

## (˅)Dropdown menu

**RightClick > *Dropdown* > Select *Dropdown (from a range)***

**Use a constant range from any sheet of your file**
- `=Flags[Short name]` for common names
- `=Flags[ISO A-2]` for ISO codes

**You can customize the country order**
- for example *United States* and tech countries on the top of the dropdown list

<img src="https://github.com/user-attachments/assets/07c40bdf-fed8-49ba-ba7c-6efabee88557" width="260">
