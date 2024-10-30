# 📹 Instagram Video Uploader Script

This Python script automates the process of uploading videos to Instagram using the Instabot library. It includes features for handling uploads with retries, cleaning up the working directory, and managing session cache. Additionally, it allows you to specify the video path, caption, and restart timer using a `.env` file. 

**Note: This is a paid tool and is not available for free.**

## 📋 Features
- Upload videos to Instagram with automatic retries.
- Clear old cache files to avoid issues with session management.
- Restart the script automatically after a specified time interval.
- Configurable video path, caption, and timer using environment variables.

## ⚙️ Requirements
- Python 3.x
- Instabot library
- `python-dotenv` library

## 🛠️ Setup

2. **Install dependencies**:
   ```bash
   pip install instabot python-dotenv
   ```

3. **Create a `.env` file**:
   Modify the file named `.env` in the root directory of your project and add the details according to yours:

   ```env
   INSTAGRAM_USERNAME=your_username
   INSTAGRAM_PASSWORD=your_password
   VIDEO_PATH=video.mov
   VIDEO_CAPTION=#anime #manga
   RESTART_TIMER=300  # Restart timer in seconds (5 minutes)
   ```

4. **Run the script**:
   Execute the script using the following command:
   ```bash
   python main.py
   ```

## ⏳ Usage
- The script will log into your Instagram account, upload the specified video, and clean up the directory after each upload attempt.
- If the upload fails, it will retry the specified number of times before cleaning up and stopping.
- After a successful upload, the script will wait for the defined restart timer before restarting.

## 📖 Important Notes
- Ensure that your Instagram account is configured to allow uploads via third-party applications.
- The `VIDEO_PATH` should point to a valid video file located in the same directory as the script.

## 🐛 Troubleshooting
- If you encounter any issues, check the log messages for errors.
- Ensure your Instagram credentials are correct in the `.env` file.



## 💼 About This Tool

This bot is a **paid tool** and is not available for free. If you're interested in using this bot, please feel free to contact me at sikandersaleem5323@gmail.com for further details and pricing. Free consultations are also available to discuss other tools that may suit your needs.
