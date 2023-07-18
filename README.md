# Scrumdinger

This project aims to help SCRUM meetings by displaying a graphical timer that divides the time among the different Team Members. It also plays a "ding" sound for each of the Members in the Team when their time runs out. The app also records the audio and automatically transcribes the meeting, which will then be available immediately after the meeting, saved in the History section of the Team's info.

![Summary Image of the Project](/assets/images/summary.png)


## Technologies Used

- Switft & SwiftUI
- State & ScenePhase Management
- Custom Store with conformance to ObservableObject
- Loading & Saving of JSON data to the local File System
- Programmatic drawing of dynamic Geometric shapes shown during the meeting
- Using AVFoundation package and extending the AVPlayer to play the ding/reminder sound
- Using AVFAudio package and AVAudioSession to record the Audio; the OS helps gather the required User permissions to be able to record, etc
- Using the built-in Speech Recognition package & AVAudioEngine to transcribe the audio recording
- (among other things)


## Screencasts

| **Creating a new Team** | |
| :--- | --- |
| <img src="/assets/images/create_team.gif" width="300px"> | The Theme Picker is featuring the new _.navigationStyle_ Picker, which automatically pushes a new Navigation view into the screen, all managed by SwiftUI. Each row in the List of Themes is then customized using a separate SwiftUI View to show the actual color for each of the items on the list, instead of just the name (for example), and so on. |

| **Editing a Team, <br />Running a Meeting, <br />and Reviewing the Transcipt** | |
| :--- | --- |
| Note: The Transcription result may vary depending on any of the Speakers' accents, how near or far they are from their respective microphones, how slow or fast they talk, or if there are overlapping voices from the other members of the Team, and there may be background noises too, etc. But for most cases, it works really well. | <img src="/assets/images/edit_team.gif" width="300px"> |

<sub>All Rights Reserved ©️ 2023</sub>