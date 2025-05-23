# 𓊁Google Sheets 🇺🇳 258 vectorial flags of all countries 

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

## 🇺🇳Fetch SVG or PNG flag by name or by ISO code

**You can retrieve the SVG image of your flag**
- by common name `=XLOOKUP("France",Flags[Short name],Flags[Image])`
- by ISO code `=XLOOKUP("France",Flags[ISO A-2],Flags[Image])`
- using a dropdown menu

**You can fetch flag**
- of every country flag 🇺🇸🇫🇷🇬🇧🇨🇭🇯🇵🇨🇳...
- of country set like European Union 🇪🇺
- worldwide symbol 🌐
- in PNG as well `=XLOOKUP("France",Flags[Short name],Flags[330px])`

**Dynamic imports are made from Wikipedia (Wikimedia Commons)**
- Wikipedia is the most reliable website for those resources
- the risk of having dead links is minimal
- `[SVG]` colomn contains SVG flags dynamically crawled from Wikipedia.
- `[330px]` colomn contains PNG flags dynamically crawled from Wikipedia. It can be pasted as value to `[Image]` column to use PNG by default.
- `[Image]` column contains SVG flags which was copied from `[SVG]` column. No external access required to use it.

![image](https://github.com/user-attachments/assets/5f496067-c417-4ba3-b767-93628bdf2c50)

## (˅)Dropdown menu

**RightClick > *Dropdown* > Select *Dropdown (from a range)***

**Use a constant range from any sheet of your file**
- `=Flags[Short name]` for common names
- `=Flags[ISO A-2]` for ISO codes

**You can customize the country order**
- for example *United States* and tech countries on the top of the dropdown list

<img src="https://github.com/user-attachments/assets/07c40bdf-fed8-49ba-ba7c-6efabee88557" width="260">

## 🔍Explore the details of all flags: vectorial SVG & Apple emoji flags

- Select **🎓Wide flags** tab
- Click **View > Full screen**
- Then **scroll up/down**

![Screenshot 2025-04-24 at 11 57 14](https://github.com/user-attachments/assets/8b723874-a857-4fe1-b88c-fae85dd9a46e)

## 😉 Author 🇫🇷 Vincent ᗱƆᑌᑎϹᗴ

**𝕏 [@VincentBounce](https://x.com/VincentBounce)** | **YouTube [@VincentBounce](https://www.youtube.com/@VincentBounce/)** | **Instagram [@VincentBounce](https://instagr.am/vincentbounce/)**
