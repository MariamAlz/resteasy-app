# RestEasy App

> **Internship:** ENGR 399 Engineering Internship · Khalifa University · remote with Children's National Hospital, Washington DC

A cross-platform mobile app prototype for nighttime pediatric asthma monitoring. RestEasy started as a device and app idea from a group of George Washington University medical students. During the internship I wrote the Software Requirements Specification and built the app prototype.

## Features

- **Cross-platform:** built with Xamarin.Forms to target iOS, Android and Windows from a single shared .NET codebase.
- **Exacerbation alarm:** when a child with nocturnal asthma has an exacerbation, the parent gets a notification, and the details of the last alarm can be viewed in the app.
- **Health history:** heart rate (HR), respiratory rate (RR) and SpO2 are continuously updated and saved to a local database.

## Architecture

```
Device emulator (Windows)  --TCP/IP-->  RestEasy app (Xamarin.Forms)  -->  SQLite.Net database
```

## Tech

C#, Xamarin.Forms, SQLite.Net, TCP/IP sockets, NuGet, Visual Studio
