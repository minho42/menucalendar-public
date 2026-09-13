# Menu Calendar

A tiny macOS menu bar app that shows today's event from one calendar, in one line.

```
roster [▸ Dentist 15:00]
```

## What the line shows

| Label | Meaning |
|---|---|
| `roster [N10]` | All-day event, shown all day |
| `roster [Dentist 15:00]` | Next timed event and its start time |
| `roster [▸ Dentist 15:00]` | Timed event happening now |
| `roster [–]` | Nothing left today |
| `[⋯]` / `[!]` | No calendar chosen / no calendar access |

Finished events drop off, and the line resets at midnight. Click or right-click it to see all of today's events, pick a calendar, show or hide the calendar name, turn on launch at login, or quit.

## Build

Requires macOS 14+ and Xcode 26.

1. Open `menucalendar.xcodeproj` and run the `menucalendar` scheme.
2. Allow Calendar access when asked.
3. `⌘U` runs the label formatting tests.

## Privacy

Everything stays on your Mac. See [privacy-policy.md](privacy-policy.md).

## Contact

[minho42+menucalendar@gmail.com](mailto:minho42+menucalendar@gmail.com)
