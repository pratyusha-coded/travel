 <div align="center">
  <br />
  <a href="https://github.com/yourusername/tripwise">
    <img src="https://img.shields.io/badge/✈️_TripWise-AI_Travel_Co--Pilot-0f172a?style=for-the-badge&logoColor=white" height="60" alt="TripWise Logo" />
  </a>
  
  <h3 style="font-size: 24px; font-weight: bold;">Plan smarter, <span style="color: #38bdf8;">travel happier.</span></h3>

  <p style="color: #64748b;">
    One place to estimate your budget, build your itinerary, and discover hidden gems.
    <br />
    Tailored for 🇮🇳 Indian Travelers.
  </p>

  <p>
    <a href="https://your-live-demo-link.com">
      <img src="https://img.shields.io/badge/✨_Try_Live_Demo-3b82f6?style=for-the-badge" height="35" />
    </a>
    <a href="#-getting-started">
      <img src="https://img.shields.io/badge/🛠️_Setup_Locally-1e293b?style=for-the-badge" height="35" />
    </a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/AI-Gemini_2.5-8E75B2?style=flat-square&logo=google" />
    <img src="https://img.shields.io/badge/Images-Pexels_API-05A081?style=flat-square&logo=pexels" />
    <img src="https://img.shields.io/badge/Auth-Firebase-FFCA28?style=flat-square&logo=firebase" />
    <img src="https://img.shields.io/badge/UI-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css" />
  </p>
</div>

<br />

<div align="center"> 
  <table>
    <tr>
      <td align="center"><b>1. Describes Your Trip</b></td>
      <td align="center"><b>2. AI Generates the Plan</b></td>
    </tr>
    <tr>
      <td>
        <img src="https://placehold.co/500x300/0f172a/ffffff?text=Landing+Page+Screenshot" width="400" />
      </td>
      <td>
        <img src="https://placehold.co/500x300/1e293b/ffffff?text=Itinerary+Result+Screenshot" width="400" />
      </td>
    </tr>
  </table>
</div>

---

## 💎 Features

Just like the website's feature cards, TripWise offers:

| <div align="center">💸</div> | <div align="center">🗓️</div> | <div align="center">📸</div> |
| :--- | :--- | :--- |
| **Smart Budgeting** | **AI Itineraries** | **Visual Discovery** |
| Get realistic estimates in **₹ INR** for flights, trains, and hotels based on whether you choose *Budget, Comfort, or Luxury*. | No more generic lists. Get a **day-by-day** plan that makes sense logistically, curated by Google's Gemini AI. | Don't just read about it. The app fetches **real photos** of the destination and local food using the Pexels API. |

---

## 🚀 How It Works

The application follows a simple "State-less" to "State-full" architecture:

1.  **Authentication:** Users sign in via Firebase (Data is synced to Cloud).
2.  **Input:** User selects Origin, Destination, Days, and **Travel Style**.
3.  **Processing:**
    * Request sent to **Gemini API** for JSON data.
    * Parallel requests sent to **Pexels API** for images.
4.  **Rendering:** The UI updates dynamically with a 3D-tilt card interface.

---

## 🛠️ Getting Started

Follow these steps to get your own AI Travel Agent running.

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/tripwise.git](https://github.com/yourusername/tripwise.git)
cd tripwise
