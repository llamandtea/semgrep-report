# Semgrep Report Viewer

A modern, interactive HTML viewer for Semgrep JSON reports that makes security findings easy to understand and navigate.

![Semgrep Report Viewer Screenshot](https://github.com/xsafetech/semgrep-report/blob/main/iShot_2024-12-11_14.10.45.png)

## Features

- 🎯 **Clean, Modern Interface**: Beautifully designed UI that makes security findings easy to read and understand
- 🔍 **Smart Filtering**: Filter vulnerabilities by severity level (High, Medium, Low)
- 📊 **Statistics Dashboard**: Quick overview of total findings and breakdown by severity
- 🎨 **Visual Severity Indicators**: Color-coded cards and badges for immediate severity recognition
- 📝 **Detailed Information**: View complete vulnerability details including:
  - Vulnerability title and description
  - File location and line numbers
  - Relevant code snippets
- 💻 **Standalone HTML**: Single HTML file with no external dependencies

## Getting Started

1. Generate a Semgrep JSON report:
```bash
semgrep scan --json -o report.json
```

2. Download the `semgrep-report.html` file from this repository

3. Open the HTML file in your browser and click "Load Report" to upload your Semgrep JSON report

That's it! Your Semgrep findings will be displayed in a clean, organized interface.

## Usage

1. **Loading a Report**:
   - Click the "Load Report" button in the top right
   - Select your Semgrep JSON report file
   - The report will automatically be parsed and displayed

2. **Filtering Results**:
   - Click on the severity cards (High, Medium, Low) to filter findings
   - Click "Total Findings" to show all results

3. **Viewing Details**:
   - Each finding card shows the vulnerability title, description, and affected code
   - File paths and line numbers are clearly displayed
   - Code snippets are syntax highlighted for better readability

## Technical Details

- Built with vanilla JavaScript - no frameworks or external dependencies
- Uses TailwindCSS (included via CDN) for styling
- Fully client-side - no server required
- Mobile-responsive design

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Here are some ways you can contribute:

- 🐛 Report bugs
- ✨ Request features
- 📝 Improve documentation
- 🎨 Enhance UI/UX
- 💻 Add new features

## License

MIT License - feel free to use this tool in your security workflows!

## Acknowledgments

- Built with [TailwindCSS](https://tailwindcss.com/)
- Inspired by various security report visualization tools
- Thanks to the Semgrep team for their amazing security scanner
