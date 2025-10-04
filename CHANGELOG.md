## [2.2.0] - 2025-10-04

### Added
- Add option to switch between 12-hour and 24-hour clock
- Add clock size setting: normal or large
- Add ability to set any weekday as the first day of the week
- Add option to display ISO 8601 week numbers
- Add colored dots on calendar days matching the colors of calendars that have events
- Add static Calendar widget
- Add Agenda widget small variant (can be pinned to the lock screen)
- Add transparent background option for widgets
- Add option to show the app window at the top of the screen
- Add default meeting length setting
- Add default reminder setting for meetings
- Add configurable calendar and event synchronization
- Add ability to pin the window so it stays open when out of focus
- Add automatic end-time adjustment when the start time is changed

### Changed
- Separate event display settings per area: calendar, agenda, tray icon, taskbar icon, and widgets
- Improve event synchronization engine
- Fix rendering of widgets in the Windows Widgets Board
- Fix app window rendering
- Fix editing of recurring event series
- Fix issues in the event editor


## [2.1.0] - 2024-10-10
### Added
- Add support for Google accounts
- Add support for Google Meet online meetings
- Add support for Outlook app (Microsoft 365)
- Add German and Italian localizations
- Add Agenda widget for Windows Widgets Board
- Add separate visibility setting for event indicators in the calendar view

### Changed
- Fix communication between app processes
- Fix title bar styles in the settings window
- Fix scrolling and positioning for non-100% DPI displays
- Fix real-time synchronization mechanism
- Fix time format in time pickers
- Fix date format and styles in date pickers
- Fix calendar picker in the agenda view
- Fix account authentication flow


## [2.0.0] - 2024-02-01
### Added
- Add week numbers in the calendar view (optional)
- Add two sizes of the main app window: normal and fit to screen height
- Add basic event operations: add, edit, delete
- Add account management in the app (toggle calendar visibility, change calendar color)
- Add support for work or school accounts
- Add support for Microsoft Teams for Business (join a meeting directly from the agenda)
- Add support for cancelled meetings (shown as translucent in the agenda)
- Add ability to open the app directly from the taskbar icon (not only from the system tray)
- Add jump list support (mirrors the app’s system tray context menu)
- Add taskbar badge with number of events
- Add two app background styles: Acrylic and Mica
- Add new event designer for creating and editing events
- Add new preview for existing events
- Add context menu for events in the agenda view
- Add new icon for series events in the agenda view
- Add automatic background app updates
- Add confirmation message after creating or editing an event

### Changed
- Migrate Calendar Flyout from Windows Appointments API to Microsoft Graph API
- Update UI elements in the agenda
- Update app icon in the system tray

### Deleted
- Remove support for non-Microsoft calendars
- Remove synchronization with the Microsoft Calendar app (UWP, introduced in Windows 10)
