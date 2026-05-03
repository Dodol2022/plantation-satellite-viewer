# Plantation Satellite Viewer - UI Screenshots & Mockups

## 📱 Application Overview

This document provides detailed UI mockup descriptions for all screens in the Plantation Satellite Viewer application. Follow the instructions below to generate actual screenshots on your device.

---

## 🎨 Screen 1: Main Dashboard

### Layout Description:
```
┌─────────────────────────────┐
│  Plantation Satellite View  │  ← Header (24sp)
├─────────────────────────────┤
│  [Map View - 60% of screen] │  ← Google Maps showing plantations
│                             │     with markers
│  ┌─────────────────────────┐│
│  │ Plantation A            ││
│  │ Status: Active ✓        ││
│  │ NDVI: 0.65              ││
│  └─────────────────────────┘│
├─────────────────────────────┤
│ [Bottom Sheet - 40%]        │  ← Scrollable info panel
│ ╔═════════════════════════╗ │
│ ║ 📊 Analytics Dashboard  ║ │
│ ║ Total Area: 5,000 ha    ║ │
│ ║ Avg Health: 72%         ║ │
│ ║ Last Update: 2 hours ago║ │
│ ╚═════════════════════════╝ │
├─────────────────────────────┤
│  [Navigation Bar]           │
│  🏠 Home | 📍 Search |      │
│  📤 Upload | ⚙️ Settings   │
└─────────────────────────────┘

Colors:
- Header: #2196F3 (Blue)
- Map Background: #E8F5E9 (Light Green)
- Card Background: White
- Text Primary: #212121
- Text Secondary: #757575
```

---

## 🎨 Screen 2: Search by Location

### Layout Description:
```
┌─────────────────────────────┐
│ Search Plantation by        │
│ Location                    │ ← Header
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 🔍 Enter plantation     │ │ ← Search Input Field
│ │    name, city, region...│ │
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Filter Options:             │
│ [All] [Active] [Monitored]  │ ← Filter Chips
├─────────────────────────────┤
│ Search Results:             │
│ ┌─────────────────────────┐ │
│ │ 📍 Plantation Alpha     │ │
│ │    East Jakarta, ID     │ │ ← Result Card 1
│ │    Area: 1,200 hectares │ │
│ │    Last Update: 1h ago  │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ 📍 Plantation Beta      │ │
│ │    West Surabaya, ID    │ │ ← Result Card 2
│ │    Area: 800 hectares   │ │
│ │    Last Update: 3h ago  │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ 📍 Plantation Gamma     │ │
│ │    North Medan, ID      │ │ ← Result Card 3
│ │    Area: 950 hectares   │ │
│ │    Last Update: 30m ago │ │
│ └─────────────────────────┘ │
└─────────────────────────────┘

Card Styling:
- Elevation: 2dp
- Corner Radius: 8dp
- Icon Color: #2196F3
- Background: White
- Padding: 16dp
```

---

## 🎨 Screen 3: Search by GPS Coordinates

### Layout Description:
```
┌─────────────────────────────┐
│ Search by GPS Coordinates   │ ← Header
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 📍 Use Current Location │ │ ← Green Button (4CAF50)
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Latitude Input:             │
│ ┌─────────────────────────┐ │
│ │ 🗺️ -6.1751             │ │ ← Numeric Input
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Longitude Input:            │
│ ┌─────────────────────────┐ │
│ │ 🗺️ 106.8270            │ │ ← Numeric Input
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Search Radius (meters):     │
│ ┌─────────────────────────┐ │
│ │ 1000                    │ │ ← Numeric Input (default)
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 🔍 Search              │ │ ← Blue Button (2196F3)
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ GPS Search Results:         │
│ ┌─────────────────────────┐ │
│ │ Plantation East Jakarta │ │
│ │ 📍 Distance: 0.25 km    │ │ ← Result Card 1
│ │ Health Score: 78% 🟢    │ │
│ │ GPS: -6.1751, 106.8270  │ │
│ │ Area: 1,200 ha          │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ Plantation South Block  │ │
│ │ 📍 Distance: 0.82 km    │ │ ← Result Card 2
│ │ Health Score: 65% 🟠    │ │
│ │ GPS: -6.1890, 106.8400  │ │
│ │ Area: 950 ha            │ │
│ └─────────────────────────┘ │
└─────────────────────────────┘

Health Score Colors:
- > 70%: Green (#4CAF50)
- 50-70%: Orange (#FF9800)
- < 50%: Red (#F44336)
```

---

## 🎨 Screen 4: Upload Menu (Submenu)

### Layout Description:
```
┌─────────────────────────────┐
│ Upload Options              │ ← Header
├─────────────────────────────┤
│                             │
│  ┌───────────────────────┐  │
│  │   📁 Upload SHP       │  │
│  │                       │  │ ← Card 1
│  │ Shapefile boundaries  │  │ (Elevation: 4dp)
│  │ Single or Multiple    │  │
│  └───────────────────────┘  │
│                             │
│  ┌───────────────────────┐  │
│  │   📄 Upload JSON      │  │
│  │                       │  │ ← Card 2
│  │ Configuration files   │  │ (Elevation: 4dp)
│  │ Metadata & settings   │  │
│  └───────────────────────┘  │
│                             │
│  ┌───────────────────────┐  │
│  │   📷 Upload Photo     │  │
│  │   (Single)            │  │ ← Card 3
│  │ Geotagged photo       │  │ (Elevation: 4dp)
│  │ Single image upload   │  │
│  └───────────────────────┘  │
│                             │
│  ┌───────────────────────┐  │
│  │   🖼️ Upload Photos    │  │
│  │   (Multiple)          │  │ ← Card 4
│  │ Batch geotagged       │  │ (Elevation: 4dp)
│  │ Multiple image upload │  │
│  └───────────────────────┘  │
│                             │
└─────────────────────────────┘

Card Design:
- Background: White
- Icon Size: 40dp
- Icon Colors: Blue (#2196F3)
- Text: Left-aligned
- Padding: 20dp
- Corner Radius: 12dp
- Clickable with ripple effect
```

---

## 🎨 Screen 5: File Upload - SHP

### Layout Description:
```
┌─────────────────────────────┐
│ Upload Shapefile            │ ← Header
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 📁 Select SHP Files     │ │ ← File Picker Button
│ │ Click to browse...      │ │
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Selected Files:             │
│ ✓ plantation_boundary.shp   │ ← File 1 (with checkmark)
│ ✓ plantation_boundary.shx   │ ← File 2
│ ✓ plantation_boundary.dbf   │ ← File 3
├─────────────────────────────┤
│ File Info:                  │
│ Total Size: 2.4 MB          │
│ Files Selected: 3/3         │
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 📤 Upload Now           │ │ ← Upload Button
│ └─────────────────────────┘ │
│                             │
│ Upload Progress:            │
│ ████████░░░░░░░░░░ 40%      │ ← Progress Bar
└─────────────────────────────┘
```

---

## 🎨 Screen 6: File Upload - Multiple Photos

### Layout Description:
```
┌─────────────────────────────┐
│ Upload Geotagged Photos     │ ← Header
│ (Multiple)                  │
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 📷 Select Photos        │ │ ← Gallery Picker Button
│ │ From Gallery            │ │
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Selected Photos:            │
│ ┌─────┬─────┬─────┐        │
│ │ 📷  │ 📷  │ 📷  │        │ ← Photo 1, 2, 3 thumbnails
│ │1.2MB│1.5MB│0.9MB│        │
│ └─────┴─────┴─────┘        │
│ ┌─────┬─────┐              │
│ │ 📷  │ 📷  │              │ ← Photo 4, 5 thumbnails
│ │2.1MB│1.8MB│              │
│ └─────┴─────┘              │
├─────────────────────────────┤
│ Photo Info:                 │
│ Total Photos: 5             │
│ Total Size: 7.5 MB          │
│ GPS Data Found: 5/5 ✓       │ ← All geotagged
├─────────────────────────────┤
│ Photo Metadata Example:     │
│ Photo 1:                    │
│ - GPS: -6.1751, 106.8270    │
│ - Time: 2024-05-03 14:30    │
│ - Size: 1.2 MB              │
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 📤 Upload All Photos    │ │ ← Upload Button
│ └─────────────────────────┘ │
│                             │
│ Upload Progress:            │
│ ██████████░░░░░░░░░░ 50%    │ ← Progress Bar
└─────────────────────────────┘
```

---

## 🎨 Screen 7: Analytics Dashboard

### Layout Description:
```
┌─────────────────────────────┐
│ Analytics & Monitoring      │ ← Header
├─────────────────────────────┤
│                             │
│ Summary Cards (Row 1):      │
│ ┌──────────┬──────────────┐ │
│ │ 📊 5,000 │ 📈 +250 ha   │ │
│ │ Total ha │ This Month   │ │
│ └──────────┴──────────────┘ │
│                             │
│ Summary Cards (Row 2):      │
│ ┌──────────┬──────────────┐ │
│ │ 🟢 72%   │ 📸 245 Photos│ │
│ │ Avg NDVI │ Captured     │ │
│ └──────────┴──────────────┘ │
├─────────────────────────────┤
│                             │
│ NDVI Health Trend (Chart):  │
│   100% │     ╱╲     ╱╲      │
│   80%  │    ╱  ╲   ╱  ╲     │
│   60%  │   ╱    ╲ ╱    ╲    │ ← Line Chart
│   40%  │──────────────────   │
│        └────────────────────  │
│        Jan  Feb  Mar  Apr    │
│                             │
├─────────────────────────────┤
│ Plantation Status:          │
│ Active:   45 plantations    │
│ Inactive: 5 plantations     │
│ Monitoring: 42 plantations  │
│                             │
├─────────────────────────────┤
│ Recent Updates:             │
│ • Plantation Alpha updated  │
│   2 hours ago               │
│ • 3 photos uploaded to      │
│   Plantation Beta           │
│ • Health score improved     │
│   by 5% in Gamma area       │
└─────────────────────────────┘

Colors:
- Healthy: #4CAF50 (Green)
- Warning: #FF9800 (Orange)
- Critical: #F44336 (Red)
- Chart Line: #2196F3 (Blue)
```

---

## 📸 How to Generate Actual Screenshots

### Step 1: Build & Run the App
```bash
# In Android Studio
1. Click "Run" button (Shift + F10)
2. Select your target device/emulator
3. Wait for the app to build and install
```

### Step 2: Navigate to Each Screen
1. **Main Dashboard**: Opens automatically when app launches
2. **Search by Location**: Tap "📍 Search" in bottom navigation
3. **Search by GPS**: Tap "📍 Search" → Select "GPS Coordinates"
4. **Upload Menu**: Tap "📤 Upload" in bottom navigation
5. **File Upload Screens**: Select specific upload option
6. **Analytics Dashboard**: Tap "📊 Analytics" in menu

### Step 3: Capture Screenshots

**On Emulator:**
- Press `Ctrl + S` (Windows/Linux) or `Cmd + S` (Mac)
- Or: `Android Studio → Logcat → Camera Icon`

**On Physical Device:**
- Press `Volume Down + Power Button` simultaneously
- Screenshot saved to device gallery

### Step 4: Take Screenshots of Each Screen
```
Required Screenshots:
□ Main Dashboard
□ Search by Location (with results)
□ Search by GPS (with results)
□ Upload Menu
□ SHP File Upload
□ Multiple Photos Upload
□ Analytics Dashboard
□ Settings Screen
```

---

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Blue | #2196F3 | Headers, buttons, icons |
| Success Green | #4CAF50 | Healthy status, uploads |
| Warning Orange | #FF9800 | Caution, medium priority |
| Error Red | #F44336 | Critical, errors |
| Light Background | #F5F5F5 | Screen backgrounds |
| Card White | #FFFFFF | Cards, content areas |
| Text Primary | #212121 | Headings, main text |
| Text Secondary | #757575 | Subtitles, hints |

---

## 📝 Typography

| Element | Font Size | Weight | Usage |
|---------|-----------|--------|-------|
| Header | 24sp | Medium | Screen titles |
| Title | 18sp | Medium | Card titles |
| Subtitle | 14sp | Regular | Secondary info |
| Body | 14sp | Regular | Main content |
| Caption | 12sp | Regular | Hints, details |
| Button | 16sp | Medium | Action buttons |

---

## ✅ Testing Checklist

- [ ] All screens render correctly
- [ ] Navigation flows smoothly
- [ ] Search results load and display properly
- [ ] File uploads show progress
- [ ] Charts display data accurately
- [ ] GPS functionality works
- [ ] Maps integration functional
- [ ] All buttons are clickable
- [ ] Error messages appear appropriately
- [ ] Performance is smooth (no lag)