# Video Production Analysis System (VPAS)

An open-source tool that records manufacturing operations on video and enables simple process analysis and work frequency visualization. It supports understanding of Muri (overburden), Muda (waste), and Mura (unevenness), while promoting process visualization for production improvement.

## System Features

This system was developed to enable anyone to easily conduct "video process analysis" for on-site improvements in manufacturing.

### Differences from General Video Process Analysis Systems

General commercial video process analysis tools offer advanced features such as:

- **Complex multi-axis analysis**: Simultaneous analysis of multiple workers and machine operations
- **Detailed motion analysis**: Frame-by-frame motion extraction and optimization recommendations
- **Automatic analysis**: AI-driven motion pattern recognition and anomaly detection
- **Advanced simulation**: Effect prediction and simulation of improvement proposals
- **Enterprise-level integrated management**: Multiple project management, report generation, and permission management

In contrast, this system is characterized by:

- **Simple and easy to use**: Start recording work immediately without complex operations
- **Low cost**: Completely free to use
- **Real-time recording**: Record work content on-the-fly while playing the video in the browser
- **Basic analysis features**: Work frequency aggregation and pie chart visualization provide an instant overview of work balance
- **Flexible data utilization**: Data can be exported in JSON and CSV formats for easy secondary analysis in Excel and similar tools
- **Customizability**: Being open-source, modifications and improvements can be made to suit your organization's needs

### Ideal Use Cases

- Understanding work time in new employee training
- Confirming work balance between processes
- Comparing work time across multiple workers
- Recording work time changes before and after improvements
- "Visualization" as the first step toward productivity enhancement

## Supported Environment

- **Execution Environment**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Language**: JavaScript (frontend only)
- **External Libraries**: Tailwind CSS, Chart.js, YouTube IFrame API

## Feature Overview

- **Multiple video source support**: Analyze YouTube videos or local video files
- **Work content recording**: Record video playback time and related work content in chronological order
- **Keyboard shortcut support**: Quickly record work using keyboard operations
- **Analysis features**: Visualize recorded work data in list or graph format
- **Project management**: Save and load analysis data in JSON format
- **Data export**: Export recorded data in CSV format for detailed analysis in Excel and similar tools
- **Customizable work items**: Add and edit work items freely according to your needs

## Usage Guide

### 1. Loading a Video

#### Using YouTube Videos
1. Paste a YouTube video URL in the "Enter YouTube video URL" field
2. Click the "Load" button
3. The video will be loaded in the playback area

#### Using Local Video Files
1. Click the "Select Local Video File" button
2. Select a video file from your computer (supports MP4, MOV, WebM, etc.)
3. The video will be loaded in the playback area

### 2. Recording Work

There are two methods to record work content in the playing video:

#### Recording with Mouse
Click the buttons displayed in the "Work Items" section on the right panel

#### Recording with Keyboard (Recommended)
- **A Key**: Record Work A
- **S Key**: Record Work B
- **D Key**: Record Work C
- **F Key**: Record Work D
- **Q Key**: Record Break
- **W Key**: Record Other

### 3. Playback Controls

| Operation | Key | Button |
|-----------|-----|--------|
| Play | Z | Play button |
| Pause | X | Pause button |
| Set Marker | C | Set Marker button |
| Skip Back | ← | << button |
| Skip Forward | → | >> button |

**Marker Function**: Press C to mark the current playback time. Press C again to return to the marked time.

### 4. Viewing Recorded Data

View recorded work data in the lower right panel:

#### List View
- Playback time and work content are displayed in a list
- Click on playback time to jump the video to that timestamp
- Delete individual records using the "Delete" button

#### Graph View
- Display the number of records for each work item in a pie chart
- Work proportions are instantly visible

### 5. Editing Work Items

1. Click "Edit Work Items" in the list display area
2. In the modal window, set the name, color, and shortcut key for each work item
3. Add new work items using "Add New Work"
4. Delete unnecessary work items using the "Delete" button
5. Click "Save" to apply changes

**Note**: Z, X, and C keys are system-reserved and cannot be used as shortcuts.

### 6. Saving and Loading Projects

#### Saving a Project
1. Click the "Save Project" button at the top of the page
2. A JSON format file will be downloaded
3. Save this file to open the same project later

#### Loading a Project
1. Click the "Load Project" button
2. Select a previously saved project file (.json)
3. Your previous work data and video settings will be restored

### 7. Setting Project Title

Enter a project name in the text field at the top of the page. This name will be used as the filename when saving and exporting to CSV.

### 8. Exporting Data

1. Click the "Export to CSV" button
2. A CSV format file will be downloaded
3. Open it in Excel or other spreadsheet software for more detailed analysis

## Keyboard Shortcuts

| Key | Function |
|-----|----------|
| Z | Play |
| X | Pause |
| C | Set Marker / Return to Marker |
| ← | Skip Back |
| → | Skip Forward |
| A～F, Q, W | Record Work (depends on work item settings) |

## New Project

Click the "New Project" button to reload the page and clear all records. Use this when starting a new analysis.

## Supported Video Formats

- **YouTube**: All public videos
- **Local Files**: MP4, MOV, WebM (formats supported by your browser)

## Troubleshooting

### YouTube video won't load
- Verify that you've entered a correct YouTube URL
- URL should be in the format `https://www.youtube.com/watch?v=xxxxx` or `https://youtu.be/xxxxx`
- Confirm that the video is set to public

### Local video file won't play
- Check if your browser supports the file format
- Verify that the file is not corrupted

### Keyboard shortcuts not working
- Check if a text input field is active
- Check if a modal window is open

### Data not being saved
- Verify that JavaScript is enabled in your browser
- Check if the file has been saved in your Downloads folder

## Tips

- **Efficient recording**: Using keyboard shortcuts instead of mouse operations allows faster work recording
- **Customize work items**: Setting optimal work items for each project enables more accurate analysis
- **Regular saving**: We recommend regularly clicking the "Save Project" button to save progress
- **Use graphs**: Use the graph view to confirm work balance and improve productivity
- **Detailed analysis with CSV**: Further advanced analysis is possible by processing the exported CSV in Excel

## Supported Browsers

- Google Chrome (latest version)
- Mozilla Firefox (latest version)
- Apple Safari (latest version)
- Microsoft Edge (latest version)
