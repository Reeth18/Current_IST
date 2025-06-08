# Current_IST
Showing the current time of India
🕰️ Live IST Clock (with Loading Animation)
This is a simple yet elegant web project that displays the current Indian Standard Time (IST) with precision up to milliseconds. Before showing the live time, the page features a playful "Loading..." animation where the dots bounce in a wave-like motion.

📋 Features
✅ Real-Time IST Display (updated every millisecond)

✅ 12-Hour Format with AM/PM

✅ Loading Animation with bouncing dots (wave effect)

✅ Responsive Design for different screen sizes

✅ Delayed Reveal (5 seconds delay before showing time)

✅ Title appears only when the clock starts

🔧 Technologies Used
HTML5

CSS3 (with media queries and keyframe animations)

Vanilla JavaScript

📦 How It Works
1. Initial Loading State
When the page loads, a “Loading…” message is shown.

The three dots in the message use a CSS keyframe animation to bounce in a staggered wave motion.

This continues for 5 seconds before the actual time is revealed.

2. IST Time Calculation
JavaScript calculates the current UTC time and adds an offset of 5 hours 30 minutes (19800000 ms) to convert it to IST.

The clock is shown in 12-hour format, and padded with leading zeros where necessary.

The setInterval method updates the display every 1 millisecond to keep it ultra-precise.

3. After Delay
The h1 heading “Current Indian Standard Time” appears.

The loading animation is replaced with the actual time in the format:

ruby
Copy
Edit
HH:MM:SS.MMM AM/PM
🎨 Visual Behavior
text
Copy
Edit
[Loading... (dots bounce like a wave)]
      ↓ (after 5 seconds)
Current Indian Standard Time
08:53:42.129 PM
🧪 Responsive Adjustments
Media queries adjust font sizes on devices with smaller screen widths:

Screen Width	Title Font	Clock Font
> 980px	50px	30px
≤ 980px	40px	25px
≤ 767px (mobile)	35px	20px

🚀 How to Use
Save the HTML code to a file, for example: index.html.

Open the file in any modern web browser (Chrome, Firefox, Edge).

Watch the animation, then enjoy your live IST clock!

📸 Preview
plaintext
Copy
Edit
Loading...
(dot wave animation)

↓ after 5 seconds

Current Indian Standard Time
09:15:47.832 PM
📁 File Structure
graphql
Copy
Edit
index.html         # Main HTML file with embedded CSS and JS
README.md          # This file
✍️ Author
Rayith Bose
Frontend Developer | JavaScript & Shopify Enthusiast