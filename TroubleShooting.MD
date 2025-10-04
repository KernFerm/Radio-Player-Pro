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
