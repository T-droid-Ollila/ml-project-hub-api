# ml-project-hub-api
# 🚀 GitHub Repository Analyzer (API + Data Pipeline)

## 📌 Overview

This project uses the **GitHub API** to automatically fetch, clean, and analyze top Machine Learning and Data Science repositories.

Instead of manually searching for projects, this pipeline helps you:

* Discover high-quality repositories
* Save them for offline use
* Analyze trends in the developer ecosystem

---

## ⚙️ Features

* 🔍 Fetch repositories using the GitHub API
* 🔁 Pagination to retrieve large datasets
* 🧹 Data cleaning and preprocessing
* 📊 Structured dataset (CSV + JSON output)
* 📈 Basic analysis (top repos, stars, languages)

---

## 🧠 Tech Stack

* Python
* pandas
* requests
* JSON
* pathlib

---

## 🔗 API Used

* GitHub Search API

---

## 📂 Project Structure

```
project/
│── sample_data/
│   ├── pagination.json
│   ├── cleaned_repositories.json
│   └── cleaned_repositories.csv
│
│── main.py
│── README.md
```

---

## 🚀 How It Works

### 1. Fetch Data

* Uses the GitHub API to retrieve repositories
* Implements pagination to collect multiple pages

### 2. Clean Data

* Handles missing values
* Selects relevant columns
* Renames fields for clarity
* Sorts repositories by popularity (stars)

### 3. Save Data

* JSON (raw data)
* CSV (cleaned dataset)

---

## ▶️ How to Run

### 1. Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```
pip install pandas requests
```

### 3. Run the script

```
python main.py
```

---

## 📊 Example Output

| repo_name                 | stars   | url                    |
| ------------------------- | ------- | ---------------------- |
| tensorflow/tensorflow     | 180000+ | https://github.com/... |
| scikit-learn/scikit-learn | 60000+  | https://github.com/... |

---

## 💡 Use Cases

* Beginners looking for ML/DS projects
* Data analysis on GitHub trends
* Building datasets for ML models
* Automating project discovery

---

## 🔥 Future Improvements

* Add visualization dashboard (Power BI / matplotlib)
* Build a recommendation system for repositories
* Automate daily data collection
* Deploy as a web app

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---
## 📜 License

This project is open-source and available under the MIT License.
---

## 👨‍💻 Author

**Ollila Simiyu**
www.linkedin.com/in/ollila-simiyu-a9b886363
