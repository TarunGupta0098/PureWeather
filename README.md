# 🌤️ PureWeather

PureWeather is a clean and responsive weather web app that fetches real-time weather data using a public weather API. It displays current weather conditions along with a 5-day forecast in a beautifully styled user interface.

---


## 🚀 Features

## ✅ Features

- 🌡️ **Displays** temperature, humidity, wind speed, pressure, and weather conditions  
- 🌡️↔️ **Toggle** between Celsius and Fahrenheit  
- 🌗 **Light and dark** theme switcher  
- 🖥️ **User-friendly interface** with weather icons and clean layout-
- 🌍 Real-time weather updates by city or geolocation.
- 📅 **5-day forecast** with date-wise breakdown  
- 📊 Interactive weather data visualization using charts.
- 📱 Responsive design optimized for all devices.
- ⚡ Efficient data fetching and caching with TanStack Query.
- 🎨 Clean and customizable UI using Shadcn UI and Tailwind CSS.
- 💻 Written in TypeScript for enhanced code quality and maintainability.

---

## 🛠️ Technologies Used

- Next.js
- React
- TypeScript
- Tailwind CSS
- TanStack Query
- Shadcn UI
- Recharts
- Weather API (e.g., OpenWeatherMap)

---

## 📸 Screenshots

> Add screenshots of your application here by uploading images in a `screenshots/` folder and referencing them below.

![Home Page](screenshots/home.png)
*Current weather display*

![Forecast](screenshots/forecast.png)
*5-day forecast layout*

---

## 📂 Getting Started

Follow these steps to run the project locally.


### 🔧 Prerequisites

- Node.js (v14+ recommended)
- npm or yarn

### 📥 Installation

1️⃣ Clone the repository:

```bash
git clone https://github.com/TarunGupta0098/PureWeather.git
```

```bash
cd PureWeather
```

2️⃣ Install Dependencies

```bash
npm install
# or
yarn install
```
3️⃣ Get your Api key

1. create free account at https://openweathermap.org
2. Search for 'api'
3. Click on **"Create API Key"**  under the "API Keys" section
4. Copy generated api key


4️⃣ Create a .env.local file and add your weather API key:
```bash
NEXT_PUBLIC_WEATHER_API_KEY=your_api_key_here
```

5️⃣ Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open http://localhost:your_portNo in your browser to see the app.



