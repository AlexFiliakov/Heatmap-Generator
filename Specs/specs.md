# Spec for the Marketing Campaign Performance Heatmap Generator

## Iteration 2 ##
Please make a new version of “Marketing Campaign Performance Heatmap Generator” with the following adjustments:
- Display the legend on the bottom horizontally and centered in the middle, with the label first, followed by the lowest value, and gradually progressing to the highest value on the right
- Reduce the margin between heatmap cells to 2 pixels
- Remove the axes lines for x-axis and y-axis and leave only the tick marks and axis labels.
- Display the chart title in 20pt font size.
- Make the image export 300dpi for printing.
- Make a button to the left of “Download as PNG” labeled “Export Embed”, and this button will download an HTML page that is an identical copy of the interactive chart, but without the options to modify the fields (no top portion) and the data should be embedded in this HTML exported page.
- Make the x-axis and y-axis labels 16pt font size.
- Make the x-axis and y-axis tick mark labels 14pt font size.
- Use Karla font for all the chart elements

## Iteration 3 ##
Here are additional changes to make:
- Provide solutions that could be maintained by a nontechnical marketing professional. Any code must provide a GUI with easy I/O interface to produce exhibits. This tool is meant for a nontechnical marketing professional who doesn’t know about programming technologies.
- The user must be able to select x-axis, y-axis, and the heatmap value and have the chart adjust accordingly.
- Use 3 colors selected from the gradients (for each color scheme: low  value, middle value, and high value) with custom threshold specification rather than having a full gradient.
- Make the legend horizontal below the x-axis label and centered horizontally.
- A user must be able to use it in browser without any setup.
- Make the configuration UI similar to the file attached (bubble-chart-tool.html)
