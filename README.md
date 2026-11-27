# Python End of Module Capstone Project
## AgriSpan KE: B2B Produce Margins Optimizer & Volatility Analyzer
### Problem Statement
B2B food SMEs businesses that rely heavily on fresh produce such as green grocer vendors, hotels, restaurants & market traders in Kenya suffer severe seasonal price volatility from unpredictable price spikes as a result of harvest cycles, fuel fluctuations and supply bottlenecks. Since they rely on reactive, manual price checks, impromptu shocks compress their gross margins, force last minute repricing & subsequently increase post-harvest spoilage costs.


### Project Objectives
- Early shock detection (By comparing current price deviations against historical averages)
- Root Cause Attribution (Linking/Cross referencing price spikes with weather anomalies, transit bottlenecks etc)
- Real-Time B2B margin optimization (Gross costs comparison against selling price to protect net profit margins & suggest cheaper alternative sourcing markets)
- Field Communication (Automatically formats market alerts & margin amounts into a manner that can be copy pasted as a WhatsApp/SMS so vendors can quickly update drivers & buyers)
- Audit Trail(Saves every vendor check into a local SQLite database)


### Proposed Solution
AgriSpan KE. market intelligence tool help Kenyan SMEs track & anticipate fresh produce price spikes, ability to flag supply shocks thereby protecting their profit margins.

**How it works**

- The vendor inputs the crops they trade e.g Tomatoes or Onions and their selling price
- Morning Alerts (AgriSpan automatically checks overnight prices e.g from KAMIS and sends an alert message on pricing and alternative options)
- With this alert the vendor makes a data informed decision on sourcing & pricing.

### Proposed Application Functionalities
- Interactive Simulator (Vendors input their costs)
- Root Cause Dashboard (Evaluates daily prices against baselines & displays or warns the vendors)
- Costs and Margins computations
- Alerts Generator (Formats daily shock status & shares the alerts to respective field teams)
### Data Requirements & Sources
- Web scraping (Kenya Agricultural Market Information System KAMIS)
- APIs (Shamba Records & KMD)
- Vendors input (Streamlit)

### Proposed Technology Stack
| Technology | Purpose |
|---|---|
| Python | Application development. |
| Streamlit | Building the web interface. |
| CSV / JSON / SQLite | Data storage. |
| Git and GitHub | Version control and project hosting. |

### Python Concepts to Demonstrate
- Variables, data types and control flow.
- Lists, tuples, dictionaries and sets.
- Functions.
- Object-Oriented Programming 
- File handling.
- Exception handling and input validation.
- Working with databases.