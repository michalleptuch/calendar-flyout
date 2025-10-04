## [2.1.0] - 2024-10-10
 
### Added
- support for Google accounts
- support for Google Meet online meetings
- support for Outlook app (from Microsoft 365 bundle)
- support for German and Italian languages
- new Agenda widget for Windows Widgets Board
- separated event indicators visibility setting for calendar view
   
### Changed
- fixed communication between app processes
- fixed title bar styles in the settings window
- fixed scrolling and positioning for non-100% DPI displays
- fixed mechanism of real-time synchronization
- fixed time format in time pickers
- fixed date format and styles in date pickers
- fixed calendar picker in agenda view
- fixed mechanism of accounts authentication flow

## [2.0.0] - 2024-02-01
 
### Added
- week numbers in the calendar view (optional)
- two sizes of the main app window - normal and fit to screen height
- ability of performing basic operations on events: adding, modifying and deleting
- account management directly in the app (changing visibility of calendar, changing calendar color)
- support for work or school accounts
- support for Microsoft Teams for Business (ability to join a meeting directly from the agenda)
- support for cancelled meetings (visible as translucent in the agenda)
- ability of opening app directly from the taskbar icon (not only from the system tray)
- support for a jump list (matches context menu of the app in the system tray)
- a badge (with number of events) on the app icon on the taskbar
- two styles of the app background - Acrylic and Mica
- new event designer for adding new events and editing existing ones
- new preview of existing events
- context menu of events in the agenda view
- new icon for series events in the agenda view
- automatic app updates in the background
- confirmation info after creating or editing an event
   
### Changed
- Calendar Flyout is based on Microsoft Graph API instead of Windows Appointments API
- updated UI elements in the agenda
- updated app icon in system tray
 
### Removed
- support for non-Microsoft calendars
- synchronization with Microsoft Calendar app (UWP version introduced in Windows 10)
