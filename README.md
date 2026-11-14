# RestEasy App

> **Internship:** ENGR 399 Engineering Internship · Khalifa University · remote with Children's National Hospital, Washington DC

A cross-platform mobile app prototype for nighttime pediatric asthma monitoring. RestEasy started as a device and app idea from a group of George Washington University medical students. This was a team project with my internship mentor and another intern.

**This repository contains my internship work on the app.**

## Features

- **Cross-platform:** built with Xamarin.Forms to target iOS, Android and Windows from a single shared .NET codebase.
- **Exacerbation alarm:** when a child with nocturnal asthma has an exacerbation, the parent gets a notification, and the details of the last alarm can be viewed in the app.
- **Health history:** heart rate (HR), respiratory rate (RR) and SpO2 are continuously updated and saved to a local database.

## Architecture

```
Device emulator (Windows)  --TCP/IP-->  RestEasy app (Xamarin.Forms)  -->  SQLite.Net database
```

## My contributions

- Wrote the Software Requirements Specification from the client's concept slides
- Designed a high-fidelity prototype of the app in Marvel App
- Built the main page UI (logo, last alarm, HR / RR / SpO2 readings, action buttons)
- Added sliders to the device emulator and redesigned it to match the app
- Added a timer that sends readings from the emulator to the app at a fixed rate
- Built the Exacerbation page (date, time and readings of the last alarm)
- Stored and retrieved readings with SQLite.Net
- Added exacerbation notifications (Plugins.Notifier) and the Alarm page

My mentor set up the project skeleton, the device emulator, the TCP connection (EasyTCP) and a database example to build on.

## Tech

C#, Xamarin.Forms, SQLite.Net, TCP/IP, NuGet, Visual Studio
