# AirSense - iOS Air Quality Monitor

Professional iOS app for monitoring air quality in real-time using the AirSense wearable sensor device. Track CO2, VOCs, NOx, temperature, and humidity directly on your iPhone or iPad.

## Features

- **Real-time Monitoring:** Live CO2, VOC, NOx, temperature, and humidity readings
- **Historical Data:** Track air quality trends over time with interactive charts
- **Smart Alerts:** Customizable notifications when air quality drops below safe levels
- **Bluetooth Connectivity:** Wireless connection to your AirSense sensor device
- **Native iOS Performance:** Optimized for iPhone and iPad

## System Requirements

- iOS 13.0 or later
- iPhone 6s or newer / iPad (5th generation) or newer
- Bluetooth 5.0 compatible
- 50MB free storage space

## Installation

### Option 1: Expo Go (Recommended for Beta Testing)
1. Download **Expo Go** from the App Store (free)
2. Contact support for access QR code
3. Scan QR code with your iPhone camera
4. App opens automatically in Expo Go

### Option 2: TestFlight Beta
- Request TestFlight access: support@airsense.app
- Installation link will be sent via email
- Tap link on your iPhone to install

### Option 3: App Store (Coming Soon)
- Search "AirSense" in the App Store
- Tap "Get" to download and install

## Getting Started

### First Time Setup

1. **Charge Your AirSense Device**
   - Fully charge before first use
   - LED indicator shows charging status
   - Approximately 2 hours for full charge

2. **Launch the App**
   - Open AirSense on your iPhone
   - Grant Bluetooth permissions when prompted
   - Grant Location permissions (required for BLE scanning on iOS)

3. **Connect to Your Device**
   - Tap "Connect to Device"
   - Select your AirSense sensor from the list
   - Wait for connection to establish (5-10 seconds)
   - Green indicator shows successful connection

4. **Start Monitoring**
   - View real-time air quality data on Home screen
   - Swipe to History tab to view trends
   - Tap Settings to customize alerts

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
- Real-time sensor readings with color-coded status
- Overall air quality score (0-100)
- Connection status indicator
- Last updated timestamp
- Quick view of all sensors

### History Tab
- Interactive charts showing 24-hour trends
- Filter by time range (1 hour, 6 hours, 24 hours, 7 days)
- Tap any data point for detailed reading
- Scroll to view historical data
- Export data (coming soon)

### Recommendations Tab
- Personalized tips based on current readings
- Health impact information
- Suggested actions to improve air quality
- Links to more information

### Settings Tab
- **Alerts:** Customize CO2 and VOC thresholds
- **Notifications:** Enable/disable push notifications
- **Dark Mode:** Toggle between light and dark themes
- **Device Info:** View connected device details
- **About:** App version and support information

## Troubleshooting

### Can't Connect to Device

**Check Bluetooth:**
1. Open Settings → Bluetooth
2. Ensure Bluetooth is ON
3. Check that AirSense device is powered on
4. Try moving closer to the device (within 10 feet)

**Grant Permissions:**
1. Open Settings → Privacy & Security → Bluetooth
2. Find AirSense app
3. Ensure permission is set to "Allow"
4. Also check Location Services permission (required for BLE)

**Restart Connection:**
1. Close the AirSense app completely
2. Turn Bluetooth OFF then ON again
3. Restart the AirSense device
4. Reopen app and try connecting again

### Data Not Updating

- Ensure device is within Bluetooth range (10m/33ft)
- Check device battery level (LED indicator)
- Try disconnecting and reconnecting
- Force close app and reopen

### Notifications Not Working

1. Open Settings → Notifications → AirSense
2. Ensure "Allow Notifications" is enabled
3. Check alert thresholds in app Settings tab
4. Verify current readings exceed threshold values

### App Crashes or Freezes

1. Force close the app
2. Restart your iPhone
3. Ensure iOS is up to date (Settings → General → Software Update)
4. Reinstall the app if issue persists

### Battery Draining Quickly

- Bluetooth connections consume power
- Close app when not actively monitoring
- Reduce notification frequency in Settings
- Ensure iPhone Low Power Mode is disabled for best performance

## Privacy & Data

- **Local Storage:** All data is stored only on your iPhone
- **No Cloud Sync:** Your air quality data never leaves your device
- **No Account Required:** No login or personal information needed
- **Bluetooth Security:** Encrypted BLE connection to sensor
- **No Tracking:** We do not collect any usage data or analytics

## Support

**Technical Support:**
- Email: support@airsense.app
- Response time: Within 24 hours

**Report a Bug:**
- GitHub Issues: https://github.com/havamal-65/air-quality-sensor-iOS/issues
- Include iOS version and device model

**Feature Requests:**
- Email: feedback@airsense.app
- We love hearing your ideas!

## Device Compatibility

**Fully Supported:**
- iPhone 15 series (all models)
- iPhone 14 series (all models)
- iPhone 13 series (all models)
- iPhone 12 series (all models)
- iPhone 11 series (all models)
- iPhone XS, XR, X
- iPhone 8, 8 Plus
- iPhone SE (2nd & 3rd generation)
- iPad Pro (all models with iPadOS 13+)
- iPad Air (3rd generation and later)
- iPad (5th generation and later)
- iPad mini (5th generation and later)

**Minimum Requirements:**
- iPhone 6s or later
- iPadOS 13.0 or later

## Technology

Built with:
- React Native & Expo SDK 54
- Bluetooth Low Energy (BLE) 5.0 protocol
- Native iOS performance optimizations
- Real-time data visualization with React Native Chart Kit

## What's Included

**With Your Purchase:**
- AirSense wearable sensor device
- Free iOS app (download from App Store)
- USB charging cable
- Quick start guide
- 1-year warranty

**Not Included:**
- iPhone or iPad (required to run app)
- Optional carrying case (sold separately)

## Updates

**App Updates:**
- Automatic updates via App Store
- Check Settings → About for current version
- Update notifications when new features available

**Firmware Updates:**
- Device firmware updates via app (coming soon)
- Automatic update prompts when available

## License

Copyright © 2026 AirSense. All rights reserved.

This app is licensed for use with AirSense hardware devices only. Unauthorized use, reproduction, or distribution is prohibited.

For licensing inquiries: licensing@airsense.app

---

**Need Help?** Email support@airsense.app or visit our GitHub for documentation.

**Purchase AirSense Device:** Contact sales@airsense.app
