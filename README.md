<div align="left">

# <font color="#1D4ED8">🚘 ADAS Car Crash Data Analysis Report</font>

---

### <font color="#2563EB">📌 Executive Summary</font>

<blockquote>
<font color="#1E40AF" size="3">
We analyzed the <b>ADAS Car Crash Dataset</b> containing <b>1,536 NHTSA reports</b>. The data shows that when excluding unknown entries, the vast majority of daily incidents occur on freeways during clear weather, with most vehicles proceeding straight prior to impact.
</font>
</blockquote>

---

### <font color="#2563EB">🛣️ Roadway Distribution & Work Zones</font>

<font color="#1E3A8A">

Excluding the <b>550 unknown location reports</b>, the majority of daily road accidents occur on freeways:

</font>

| Location | Incident Count |
| :--- | :--- |
| **Freeway** | `627` |
| **Intersection** | `161` |
| **City Streets** | `156` |
| **Rural Road** | `27` |
| **Parking Lot** | `13` |
| **Unpaved Road** | `1` |
| **Parking Garage** | `1` |

<font color="#1E3A8A">

> 💡 **Work Zone Safety:** Out of all 1,536 reports, only **18 incidents** occurred within active work zones.

</font>

---

### <font color="#2563EB">🌤️ Weather & Environmental Factors</font>

<font color="#1E3A8A">

We analyzed environmental conditions including rain, cloudiness, snow, and storms:

* **Clear Weather:** After excluding unknowns, the majority of incidents occurred under clear weather conditions.
* **Key Insight:** This trend is heavily influenced by the fact that self-driving cars are often restricted from operating in severe weather conditions like heavy fog or strong winds.

</font>

---

### <font color="#2563EB">🔄 Pre-Crash Movement Analysis</font>

<font color="#1E3A8A">

The dataset highlights vehicle actions directly preceding collisions:

* **CP Section:** **"Proceeding Straight"** was the leading movement with **177 incidents**.
* **SV Section:** **"Proceeding Straight"** was also the top occurrence with **294 incidents**.

</font>

---

### <font color="#2563EB">🩺 Injury Severity & Impact</font>

<font color="#1E3A8A">

* **Injury Rates:** Excluding unknown records, only **30% of the accidents** resulted in no injuries (property damage only).
* **Takeaway:** Unlike datasets with lower injury rates, a significant majority (70%) of known ADAS collisions involved some level of reported injury.

</font>

</div>
