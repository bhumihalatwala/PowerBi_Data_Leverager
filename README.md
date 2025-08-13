# 📊 Power BI Data Transformation & Analysis

## 🌐 Data Sources
- 🌍 **Web**: Country-wise GDP from [Worldometers](https://www.worldometers.info/gdp/gdp-by-country)  
- 📂 **Folder**: Monthly sales data (`Sales_Jan.xlsx`, `Sales_Feb.xlsx`, `Sales_Mar.xlsx`)  
- 📄 **Excel**: Employee dataset (EmployeeID, Name, Department, Region, Join Date, Birth Date)  

---

## 🔄 Transformations Applied
- 🧹 **Cleaning**: Promote headers, remove blanks, rename columns, fix data types, remove duplicates, filter nulls  
- ✍ **Text Tools**: `UPPER()`, `LOWER()`, `TRIM()`, `CLEAN()`, `REPLACE()`, split columns by delimiter  
- 🔢 **Numeric Tools**: Round revenue, calculate Profit = Revenue - Cost  
- 📅 **Date Tools**: Extract Day/Month/Year/Quarter, calculate Age from Birthdate  
- ⚡ **Conditional & Index**: Sales Category (High/Medium/Low), 0-based & 1-based index  
- 🔄 **Pivot & Unpivot**: Reshape monthly sales data  
- 🔗 **Merge & Append**: Merge sales & employee data, append Jan–Mar sales  
- 📊 **Grouping**: Total Sales, Avg Order Value, Transaction Count by Region  
- 🧪 **Data Profiling**: Column Profile, Distribution, Quality checks  
- ⚙ **Parameters & Credentials**: Dynamic folder path, updated credentials  
- 🔄 **Refresh Simulation**: Auto-load new month file (*Sales_Apr.xlsx*)  

---

## 🚧 Challenges & Solutions
| Challenge | Solution |
|-----------|----------|
| 📅 Date format inconsistencies | Changed **Change Type with Locale** & set **PC regional settings to UK** for mm-dd-yyyy |
| 📑 Inconsistent sheet names in folder import | Renamed all sales sheet names to match for successful combine |
| 🌐 Multiple source types | Used Power Query connectors for smooth integration |
| 🧾 Text inconsistencies | Applied text functions to standardize names & addresses |
| 🗂 Auto-refresh for new files | Used Folder Query with Parameters |

---

## 💡 Key Learning
This project strengthened my skills in **Power Query transformations**, **data cleaning**, **merging & appending**, **parameters**, and **automating refreshes** in Power BI.

