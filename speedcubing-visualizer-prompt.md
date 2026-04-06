# Speedcubing Data Visualizer

* Create comprehensive speedcubing analytics dashboard
* Transform cstimer export data into visual insights
* Pure data visualization (numbers, graphs, charts - some text descriptions)
* Drag-and-drop file upload for cstimer JSON files with txt extension
* Interactive visualizations with smooth animations and transitions
* Session(day)/week/month exploration with clickable drill-down capabilities
* Comprehensive speedcubing metrics (AO5, AO12, AO100, etc.)
* Time-based analysis (hourly, daily, weekly patterns)
* Fun achievements without badges (total time cubing per hour,day,week,month,all time, total amount of solves, customisable range totals(time and solves))
* Support for multiple cube types (333(3x3), 222(2x2))
* Next.js with TypeScript
* Tailwind CSS for styling
* Chart.js for interactive visualizations
* Responsive design for all devices
* Instant insights when data is uploaded
* Zoom/pan on all charts (pinch, wheel, drag) for deep dive into time ranges
* Time-of-day & day-of-week heatmaps; calendar view of activity and averages.
* PB over time
* Daily average over time
* Weekly average over time
* All-time average over time
* Weekly improvement rate
* Allows uploading data in the format of the cstimer data text file

Make it visually appealing and easy to use. make sure that if you allow zooming on charts that there is a maximum zoom out which will be the default zoom level(showing all the data and no extra space)

Make sure to make commits along the way with clear messages describing the changes made.

If you end up adding any external libraries for ui, make sure to style it to match the rest of the app as closely as possible.

Some examples of the style are at 1.png and 2.png in the root of the repo.

Use the example file provided at cstimer_20260405_161119.json. Use jq to query it as it's quite large and will fill up your context window.