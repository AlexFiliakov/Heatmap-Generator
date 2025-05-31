# Marketing Heatmap Tool - User Guide

## Quick Start (No Setup Required!)

1. **Save the Tool**: Save the HTML file to your computer
2. **Open in Browser**: Double-click the file to open it in Chrome, Firefox, Safari, or Edge
3. **Upload Your Data**: Drag and drop your CSV file or click to browse
4. **Configure**: Select your data fields from the dropdowns
5. **Export**: Download as PNG for PowerPoint or as an interactive HTML file

## Features for Marketing Professionals

### 🎯 Designed for You
- **No coding required** - Everything works through simple dropdowns and buttons
- **Runs in your browser** - No software to install or IT tickets to submit
- **Your data stays private** - All processing happens on your computer
- **Professional output** - Export presentation-ready charts at 300 DPI

### 📊 What You Can Visualize
- **Campaign Performance**: Compare partners across multiple metrics
- **Geographic Analysis**: Regions vs. performance indicators  
- **Time-based Trends**: Months/quarters vs. KPIs
- **Product Comparisons**: Products vs. customer segments
- **Channel Analysis**: Marketing channels vs. conversion metrics

## Step-by-Step Instructions

### 1. Prepare Your Data

Your CSV file should have:
- **Column headers** in the first row
- **At least 3 columns**: One for rows, one for columns, one for values

Example data structure:
```
Partner,Region,Performance Score
Partner A,North,85
Partner B,South,72
Partner C,North,91
```

### 2. Upload Your File

- **Drag & Drop**: Simply drag your CSV file onto the upload area
- **Click to Browse**: Or click the upload area to select your file
- The tool will show a success message with the number of rows loaded

### 3. Configure Your Heatmap

#### Select Your Data Fields:
- **X-Axis (Columns)**: What appears across the top (e.g., Regions, Time Periods)
- **Y-Axis (Rows)**: What appears down the side (e.g., Partners, Products)
- **Heatmap Values**: The numbers that determine the colors (e.g., Performance Score, ROI)

#### Customize Appearance:
- **Chart Title**: Give your heatmap a descriptive title
- **Color Scheme**: Choose from 6 professional color palettes
  - Red-Yellow-Green: Best for performance metrics
  - Blues: Professional corporate look
  - Others: Scientific or high-contrast options

#### Set Thresholds:
- **Low Threshold**: Below this = poor performance (first color)
- **High Threshold**: Above this = good performance (third color)
- Values in between show as the middle color

### 4. Export Your Heatmap

- **Update Heatmap**: Apply your changes and preview
- **Download as PNG**: Creates a 300 DPI image perfect for PowerPoint
- **Export Embed**: Creates a standalone HTML file you can share

## Understanding the Color Settings

### Three-Color System
Instead of a gradient, the tool uses three distinct colors:
1. **First Color** (e.g., Red): Poor performance
2. **Middle Color** (e.g., Yellow): Average performance  
3. **Third Color** (e.g., Green): Good performance

### Thresholds Explained
- If you set thresholds at 0.3 and 0.7:
  - 0.0 - 0.3 = First color (poor)
  - 0.3 - 0.7 = Middle color (average)
  - 0.7 - 1.0 = Third color (good)

### Normalization
- **Checked** (Recommended): Scales all values to 0-1 for fair comparison
- **Unchecked**: Uses raw values from your data

## Tips for Great Heatmaps

### Data Organization
- **Limit categories**: 10-20 items per axis works best
- **Clean data**: Remove blanks and "N/A" values in Excel first
- **Consistent formatting**: Ensure numbers are formatted consistently

### Visual Best Practices
- **Title**: Be specific - "Q4 2024 Partner Performance by Region"
- **Color choice**: 
  - Use Red-Yellow-Green for metrics where high is good
  - Use Blues for neutral data
  - Consider colorblind-friendly options for public presentations

### PowerPoint Integration
1. Click "Download as PNG (300 DPI)"
2. In PowerPoint: Insert → Pictures → From File
3. Resize as needed (high resolution ensures quality)
4. Add annotations with PowerPoint text boxes

## Troubleshooting

### "No valid data to display"
- Check that your selected columns contain numeric values
- Remove any text (except headers) from value columns
- Ensure no blank rows in your data

### Colors look wrong
- Verify your threshold settings make sense for your data
- Try normalizing the data if comparing different scales
- Check if low values should be good (like costs) - you may need to interpret colors differently

### File won't upload
- Ensure it's a .CSV file (not .XLSX)
- Save Excel files as "CSV (Comma delimited)"
- Check file isn't open in Excel

## Examples by Use Case

### Partner Performance Dashboard
- X-Axis: Performance Metrics (CTR, Conversion, ROI)
- Y-Axis: Partner Names
- Values: Normalized scores
- Colors: Red-Yellow-Green

### Regional Sales Analysis  
- X-Axis: Months or Quarters
- Y-Axis: Regions
- Values: Sales figures
- Colors: Blues (professional)

### Campaign Effectiveness Matrix
- X-Axis: Campaign Types
- Y-Axis: Customer Segments  
- Values: Conversion rates
- Colors: Viridis (scientific)

## Sharing Your Work

### For Presentations
- Export as PNG at 300 DPI
- Maintains quality when projected
- Easy to annotate in PowerPoint

### For Interactive Review
- Export Embed creates a standalone file
- Recipients can hover for details
- No software needed to view

### For Reports
- Screenshot the heatmap in your browser
- Paste directly into Word/Google Docs
- Include threshold explanation in caption

## Privacy & Security

- **No data uploaded**: Everything processes in your browser
- **No cookies or tracking**: The tool doesn't store anything
- **Safe for sensitive data**: Your information never leaves your computer

---

**Need Help?** This tool is designed to be self-service, but if you encounter issues:
1. Try refreshing the page and uploading again
2. Verify your CSV format matches the examples
3. Test with a smaller subset of data first