# ebsynth_utility

## Overview
#### AUTOMATIC1111 UI extension for creating videos using img2img and ebsynth.

## Example
#### sample 1
<div><video controls src="https://user-images.githubusercontent.com/118420657/209951020-bee819b7-b8ef-48a9-8630-0e7c5c9a5d2f.mp4" muted="false"></video></div>

#### sample 2
<div><video controls src="https://user-images.githubusercontent.com/118420657/209951127-ff61671c-31aa-4e11-82f2-b3d9212c8748.mp4" muted="false"></video></div>

## Installation
- Install [ffmpeg](https://ffmpeg.org/) for your operating system
  (https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/)
- Install [Ebsynth](https://ebsynth.com/)
- Use the Extensions tab of the webui to [Install from URL]

## Usage
- Go to [Ebsynth Utility] tab
- Create an empty directory somewhere, and fill in the "Project directory" field
- Place the video you want to edit from somewhere, and fill in the "Original Movie Path" field
  Use short videos of a few seconds at first.
- Select stage 1 and Generate
- Execute in order from stage 1 to 7
  Progress during the process is not reflected in webui, so please check the console screen.
  If you see "completed." in webui, it is completed.


