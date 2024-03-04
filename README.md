# Audio Pill Player
The Audio Pill Player is an interactive web application designed to allow users to create and manipulate audio tracks, similar to the functionality provided by iMovie for video editing. This project is built on React, providing a dynamic and responsive user interface, and utilizes various libraries such as Tone.js and Teoria.js for audio processing and music theory functionalities.

Try it out 

##### Installation
Clone this repository:
```
git clone https://github.com/your-username/audio-pill-player
cd Audio-Pill
```
Install dependencies:
``` npm install ```

Start the development server:
``` npm start ```

## Key Features:
- Timeline: Visually represent and manage audio tracks.
- Track Manipulation: Allow adding, removing, and shifting of audio tracks on the timeline.
- Playback Control: Play, pause, and stop functionalities for the entire composition.
- Dynamic Updates: Update the timeline and playback in real-time based on user interactions.

## Technology Stack:
- React: For building the user interface and handling user interactions.
- Web Audio API: For audio playback and manipulation functionalities.
- Audio Library: Libraries like Tone.js or Howler.js can simplify audio handling and effects.

The ```selector``` directory is divided into a beat *visualizer* and a beat *selector*. ```Selector.js``` also includes effects and note options, defined in ```SelectorOptions.js```

## New Features in Version 2.0
- Sample upload: allow for users to upload their own samples to use in the sequencer.

## More Features to be implemented
- Mobile support.
- More instrument effects.

## Issues
- Audio Distortion: There is an issue with audio distortion after continued use, likely due to memory or CPU constraints. Ongoing efforts are focused on optimizing resource utilization and exploring alternative audio processing solutions to address this issue.


