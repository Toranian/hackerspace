# Hackerspace Changelog
This file chronologically records all notable changes to this website, including new features, tweaks, and bug fixes.

[Changelogs](http://keepachangelog.com/en/0.3.0/) | [Versioning](http://semver.org/)

### [1.11.0] 2018-05-15 - Math!
* Many mobile tweaks
* Added LaTeX math support
* Quest submenu in top navbar
* [teacher only] Customizable menu links

### [1.10.2] 2018-06-02 - The mobile device update
* force responsive images in submissions (so large images no longer extend past the content area)
* create mobile menu for notifications
* turn off suggestions
* various mobile layout tweaks
* remove left menu on mobile, added to top menu bar.
* [bugfix] only offer to add valid media to portfolios
* [bugfix] create portfolio when adding if it doesn't exist (instead of error)

### [1.10.1] 2018-03-06
* new button to access in-progress quests directly (much faster)
* students can view unavailable quests as a preview
* indicator when specific teachers are notified by particular quests
* [bugfix] skipped quests bugging out

### [1.10.0] 2018-02-23 - The Studio Tyee update
* [Teacher only] Site name and banner as a configurable setting (support for Studio Tyee)

### [1.9.1] 2018-02-03
* [teacher only] export data as json (for use with browser extension to upload marks to CIMS)
* [bugifx] comment ban was banning wrong person

### [1.9.0] 2018-01-07
* User custom stylesheets!
* New styling options in text editor (summernote plugins)
* [teacher only] Export of student data for report cards
* [teacher only] Figure styles and packed responsive images (see https://hackerspace.sd72.bc.ca/quests/1058/)
* Add support for <439px displays (phones in portrait modes)
* CSS tweaks for images and lists
* [bugfix] Sort marks properly

### [1.8.0] 2017-10-21
* Students can create and edit quests by turning on the TA flag in their profile
* codemirror formatting when using codeview
* New histogram chart on student XP page
* Added emoji insertion, fontawesome insertion, new semantic formats, and better video insertion
* [teacher only] Grade can now be used as a prerequisite
* [teacher only] Teachers can flag submissions for future follow up
* [teacher only] Teachers can choose to only see quests in their own blocks (default)
* Fullscreen view of quest maps
* Length of displayed Aliases are now limited
* [teacher only] Quests not visible to students now appear in a Drafts tab
* [bugfix] Fix badge granting bugs from Django 1.11
* [bugfix] Repeatable quest bug fixed
* [bugfix] Map creation was showing non-visible quests
* [bugfix] Add manual course XP adjustment to grade calcs
* Other minor tweaks
 

### [1.7.0] 2017-05-28
* Updated Django to 1.11 LTS (support to 2020)
* Fixed bugs preventing initial migrations when setting up the django app

### [1.6.0]
* Bulk badge granting
* TOC generator for FAQ
* List all dates that badges were granted in profile (as opposed to only the latest one)
* XP Chart formatting tweaks

### [1.5.0] 2017-02-01
* This changelog!
* Archive quests
* XP is now cached so it doesn't recalculate unless a new quest is approve/returned or badge awarded.
* Other minor optimizations to improve page load speeds.
* Changed license to GPL v3.
