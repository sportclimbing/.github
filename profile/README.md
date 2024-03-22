> [!WARNING]
> **Automatic updates are halted until further notice**
> 
> https://github.com/sportclimbing/ifsc-calendar/issues/7

<hr />

<div align="center">
  <h1>IFSC Climbing Calendar and Live-Streams for 2024</h1>
  <p>This generates an always up-to-date <code>iCal</code> calendar you can subscribe to using your favorite calendar app, such as <i>Google Calendar</i> or <i>Outlook</i>, to never miss an IFSC climbing event ever again.</p>
  <img src="https://img.shields.io/github/downloads/sportclimbing/ifsc-calendar/total?color=green&label=Downloads" alt="downloads" />

  <h1> 👩‍💻 Web Version</h1>
  <p>A web version of the calendar is also available and can be found here:</p>
  <h4> &nbsp; &nbsp; https://ifsc.stream</h4>
</div>

<hr />

### ⭐️ Features:
- Updates automatically every hour
- Fetches schedules directly from IFSC's website (using some APIs and fancy scraping)
- Converts times to your local timezone
- Alerts an hour befor events start
- Fetches YouTube stream URLs
- Fetches start list for events
- Works on any calendar app (Google Calendar, Outlook, etc...)
- Will work for future seasons once schedules are published
- Fully open source

<hr />

<div  align="center">
  <img src="/profile/calendar.png" alt="calendar" width="60%" />
</div>

### 🤓 How
Copy and paste this calendar URL [**https://calendar.ifsc.stream**] into your calendar subscriptions, and it will
automatically sync with your device. This works on iPhone, Google Calendar, Proton Calendar, etc... This will keep
you updated on future seasons as well.

Take a look at the **[setup guides 📖](https://github.com/sportclimbing/ifsc-calendar/wiki)** for help.

<hr />

### ⚒️ Code
Here are all the repositories needed to build [https://ifsc.stream](https://ifsc.stream/)

| Repository                                                                                   | Description                                  | Status                                                                                                                    |
|----------------------------------------------------------------------------------------------|----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [sportclimbing/ifsc-calendar](https://github.com/sportclimbing/ifsc-calendar)                | IFSC Calendar Generator                      | ![update ralendar](https://github.com/sportclimbing/ifsc-calendar/actions/workflows/update-calendar.yml/badge.svg)        |
| [sportclimbing/web](https://github.com/sportclimbing/web)                                    | Calendar Frontend                            | ![web deploy](https://github.com/sportclimbing/web/actions/workflows/static-deploy.yml/badge.svg)                         |
| [sportclimbing/ifsc-videos](https://github.com/sportclimbing/ifsc-videos)                    | An always up-to-date YouTube video DB        | ![Update video database](https://github.com/sportclimbing/ifsc-videos/actions/workflows/update-database.yml/badge.svg)    |
| [sportclimbing/calendar.ifsc.stream](https://github.com/sportclimbing/calendar.ifsc.stream)  | Calendar Backend                             | ![Deploy to prod](https://github.com/sportclimbing/calendar.ifsc.stream/actions/workflows/deploy-prod.yml/badge.svg)      |

<div align="center">
  <i>(In no way affiliated with, or endorsed by the <a href="https://www.ifsc-climbing.org/">IFSC</a></i>
</div>
