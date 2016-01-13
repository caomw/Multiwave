# Multiwave
Multiwave is a Doppler-based acoustic gesture recognizer. It is developed in C\# for use in Windows 7/8/10. It requires a microphone to be used.

## Dependencies
Multiwave depends on the following external libraries: 
* IKVM (included)
* NAudio (included)
* WindowsInput (Grab from NuGet)

## Installation
Clone the repository and build in Visual Studio 2013 or higher. If WindowsInput is missing, explicitly add it using NuGet.

## Usage
The following gestures are supported.

| 1D            | 2D            |
| ------------- |-------------  |
| Single Tap    | Directional Swipe |
| Double Tap    | Directional Tap      |
| Two-Handed push/pull |  |
| Scoll    |      |
