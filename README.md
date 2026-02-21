# Xylophone – iOS App

Xylophone is a simple iOS application built with **Swift**, **UIKit**, and **AVFoundation** that allows users to play musical notes by tapping on color-coded keys.  
This project demonstrates **audio playback, user interaction, and UI feedback** in iOS.

---

## Features

- Play a different sound for each key
- Visual feedback on key press (button fades briefly)
- Lightweight and responsive
- Demonstrates UI interaction with UIButton and AVAudioPlayer
- Easy-to-understand MVC structure

---

## Tech Stack

- Language: Swift  
- Framework: UIKit  
- Audio: AVFoundation  
- Architecture: MVC  
- IDE: Xcode  
- iOS Target: iOS 13+

---

## How It Works

1. Each xylophone key is a UIButton with the title corresponding to the sound file (e.g., "C", "D", "E").
2. When a button is pressed:
    - `playSound(soundName:)` is called
    - The corresponding `.wav` file is loaded using `AVAudioPlayer`
    - The sound is played
    - Button fades to 50% alpha for 0.2 seconds for visual feedback
      
## Author

Sandro Lomtadze
Junior iOS Developer

