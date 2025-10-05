## [2.2.0] - 2025-10-05

### Added
- Added option to switch between 12-hour and 24-hour clock
- Added clock size setting: normal or large
- Added ability to set any weekday as the first day of the week
- Added option to display ISO 8601 week numbers (weeks start on Monday; week 01 is the week with the year’s first Thursday)
- Added colored dots on calendar days matching the colors of calendars that have events
- Added static Calendar widget
- Added Agenda widget small variant (can be pinned to the lock screen)
- Added transparent background option for widgets
- Added option to show the app window at the top of the screen
- Added default meeting length setting
- Added default reminder setting for meetings
- Added configurable calendar and event synchronization
- Added ability to pin the window so it stays open when out of focus
- Added automatic end-time adjustment when the start time is changed

### Changed
- Separated event display settings per surface: calendar, agenda, tray icon, taskbar icon, and widget
- Improved event synchronization engine
- Fixed rendering of widgets in the Windows Widgets Board
- Fixed app window rendering
- Fixed editing of recurring event series
- Fixed issues in the event editor


## [2.1.0] - 2024-10-10

### Added
- Added support for Google accounts
- Added support for Google Meet online meetings
- Added support for Outlook app (Microsoft 365)
- Added German and Italian localizations
- Added Agenda widget for Windows Widgets Board
- Added separate visibility setting for event indicators in the calendar view

### Changed
- Fixed communication between app processes
- Fixed title bar styles in the settings window
- Fixed scrolling and positioning for non-100% DPI displays
- Fixed real-time synchronization mechanism
- Fixed time format in time pickers
- Fixed date format and styles in date pickers
- Fixed calendar picker in the agenda view
- Fixed account authentication flow


## [2.0.0] - 2024-02-01

### Added
- Added week numbers in the calendar view (optional)
- Added two sizes of the main app window: normal and fit to screen height
- Added basic event operations: add, edit, delete
- Added account management in the app (toggle calendar visibility, change calendar color)
- Added support for work or school accounts
- Added support for Microsoft Teams for Business (join a meeting directly from the agenda)
- Added support for cancelled meetings (shown as translucent in the agenda)
- Added ability to open the app directly from the taskbar icon (not only from the system tray)
- Added jump list support (mirrors the app’s system tray context menu)
- Added taskbar badge with number of events
- Added two app background styles: Acrylic and Mica
- Added new event designer for creating and editing events
- Added new preview for existing events
- Added context menu for events in the agenda view
- Added new icon for series events in the agenda view
- Added automatic background app updates
- Added confirmation message after creating or editing an event

### Changed
- Migrated Calendar Flyout from Windows Appointments API to Microsoft Graph API
- Updated UI elements in the agenda
- Updated app icon in the system tray

### Deleted
- Removed support for non-Microsoft calendars
- Removed synchronization with the Microsoft Calendar app (UWP, introduced in Windows 10)
