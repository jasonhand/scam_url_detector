# 🛡️ Scam URL Detector

A modern, interactive web application that helps users identify potentially malicious URLs and phishing attempts. Built with HTML, CSS, and JavaScript, this tool provides real-time URL analysis with a beautiful, user-friendly interface.

## ✨ Features

### 🔍 **URL Analysis**
- **Real-time Detection**: Analyzes URLs for common scam and phishing patterns
- **Risk Assessment**: Categorizes URLs as Safe, Suspicious, or High Risk
- **Confidence Scoring**: Provides percentage-based confidence in the analysis
- **Detailed Reports**: Lists specific risk factors and security indicators

### 🎯 **Detection Capabilities**
- **Suspicious TLDs**: Identifies dangerous top-level domains (.tk, .ml, .ga, etc.)
- **URL Shorteners**: Detects shortened URLs that hide real destinations
- **Phishing Keywords**: Recognizes common scam-related terms
- **Domain Analysis**: Checks for suspicious subdomains and patterns
- **IP Address Detection**: Flags URLs using IP addresses instead of domains
- **URL Encoding**: Identifies obfuscated URLs with excessive encoding

### 🧪 **Interactive Testing**
- **Sample URLs**: Pre-loaded examples to demonstrate the tool's capabilities
- **Click-to-Copy**: Easy copying of sample URLs for testing
- **Toast Notifications**: Visual feedback when URLs are copied
- **Analysis History**: Tracks recent URL analyses with risk levels

### 🎨 **Modern UI/UX**
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Glass Morphism**: Beautiful semi-transparent effects with backdrop blur
- **Smooth Animations**: Engaging hover effects and transitions
- **Professional Branding**: Integrated with Datadog Security Labs

## 🚀 **How It Works**

1. **Input URL**: Paste any suspicious URL into the input field
2. **Analysis**: The app examines multiple security indicators:
   - Domain reputation and structure
   - URL patterns and keywords
   - Technical indicators (ports, encoding, etc.)
   - Known legitimate domain whitelist
3. **Risk Assessment**: Calculates a risk score and confidence level
4. **Results Display**: Shows detailed analysis with specific risk factors
5. **Recommendations**: Provides clear guidance on whether to proceed

## 🔗 **Datadog Links**

Go check out the amazing open source tools from Datadog for security analysis:

- **[Guarddog CLI](https://github.com/DataDog/guarddog)**: Command-line tool for security analysis
- **[Datadog App](https://app.datadoghq.com)**: Main Datadog monitoring platform
- **[Guarddog 2.0 Release](https://securitylabs.datadoghq.com/articles/guarddog-2-0-release/)**: Blog post about the latest release

## 🛠️ **Technical Details**

### **Frontend Technologies**
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, and animations
- **Vanilla JavaScript**: No frameworks required, pure browser functionality

### **Security Features**
- **Client-side Analysis**: All processing happens in the browser
- **No Data Storage**: URLs are not stored or transmitted
- **Privacy-Focused**: No tracking or analytics

### **Browser Compatibility**
- **Modern Browsers**: Chrome, Firefox, Safari, Edge
- **Mobile Support**: Responsive design for all screen sizes
- **Progressive Enhancement**: Works without JavaScript (basic functionality)

## 📱 **Usage**

1. **Open the App**: Load `index.html` in any modern web browser
2. **Test Sample URLs**: Click on the provided examples to see how it works
3. **Analyze Your URLs**: Paste suspicious links to check their safety
4. **Review Results**: Read the detailed analysis and risk factors
5. **Make Informed Decisions**: Use the confidence score to determine if a URL is safe

## ⚠️ **Important Disclaimer**

This tool provides **basic URL analysis** and should not be your only line of defense against online threats. Always:

- Use caution when clicking on suspicious links
- Keep your software and browsers updated
- Consider using additional security tools
- When in doubt, avoid clicking the link entirely

## 🎯 **Use Cases**

- **Email Security**: Check suspicious links in emails
- **Social Media**: Verify URLs shared on social platforms
- **Business Security**: Screen links before corporate use
- **Educational Tool**: Learn about common phishing patterns
- **Security Awareness**: Train users to recognize threats

## 🔧 **Development**

### **Local Setup**
1. Clone or download the repository
2. Open `index.html` in a web browser
3. No build process or dependencies required

### **Customization**
- Modify `suspiciousPatterns` object to add new detection rules
- Update `legitimateDomains` array to whitelist trusted sites
- Adjust risk scoring thresholds in `performAnalysis()` function
- Customize UI styling in the CSS section

## 📄 **License**

This project is open source and available under the MIT License.

---

**Built with ❤️ by Datadog Security Labs**
