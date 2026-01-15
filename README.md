# AirSense - Mobile Air Quality Monitor

A professional mobile app for monitoring air quality in real-time using the AirSense wearable sensor device. Track CO2, VOCs, NOx, temperature, and humidity directly on your iPhone or Android device.

## Features

- **Real-time Monitoring:** Live CO2, VOC, NOx, temperature, and humidity readings
- **Historical Data:** Track air quality trends over time with interactive charts
- **Smart Alerts:** Customizable notifications when air quality drops below safe levels
- **Bluetooth Connectivity:** Wireless connection to your AirSense sensor device
- **Cross-Platform:** Available on iOS, Android, and web browsers

## Supported Platforms

- ✅ **iOS** - iPhone and iPad (iOS 13+)
- ✅ **Android** - Android 8.0+
- ✅ **Web** - Chrome, Edge, Firefox (desktop and Android only)

## Installation

### iOS (iPhone/iPad)

**Option 1: Expo Go (Recommended for Testing)**
1. Download **Expo Go** from the App Store (free)
2. Contact support for access QR code
3. Scan QR code to launch the app

**Option 2: TestFlight Beta**
- Request TestFlight access (coming soon)

### Android

**Option 1: Expo Go**
1. Download **Expo Go** from Google Play
2. Contact support for access QR code
3. Scan QR code to launch the app

**Option 2: APK Install**
- Download APK (coming soon)

### Web Browser

Visit: https://havamal-65.github.io/air-quality-sensor

**Compatibility:**
- ✅ Android Chrome/Edge - Full BLE support
- ✅ Desktop Chrome/Edge - Demo mode
- ⚠️ iOS Safari - Demo mode only (use native app for full functionality)

## Getting Started

### First Time Setup

1. **Charge Your AirSense Device**
   - Fully charge before first use
   - LED indicator shows charging status

2. **Install the App**
   - Choose your platform (iOS/Android/Web)
   - Follow installation instructions above

3. **Connect to Device**
   - Open the app
   - Tap "Connect to Device"
   - Select your AirSense sensor from the list
   - Grant Bluetooth permissions when prompted

4. **Start Monitoring**
   - View real-time air quality data
   - Set up custom alerts in Settings
   - Review historical trends in History tab

## Air Quality Guidelines

### CO2 Levels
| Level | Range (ppm) | Indicator | Recommendation |
|-------|-------------|-----------|----------------|
| Excellent | < 600 | 🟢 Green | Ideal air quality |
| Good | 600-800 | 🟢 Green | Good ventilation |
| Moderate | 800-1000 | 🟡 Yellow | Consider opening windows |
| Poor | 1000-1500 | 🟠 Orange | Ventilate immediately |
| Bad | > 1500 | 🔴 Red | Poor ventilation - take action |

### VOC Index
| Level | Range | Indicator | Recommendation |
|-------|-------|-----------|----------------|
| Good | 0-150 | 🟢 Green | Safe levels |
| Moderate | 150-250 | 🟡 Yellow | Monitor for sources |
| Poor | 250-400 | 🟠 Orange | Identify and ventilate |
| Bad | > 400 | 🔴 Red | Remove VOC source immediately |

## App Features

### Home Screen
- Real-time sensor readings
- Overall air quality score
- Color-coded status indicators
- Quick connection status

### History
- Interactive charts showing trends
- Filter by time range (hour, day, week, month)
- Export data (coming soon)

### Recommendations
- Personalized tips based on current readings
- Health impact information
- Suggested actions to improve air quality

### Settings
- Customize alert thresholds
- Enable/disable notifications
- Dark mode toggle
- Device information
- App version and updates

## Troubleshooting

### Can't Connect to Device

1. **Check Bluetooth:**
   - Ensure Bluetooth is enabled on your phone
   - Grant location permission (required for iOS/Android BLE)

2. **Check Device:**
   - Ensure AirSense device is powered on
   - Check battery level
   - Try moving closer to the device

3. **Restart:**
   - Close and reopen the app
   - Turn Bluetooth off and on
   - Restart your phone if issues persist

### iOS Safari Web App Shows Demo Mode

This is normal - Apple restricts Web Bluetooth on iOS Safari.
**Solution:** Install the native iOS app via Expo Go or TestFlight for full functionality.

### Android Connection Issues

1. Grant all permissions:
   - Bluetooth
   - Location (required for BLE scanning)
2. Check battery optimization settings
3. Try restarting Bluetooth

### Data Not Updating

- Ensure device is within Bluetooth range (10m/33ft)
- Check device battery level
- Reconnect to device
- Close other apps using Bluetooth

## Support

For technical support or questions:
- **Email:** support@airsense.app (update with your actual contact)
- **GitHub Issues:** https://github.com/havamal-65/air-quality-sensor-iOS/issues

## Privacy

- All data is stored locally on your device
- No cloud storage or data collection
- Bluetooth connection is secure and encrypted
- No personal information is required

## System Requirements

**iOS:**
- iOS 13.0 or later
- iPhone 6s or newer
- iPad (5th generation) or newer
- Bluetooth 5.0 compatible

**Android:**
- Android 8.0 (Oreo) or later
- Bluetooth 5.0 compatible
- Minimum 2GB RAM recommended

**Web:**
- Chrome 56+, Edge 79+, Firefox 52+
- Bluetooth adapter required for real device connection

## Technology

Built with:
- React Native & Expo SDK 54
- Bluetooth Low Energy (BLE) protocol
- Real-time data visualization
- Cross-platform compatibility

## License

Copyright © 2026 AirSense. All rights reserved.

For licensing inquiries, contact: licensing@airsense.app

---

**Note:** This repository contains the mobile app code. The AirSense hardware device is sold separately. Contact sales for hardware purchase information.
