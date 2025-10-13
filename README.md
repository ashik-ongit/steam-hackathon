# 🎮 Steam Game Explorer

A sleek game search web app built for the **Google Cloud Hackathon 2025**, powered by MongoDB Atlas and Streamlit.

---

## 🚀 Features

- 🔍 Search Steam games by title
- 📊 View game genre, price, developer, publisher, and more
- 🖼️ Game image previews
- 🔁 Realtime search from MongoDB database
- ✨ Neon UI vibes + animated background GIF

---

## 🔧 Tech Stack

- **Frontend & UI**: Streamlit
- **Backend**: Python
- **Database**: MongoDB Atlas
- **Data Format**: JSON

---

## 🗃 Project Structure

```
steam-hackathon/
│
├── app.py                    # Main app file (Streamlit)
├── steam_games_15.json       # Game dataset
├── requirements.txt          # Python dependencies
├── giff/                     # Background GIF folder
├── games_data/               # (optional) more data files
├── demo_video_of_web.mp4     # Demo walkthrough
├── hackathon_screenshots/    # Folder of screenshots
└── README.md                 # You’re reading this!
```

---

## 📽️ Demo

- 📸 Screenshots → in `hackathon_screenshots/`  
- 🎥 Demo video → `demo_video_of_web.mp4`

Game search examples include:
- Counter Strike
- GTA
- Half-Life
- NFS
- Team Fortress
- Left 4 Dead  
...and more.

---

## ⚙️ How to Run

> 💡 You need Python 3.x installed!

1. Clone or download the repo:
   ```bash
   git clone https://github.com/your-username/steam-hackathon.git
   cd steam-hackathon
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the app:
   ```bash
   streamlit run app.py
   ```

4. Make sure your MongoDB Atlas URI is set in `app.py`:
   ```python
   client = pymongo.MongoClient("your_mongodb_atlas_uri")
   ```

---

## 📦 Dependencies

Saved in `requirements.txt`:
```
streamlit
pymongo
pandas
```

---

## 🙌 Author

**🚀 Built by Ashik K**  
🔗 [LinkedIn](https://www.linkedin.com/in/ashik2212)

---

## 🏁 Submission

This project is built for the [Google Cloud Hackathon 2025](https://devpost.com) under:

- MongoDB Track
- GitLab Track

🎯 Focus: Clean UI, practical functionality, and simple data-powered search.

---

## 📝 License

MIT License – feel free to use, modify & improve!



BDO|e1`z1v`cm44E~

