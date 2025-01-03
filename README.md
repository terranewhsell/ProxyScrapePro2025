# Proxy Scraper Pro 2025 🌐

A professional and modern tool for proxy scraping, validation, and management.

## 🌟 Main Features

### Proxy Scraping
- **Multiple Sources**: Over 20 reliable sources including:
  - Github-clarketm
  - Github-TheSpeedX
  - Github-ShiftyTR
  - Github-hookzof
  - Github-monosans
  - Github-mertguvencli
  - ProxyNova
  - SSLProxies
  - FreeProxyList
  - And many more...

- **Protocol Filtering**:
  - HTTP
  - HTTPS
  - SOCKS4
  - SOCKS5

### Proxy Validation
- Real-time validation
- Response time measurement
- Automatic detection of:
  - Country
  - Protocol
  - Anonymity level
- Real-time progress counter
- Customizable test URL

### Favorites Management
- Mark proxies as favorites (★)
- Persistent favorites list
- Export favorites
- Individual favorites management

### Export and Save
- **Multiple Formats**:
  - IP:Port
  - http://IP:Port
  - https://IP:Port
  - socks4://IP:Port
  - socks5://IP:Port
- Excel export
- Custom file names
- Overwrite verification

### User Interface
- Modern and professional design
- Light/Dark mode
- Multi-language support:
  - English (default)
  - Spanish
  - French
  - German
  - Chinese
  - Russian
  - Dutch
- Sortable table columns
- Real-time statistics

## 📋 User Manual

### 1. Getting Proxies
1. Select desired sources in the "Sources" section
2. Set a proxy limit (optional)
3. Select desired protocol (or "all")
4. Click "⚡ Get Proxies"

### 2. Validation
1. Enter a test URL (optional)
2. Select proxies to validate
3. Click "✓ Validate"
4. Watch real-time progress

### 3. Favorites Management
- **Add to Favorites**:
  1. Select a proxy
  2. Click "★ Add" or use context menu (right-click)
  
- **View Favorites**:
  1. Click "View Favorites"
  2. Manage favorites list
  3. Export or delete favorites

### 4. Export
- **Save Proxies**:
  1. Click "Save Proxies"
  2. Select desired format
  3. Enter custom name
  4. Confirm operation

- **Export to Excel**:
  1. Click "Export to Excel"
  2. File will be saved in "resources" folder

### 5. Additional Features
- **Sort**: Click column headers
- **Copy Proxy**: Double click or context menu
- **Change Language**: Language menu in top bar
- **Change Theme**: Dark/Light mode button
- **Filter by Country**: Tools menu > Filter by Country
- **Remove Duplicates**: Tools menu > Remove Duplicates

## 🛠️ Technical Requirements
- Python 3.7 or higher
- Required libraries:
  - tkinter
  - requests
  - beautifulsoup4
  - pandas (for Excel export)

## 📁 File Structure
- `main.py`: Main application
- `scraper.py`: Proxy scraping module
- `validator.py`: Validation module
- `ui_helper.py`: Interface components
- `styles.py`: Styles and themes
- `languages.py`: Translations
- `resources/`: Folder for saved files

## 🔧 Installation
1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the program:
```bash
python main.py
```

## 📝 Additional Notes
- Proxies are validated against specified URL
- Favorites are saved automatically
- "resources" folder is created automatically
- Exported files include timestamp

## 🔒 Security
- No personal information is sent
- No registration required
- Open source and verifiable
- No external connections except for validation

## 🤝 Contributions
Contributions are welcome. Please open an issue first to discuss proposed changes.

## 📄 License
This project is under the MIT License. See the LICENSE file for details. 