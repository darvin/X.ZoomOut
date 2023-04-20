# X.ZoomOut
Zoom replacement with spatial audio and generated avatars

Zoom with spatial audio 🔊 and generated video stream: a virtual meetings app for mobile 📱 and desktop 💻 that generates a video stream of "conference table" environment with photorealistic avatars 👥 of participants, with localized spatial audio 👥. 

Turn off your video camera and remain visible as a generated avatar






Introducing an innovative virtual meeting application that offers a unique and immersive conference table experience. This app utilizes advanced technology to generate a 3D video stream of a conference table environment, complete with photorealistic avatars of each participant.

One of the most exciting features of this app is the localized spatial audio, which allows users to hear the voices of their coworkers as if they were sitting next to them at the conference table. And for those who prefer not to have their cameras on during the meeting, this app offers the option to generate an avatar that will represent them visually.

This avatar is visible to other participants in the meeting, ensuring that everyone knows who is present and engaged. This innovative feature is made possible by a Stable-diffusion like system that generates avatars using minimal resources and low latency. The system can even be trained on a user's own photo to create a more personalized avatar.

With this advanced virtual meeting app, you can collaborate with coworkers from anywhere in the world, all while feeling like you're in the same room. Whether you're having a quick catch-up or a longer team meeting, this app is designed to make remote collaboration more efficient, productive, and enjoyable.




To implement this solution, we will use WebRTC for voice-only communication and screensharing. We will leverage SwiftUI to create the user interface for the virtual meeting app.

For generating the static "conference table" view, we will use on-device StableDiffusion. We will use Control-Net for selective low-resolution generation of the face features update in real-time.



