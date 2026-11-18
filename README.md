# Battery Manager

A clean Windows desktop app for monitoring your laptop battery and getting alerts at the levels you choose.

## Features

- Set your own low-battery and almost-full alert levels
- Hear spoken alerts that repeat until you plug in or unplug the charger
- See battery percentage, charging status, and time remaining
- View health, wear, capacity, charge cycles, voltage, and battery details
- Run quietly near the Windows clock
- Start automatically with Windows

Only your two alert levels are saved. No battery history is stored.

Some laptops do not share every battery detail, so a value may show as "Not reported".

## Download

Get **BatteryManagerSetup.exe** from the [latest release](../../releases/latest).

Requires 64-bit Windows.

## Build from source

1. Install Visual Studio with the **.NET desktop development** workload.
2. Open the solution.
3. Press **F5** to run the app.

## Built with

- C# and WPF on .NET 10
- [WPF UI](https://github.com/lepoco/wpfui)
