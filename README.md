# jquery.notification

A simple and small notification plugin for jQuery.

## Demo

Check out http://marcojetson.github.com/jquery-notification/

## Installation

Include script after jQuery

    <script src="jquery.notification.js"></script>

** License

Licensed under the GPL license
http://www.gnu.org/licenses/

## Usage

    $.createNotification(options)

## Options

### click
Click callback

### content
Notification content

### duration
On screen duration in milliseconds, set it to 0 for sticky, default 5000

### fadeIn
Fade in effect duration in milliseconds, default 400

### fadeOut
Fade out effect duration in milliseconds, default 400

### limit
Visible limit per board, when reached notifications wont be created, default false

### queue
If queue is active and limit is reached notifications will be shown when other hides, default false

### slideUp
Slide up effect duration in milliseconds, default 200

### horizontal
Horizontal alignment, default right

### vertical
Vertical alignment, default top