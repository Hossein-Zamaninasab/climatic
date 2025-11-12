# 🌦️ Climatic: Weather & Public Health Dashboard

**[⚡️ View the Live Demo ⚡️](https://www.google.com/search?q=https://hsyn.ir/Climatic)**

<img width="1600" height="1141" alt="screencapture-hsyn-ir-Climatic-2025-11-12-09_14_58" src="https://github.com/user-attachments/assets/8aa01744-45f8-4c7e-a608-4ee548a08ae3" />

-----

## 🎯 Motivation & Purpose

Ambient (outdoor) air pollution is a global public health crisis. According to the World Health Organization (WHO), approximately **4.2 million premature deaths worldwide** are attributed to exposure to outdoor air pollutants annually, particularly fine particulate matter (**PM2.5**) [1].

Unfortunately, public access to transparent, comprehensible, and real-time data on these hazardous indicators is often limited. Public information systems may not always provide clear or timely warnings to citizens, hindering their ability to take protective measures.

`Climatic` was developed as an **independent, free, and open-source public health tool**. Its primary goal is to empower citizens by translating complex meteorological and air pollution data into actionable, easy-to-understand information, enabling them to make informed decisions to protect their health and well-being.

-----

## ✨ Key Features & Chart Details

The dashboard is organized into four primary analytical tabs:

### 1\. Daily Forecast Tab

This section provides a macro-level overview of upcoming weather trends.

  * **Charts:** Minimum & Maximum Temperature, Max Wind Gust, Total Precipitation, and Max UV Index.
  * **Filters & Features:**
      * **Time Range:** Selectable view for Monthly (default) or Yearly data.
      * **Historical Comparison:** A key feature for climate analysis, allowing users to overlay the previous year's temperature data against the current year's forecast.

### 2\. Today & Tomorrow Tabs (Hourly)

These tabs provide granular, 24-hour details for short-term planning.

  * **Charts:** Apparent ("Feels Like") Temperature, Precipitation Probability, Wind Speed, Cumulative Precipitation, and hourly UV Index.
  * **Filters & Features:**
      * **Hourly Comparison:** Compare today's apparent temperature with yesterday's (on the Today tab) or tomorrow's with today's (on the Tomorrow tab).
      * **Data Toggles:** Users can toggle the visibility of individual chart series (e.g., Wind, Precipitation).

### 3\. Air Quality (AQI) Tab

This is the project's most critical public health component.

  * **Charts:** Real-time concentration tracking for key pollutants:
      * **PM2.5** (Fine, hazardous particles)
      * **PM10** (Coarse particles)
      * **O₃** (Ground-level Ozone)
      * **NO₂** (Nitrogen Dioxide)
      * **SO₂** (Sulphur Dioxide)
      * **CO** (Carbon Monoxide)
  * **Indices:** Calculates and displays both the **European AQI** and the **US AQI**.
  * **Visualization:** Utilizes custom-built gauge charts to visualize the status of each pollutant against "Good," "Poor," and "Hazardous" thresholds.

### 4\. AI-Powered Summary

For users without the technical expertise to interpret complex graphs, an AI assistant analyzes the data from all tabs and provides an operational summary in plain language.

  * **Example:** "*Outdoor running is not advised today due to high PM2.5 and UV levels. Sensitive individuals should remain indoors.*"
  * **Multilingual:** This analysis is available in four languages: **English, German, Farsi, and Arabic**.

-----

## 🔬 Public Health Relevance (Why This Data Matters)

This project is not just a data visualization; each metric is directly linked to human health outcomes:

  * **Air Pollution (PM2.5 & O₃):**
    Globally, **99% of the world's population** breathes air that exceeds WHO guideline limits [1]. PM2.5 particles are small enough to enter the bloodstream, making them a primary cause of cardiovascular disease, stroke, and lung cancer. The burden is especially heavy in developing nations; for instance, air pollution is estimated to cause over **1.6 million deaths in India** and **1.2 million deaths in China** annually [2].

  * **UV Index:**
    Chronic exposure to UV radiation is the leading cause of skin damage, premature aging, and the vast majority of skin cancers. It can also cause severe eye damage, including cataracts [3]. By providing an hourly UV forecast, this dashboard helps users take precautions (like using sunscreen and eye protection) during peak hours (typically 10 a.m. to 4 p.m.).

  * **Temperature (Heat & Cold Stress):**
    Extreme temperatures place severe stress on the cardiovascular and respiratory systems. A landmark 2021 study in *The Lancet* estimated that over **5 million premature deaths globally** per year are associated with non-optimal ambient temperatures (both cold and heat) [4]. These risks are particularly acute for the elderly, children, and individuals with chronic illnesses.

-----

## 🛠️ Tech Stack

  * **Frontend:** JavaScript (ES6+), **ApexCharts.js** (for interactive charts), Bootstrap 5
  * **Backend:** **PHP 7.4**, MySQL (for user management, settings persistence)
  * **APIs:**
      * **Open-Meteo:** (Primary source for all weather and air quality data)
      * **OpenAI API (gpt-4o):** (Powers the AI-driven summary feature)

-----

## 📸 Gallery

\<div align="center"\>

| Air Quality Tab (AQI) | Hourly Forecast (Today) | Daily Forecast (Monthly) |
| :---: | :---: | :---: |
| ![pollution](https://github.com/user-attachments/assets/0fbd0224-8039-448a-aa43-43b13c1640e1) | `[Your Today Tab Screenshot Here]` | `[Your Daily Tab Screenshot Here]` |

\</div\>

-----

## 👨‍🔬 About the Developer

I am **Hossein Zamaninasab**, an M.Sc. Biology student at the University of Oldenburg, Germany, and an Environmental Health Data Researcher.

This project sits at the intersection of my passions for programming (PHP/JS), data analysis, and spatial epidemiology. It is an attempt to leverage technology to promote public health awareness.

  * **LinkedIn:** [linkedin.com/in/hossein-zamaninasab](https://www.google.com/search?q=https://www.linkedin.com/in/hossein-zamaninasab)
  * **Google Scholar:** [scholar.google.com/citations?user=sA3vB8cAAAAJ](https://www.google.com/search?q=https://scholar.google.com/citations%3Fuser%3DsA3vB8cAAAAJ)
  * **GitHub:** [github.com/Hossein-Zamaninasab](https://www.google.com/search?q=https://github.com/Hossein-Zamaninasab)

-----

## 📚 References

[1] **World Health Organization (WHO).** (2021). *"Ambient (outdoor) air pollution"*. [WHO Fact Sheet](https://www.who.int/news-room/fact-sheets/detail/ambient-\(outdoor\)-air-quality-and-health)
[2] **State of Global Air.** (2020). *"Report 2020: A Special Report on Global Exposure to Air Pollution and its Health Impacts"*. Health Effects Institute. [Link](https://www.google.com/search?q=https://www.stateofglobalair.org/report/state-global-air-2020)
[3] **World Health Organization (WHO).** (2017). *"Radiation: Ultraviolet (UV) radiation"*. [WHO Fact Sheet](https://www.who.int/news-room/fact-sheets/detail/ultraviolet-radiation)
[4] **Zhao, Q., et al.** (2021). *"Global, regional, and national burden of mortality associated with non-optimal ambient temperatures from 2000 to 2019: a three-stage modelling study"*. **The Lancet Planetary Health**, 5(7), e415-e425. [DOI: 10.1016/S2542-5196(21)00081-4](https://doi.org/10.1016/S2542-5196\(21\)00081-4)
