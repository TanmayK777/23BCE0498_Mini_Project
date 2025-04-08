# Weather App 🌦️

A responsive weather web application that displays current and forecasted weather data using OpenWeatherMap API. The app includes user authentication features such as login, signup, and password reset.

## 🚀 Features

- Current weather and hourly forecast
- Air quality index visualization
- Sunrise and sunset information
- Login, Signup, and Password Reset pages
- Mobile responsive UI
- Dark-themed modern design

## 📁 Project Structure

```
.
├── index.html              # Login Page
├── signup.html            # Signup Page
├── passwordreset.html     # Password Reset Page
├── weatherapp.html        # Main Weather App Page
├── info.html              # About Page
├── style.css              # App styling
├── script.js              # Main JavaScript logic
└── README.md              # Project documentation
```

## 🧰 Dependencies

This project uses the following:
- HTML5, CSS3, JavaScript (Vanilla)
- OpenWeatherMap API

No additional libraries or frameworks are required.

## ⚙️ Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/TanmayK777/23BCE0498_Mini_Project.git
cd 23BCE0498_Mini_Project
```

2. **Open the App**
Simply open `index.html` in your web browser to start the application.

3. **Run with Live Server (Optional)**
For a better development experience:
- Use VSCode with Live Server extension.
- Right-click on `index.html` → "Open with Live Server".

## 🌐 Deployment

This project can be deployed using GitHub Pages:

1. Go to your GitHub repository.
2. Click on `Settings` → `Pages`.
3. Select the branch as `main` (or `master`) and folder as `/root`.
4. Save and your site will be live at:
```
https://TanmayK777.github.io/23BCE0498_Mini_Project/
```

## 🧠 How to Use

- Login (index.html) or signup (signup.html) using the provided forms. You can also change passoword (passwordreset.html).
- After login, you'll be redirected to the weather dashboard (`weatherapp.html`).
- Use the search bar to get weather details for your city.
- Use the location button to fetch weather based on your current location.
- Explore air quality, sunrise/sunset, and forecast data.

## 📌 Notes

- Make sure to use your own OpenWeatherMap API key inside `script.js`.
- Check browser console for any API errors or CORS issues.

