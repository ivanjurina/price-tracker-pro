# price-tracker-pro

A powerful Chrome extension for tracking prices across any shopping website with multi-currency support, price history visualization, and comparison features.

## Features

- 🌐 Works on any shopping website
- 💰 Multi-currency support (USD, EUR, GBP, JPY)
- 📊 Price history visualization with interactive charts
- 📥 Export data to CSV and JSON formats
- 🔄 Automatic price checking (hourly)
- 🔔 Price drop notifications
- 🔍 Basic price comparison across sites
- 📱 Responsive popup interface

## Installation

### For Users
1. Download the latest release from the releases page
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the downloaded folder

### For Developers
```bash
# Clone the repository
git clone https://github.com/ivanjurina/price-tracker-pro.git

# Navigate to the project directory
cd price-tracker-pro

# Install dependencies (if any)
# Note: This project currently doesn't require npm dependencies
```

## Usage

1. Visit any product page on a shopping website
2. Click the extension icon to see current price information
3. Set price alerts and view price history
4. Export data in CSV or JSON format
5. Compare prices across different sites

## Screenshots
[Add screenshots here]

## Technical Details

### Files Structure
```
price-tracker-pro/
├── manifest.json
├── background.js
├── content.js
├── popup.html
├── popup.js
├── icons/
│   ├── icon16.png
│   ├── icon48.png
│   └── icon128.png
└── README.md
```

### Supported Features
- Price detection across various website layouts
- Currency conversion
- Price history tracking
- Data export functionality
- Price comparison (basic implementation)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Improvements

- [ ] Add support for more currencies
- [ ] Implement real-time currency conversion using an API
- [ ] Add more advanced price comparison features
- [ ] Implement machine learning for price prediction
- [ ] Add support for browser sync
- [ ] Improve price detection algorithm
- [ ] Add support for batch tracking multiple products

## License

Distributed under the MIT License. See `LICENSE` for more information.

* Chart.js for price history visualization
* Chrome Extensions API
* All contributors and users of this project
