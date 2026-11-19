# BMW M5 Global Analytics Dashboard (1984–2026)

An interactive Power BI report analyzing the **BMW M5** across seven generations (**E28** to **G90 / G99**), covering technical performance evolution, global production volume, regional market share, and 2025–2026 international pricing.

---

## Dashboard Preview

<img width="1141" height="491" alt="image" src="https://github.com/user-attachments/assets/f0fdfd6f-c5f1-44b7-b06e-2fe6bf1810d8" />

---

## Key Insights from the Dataset

### 1. Performance & Weight Evolution (1984–2026)
* **Power & Torque Surge:** Output climbs from **286 hp / 340 Nm** on the original **E28** (1984–1988) to **717 hp / 1,000 Nm** on the plug-in hybrid **G90 / G99** (2024–2026) — a **+431 hp (+150.7%)** jump in horsepower and **+660 Nm (+194.1%)** gain in torque.
* **Acceleration Benchmark:** Despite newer hybrid models adding weight, the lightweight **F90 CS** (1,866 kg) remains the quickest in the dataset at **3.0 seconds** (0–100 km/h), ahead of the **G90 / G99** at **3.5 seconds**.
* **Curb Weight Shift:** Moving from naturally aspirated and twin-turbo ICE setups to PHEV hardware pushes curb weight from **1,430 kg** (E28) to **2,510 kg** (G90 / G99), a **+1,080 kg (+75.5%)** increase.

### 2. Global Production & Regional Demand
* **High-Volume Era:** Across all listed generations, total estimated production reaches **121,473 units**, led by the **F90** (**31,975** standard units, or **33,107** including **1,132** M5 CS units).
* **US Market Dominance:** In F90 regional distribution (**33,107** total units), the **United States** leads with **12,541 units (37.9%)**, followed by **Rest of Europe & Global** (**4,676** / **14.1%**), **Germany** (**4,635** / **14.0%**), and **China & East Asia** (**3,973** / **12.0%**). For the limited **M5 CS** (**1,132** units), the US accounts for **454 units (40.1%)**.
* **M & 5-Series Momentum:** Between 2024 and 2025, **BMW M GmbH** deliveries grew **+3.3%** (from **206,582** to **213,457**), while the **BMW 5 Series / 6 Series** family rose **+19.5%** (from **250,696** to **299,582**).

### 3. Global Pricing Spread (2025–2026)
* **Wide Regional Gap:** Converted G90 Sedan starting prices average **$174,036 USD** (median **$162,406 USD**) across the 12 tracked markets, ranging from **$97,200 USD** in Canada (at the modeled FX rate) up to **$342,000 USD** in Pakistan (estimated CBU import).
* **Touring Premium:** Across all 12 markets, the **G99 Touring** averages **$178,037 USD**, representing a mean **$4,000 USD** premium over the **G90 Sedan** (from **$2,000 USD** in the US to **$10,800 USD** in the Pakistan CBU estimate).

---

## Dataset Structure

| Sheet Name | Key Fields Analyzed |
| :--- | :--- |
| **Generations & Specs** | Generation, Chassis Code, Production Years, Body Styles, Engine Code & Type, Displacement, Max Power, Max Torque, Transmission, Drivetrain, 0–100 km/h, Top Speed, Curb Weight, Global Production |
| **Global Pricing (2025-2026)** | Region, Country / Market, Currency, G90 Sedan & G99 Touring Local Prices, FX Rate to USD, USD Equivalents, Touring Premium, Availability Status |
| **Global Market Distribution** | Country / Region, F90 & M5 CS Units and Shares, Body Preference, Market Insights, plus 2024–2025 BMW M & 5-Series Deliveries |
| **Executive Dashboard** | KPI Summary Cards & Multi-Chart Overview |

---

## Tools & Styling
* **BI Tool:** Microsoft Power BI Desktop (Power Query for cleaning/shaping)
* **Theme Palette:** Dark studio charcoal/slate backgrounds (`#2B2B2B` / `#363636`) paired with Isle of Man Green accents (`#1E825C` / `#34B382`)
