# Tourist-Plan 
# 🌍 Tourist Guy
🌍 Tourist Guy is a Python-based travel planner that helps users choose destinations, estimate trip budgets, compare packages, visualize expense breakdowns, and explore routes on interactive maps. ✈️📊 Smart, simple, and engaging trip planning in one project. 🧳

**Tourist Guy** is a Python-based travel planning project built in Jupyter Notebook that helps users choose a destination, estimate trip costs, select travel packages, and visualize routes on an interactive map. It combines trip budgeting, expense analysis, and travel route planning into one simple and engaging project.

---

## ✨ Features

- 🧳 Select from multiple tourist destinations
- 👨‍👩‍👧‍👦 Plan trips based on number of travelers
- 📅 Choose trip duration
- 💼 Pick a travel package:
  - Low
  - Mid
  - High
- 💰 Estimate total trip cost
- 🎁 Apply special discount for groups above 10 people
- 🚗 Choose travel mode:
  - Car
  - Bus
  - Train
  - Flight
- 📊 View expense distribution using a pie chart
- 🗺️ Explore trip routes with interactive **Folium maps**
- 📍 Visit multiple attractions across selected destinations

---

## 📌 Available Destinations

The project currently supports the following destinations:

1. 🕌 Agra  
2. 🏖️ Goa  
3. 🏔️ Himachal Pradesh  
4. 🏝️ Thailand  
5. 🌄 Mauritius  

---

## ⚙️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Folium** – for interactive maps
- **Matplotlib** – for expense visualization

---

## 📂 Project Structure


Tourist Project.ipynb
This notebook contains the complete travel planning logic, user input flow, cost estimation, chart visualization, and route mapping.

# 🚀 How It Works
The program follows these steps:

User selects a destination
User enters:
number of people
number of days
preferred package
The system calculates:
base package cost
travel/fuel/ticket cost
food expenses
hotel cost
ride/activity expenses
other expenses
If travelers are more than 10, a 10% discount is applied
A pie chart shows expense distribution
A map route is generated with key tourist spots
🛠️ Installation
Make sure Python is installed, then install the required libraries:
ip install folium matplotlib
If you are using Jupyter Notebook, launch it with:

Copyjupyter notebook
# ▶️ Usage
Open the notebook:
CopyTourist Project.ipynb
Run all cells
Enter your trip details when prompted
Review:
trip summary
estimated budget
expense chart
travel map
# 📊 Expense Categories
The total estimated budget is divided into:

Travel
Food
Hotel
Ride Activity
Other Expenses
This helps users better understand how their travel budget is distributed.

# 🗺️ Route Visualization
The project uses Folium to create an interactive route map starting from Ahmedabad and showing major tourist attractions for the selected destination.
Each route includes multiple stops and markers for a more realistic travel experience.

# 🎯 Project Goal
The main goal of this project is to make trip planning:

easier ✅
more visual ✅
budget-friendly ✅
interactive ✅
It is especially useful for beginners learning Python through a real-world project.

# 🔮 Future Improvements
Possible enhancements for this project:

Add more destinations 🌍
Improve user interface 🎨
Export trip summary as PDF 📄
Add hotel and transport recommendations 🏨
Connect with real-time map or travel APIs 🔗
Build a web app version using Flask or Streamlit 💻
🤝 Contributing
Contributions, suggestions, and improvements are welcome.
Feel free to fork this repository and create a pull request.

📜 License
This project is open-source and available under the MIT License.

# 👨‍💻 Author
Developed by Paresh Prajapati ✨
If you like this project, don’t forget to star ⭐ the repository.
