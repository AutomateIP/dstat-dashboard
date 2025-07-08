# dstat-dashboard

> **A comprehensive web-based performance monitoring dashboard for analyzing dstat CSV output files**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-3.9.1-ff6384.svg)](https://www.chartjs.org/)

Transform your dstat system monitoring data into beautiful, interactive visualizations with this comprehensive web dashboard. Simply upload your dstat CSV files and get instant insights into CPU usage, memory consumption, disk I/O, network activity, and system performance trends.

![dstat Dashboard Screenshot](https://via.placeholder.com/800x400?text=Dashboard+Screenshot+Here)

## 🚀 Quick Start

1. **Generate dstat data**:
   ```bash
   dstat -cdnmg --top-cpu --top-io --top-mem --output mydata.csv 3
   ```

2. **Open the dashboard**:
   - Download or clone this repository
   - Open `index.html` in any modern web browser
   - No installation, server, or setup required!

3. **Upload & Analyze**:
   - Drag and drop your CSV file or click to browse
   - Instantly view comprehensive performance metrics
   - Explore interactive charts and statistics

## ✨ Features

### 📊 **Comprehensive Performance Metrics**
- **CPU Analysis**: User, System, Idle, and Total Utilization tracking
- **Memory Monitoring**: Used vs Free memory with trend analysis
- **Disk I/O**: Read/Write operations and throughput visualization
- **Network Activity**: Receive/Send bandwidth monitoring
- **Paging Statistics**: Memory paging activity tracking

### 🎯 **Interactive Visualizations**
- Real-time charts with zoom and pan capabilities
- Multiple time-series graphs for different metrics
- Hover tooltips with detailed information
- Responsive design for desktop and mobile

### 📈 **Smart Analytics**
- Automatic calculation of key performance indicators
- Statistical summaries (averages, peaks, totals)
- Top resource consumer identification
- System information extraction from dstat headers

### 🔧 **Easy to Use**
- **Zero Installation**: Pure HTML/JavaScript - runs in any browser
- **Drag & Drop**: Simple file upload interface
- **Instant Analysis**: No server required, everything runs locally
- **Format Support**: Works with standard dstat CSV output

## 📊 What You Get

### System Overview Dashboard
- Host information and monitoring parameters
- Total records and monitoring duration
- Top CPU and memory consuming processes

### Key Performance Statistics
- Average CPU utilization percentage
- Peak memory usage and trends
- Maximum network throughput rates
- Disk I/O operation statistics
- System load pattern analysis

### Interactive Charts
- **CPU Usage Chart**: Multi-line visualization showing user, system, and idle percentages
- **Memory Usage Chart**: Used vs available memory over time
- **Disk I/O Chart**: Read/write operations visualization
- **Network I/O Chart**: Bandwidth utilization tracking
- **Paging Activity Chart**: Memory paging statistics

## 💻 Technical Details

- **Frontend Only**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Chart Library**: Chart.js for interactive visualizations
- **CSV Processing**: Client-side parsing with Papa Parse
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Browser Support**: Chrome, Firefox, Safari, Edge (modern browsers)

## 🔧 dstat Command Examples

### Basic Monitoring (Recommended)
```bash
dstat -cdnmg --top-cpu --top-io --top-mem --output dstat.csv 3
```

### Extended Monitoring
```bash
dstat -cdnmgry --top-cpu --top-io --top-mem --top-bio --output extended.csv 5
```

### Long-term Monitoring
```bash
dstat -cdnmg --top-cpu --top-io --top-mem --output longterm.csv 60
```

### What the flags mean:
- `-c`: CPU stats
- `-d`: Disk stats
- `-n`: Network stats
- `-m`: Memory stats
- `-g`: Paging stats
- `--top-cpu`: Show most CPU-intensive process
- `--top-io`: Show most I/O-intensive process
- `--top-mem`: Show most memory-intensive process
- `--output`: Save to CSV file
- `3`: Sample interval in seconds

## 🎯 Use Cases

### 👨‍💻 **System Administrators**
- Monitor server performance over time
- Identify resource bottlenecks and capacity issues
- Troubleshoot performance problems
- Plan capacity upgrades and optimizations

### 🔧 **DevOps Engineers**
- Application performance monitoring
- Infrastructure health checks and alerting
- Performance regression analysis
- Resource utilization tracking and optimization

### ⚡ **Performance Engineers**
- Baseline performance measurement
- Load testing analysis and validation
- System optimization validation
- Performance trend identification and forecasting

## 🛠️ Development

### Built With
- **Vanilla JavaScript** - No framework dependencies
- **Chart.js** - Interactive chart visualizations
- **Papa Parse** - CSV file processing
- **Modern CSS** - Flexbox/Grid responsive layouts

### Project Structure
```
dstat-dashboard/
├── index.html              # Main dashboard application
├── README.md              # This file
├── LICENSE               # MIT License
└── screenshots/          # Dashboard screenshots
```

### Contributing
Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug or have a feature request? [Open an issue](../../issues)
2. **Submit PRs**: Fork the repo, make changes, and submit a pull request
3. **Improve Docs**: Help make the documentation better
4. **Share Feedback**: Let us know how you're using the dashboard

### Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/dstat-dashboard.git

# Navigate to the project directory
cd dstat-dashboard

# Open in browser (no build step required)
open index.html
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built for the dstat and system monitoring community
- Inspired by system administrators and performance engineers worldwide
- Powered by modern web technologies and open-source libraries

## 📞 Support

- **Issues**: [GitHub Issues](../../issues)
- **Questions**: [GitHub Discussions](../../discussions)
- **Documentation**: This README and inline code comments

---

**⭐ If you find this project useful, please consider giving it a star!**

*Transform your system monitoring data into actionable insights with beautiful visualizations.*