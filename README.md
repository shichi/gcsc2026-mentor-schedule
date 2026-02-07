# GCSC2026 Mentor Booking System

## Overview

This directory contains mentor booking data for GCSC2026.

**Timeslot System:** Each 2-hour session is divided into six 20-minute timeslots. Teams can book one timeslot per session with their preferred mentor.

## Files

- `mentor_bookings.json` - Booking data (JSON format)
- `mentor_bookings.md` - Booking status visualization (Markdown format, easy to view on GitHub)

## Usage

### Booking via Discord

Use the following commands in team channels (`#team-01` to `#team-20`):

```
/mentor book session:session_1 timeslot:10:00-10:20 mentor:金子 匡俊
/mentor cancel session:session_1 timeslot:10:00-10:20
/mentor my
/mentor status session:session_1
```

**Important:**
- You must specify both the session AND the specific 20-minute timeslot
- Each mentor can only be booked by one team per timeslot
- Each team can only book one timeslot per session

### Check Booking Status

Open `mentor_bookings.md` on GitHub to view the overall booking status by timeslot.

## Session Information

### Session 1: 10:00-12:00

**Timeslots:** 10:00-10:20, 10:20-10:40, 10:40-11:00, 11:00-11:20, 11:20-11:40, 11:40-12:00

**Mentors:**
- Masatoshi KANEKO (金子 匡俊)
- Julian Brody
- Heedong YOO
- Hyun Joo CHUNG

### Session 2: 13:00-15:00

**Timeslots:** 13:00-13:20, 13:20-13:40, 13:40-14:00, 14:00-14:20, 14:20-14:40, 14:40-15:00

**Mentors:**
- Kenta MURAOKA (村岡 健太)
- Keiichiro KATAOKA (片岡 慶一郎)
- Seung Hwan MOK
- Hyun Joo CHUNG

### Session 3: 15:30-17:30

**Timeslots:** 15:30-15:50, 15:50-16:10, 16:10-16:30, 16:30-16:50, 16:50-17:10, 17:10-17:30

**Mentors:**
- Kenta MURAOKA (村岡 健太)
- Takatsugu KONNO (紺野 貴嗣)
- Seung Hwan MOK
- Hyun Joo CHUNG

### Faculty Night: 20:00-22:00

**Not available for booking** - Faculty members will circulate among teams to provide support.
