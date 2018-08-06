# 20H Talent Ikigai Project 7: Web App Dashboard

Many websites do more than just give you information. Sites like GitHub, Zillow, Mint and Treehouse let users do things. They act like programs you run on your computer. These web applications, often include pages for looking at your profile, what you've done in the week or what you need to get done. These "dashboards" act like your control panel for controlling the web app.

In this project, you'll take a mockup and a few icons and build a beautiful, web dashboard complete with JavaScript-driven charts and graphs. You only need to take the design and create the HTML, CSS and JavaScript functionality for this one page -- you don't need to create other pages, or build any backend or database functionality.

## Project Instructions

To complete this project, follow the instructions below:

#### Look at the provided web app dashboard mockup: dashboard.png:

- Create an HTML file for the app dashboard.

#### Create a responsive web page with the following:

- Header with app name, notification icon badge and profile avatar and name.

- SVG Icon based navigation with the following links: Dashboard, Members, Visits, and Settings. NOTE: You only have to build out the main dashboard page, not any of the other pages.

- Main content area where the specific dashboard widgets will go.
  
- Ensure that the design responds well from mobile (320px), to tablet and desktop screen sizes.
		
- Make sure header, navigation and main widget area respond well to common mobile, tablet and desktop device sizes.

#### Create a demo alert notification:
- In the dashboard.png, this appears as the purple bar near the top of the page with the word "Alert" in it. When the page loads this alert should be visible, but the user should be able to close the alert by clicking the X button.
  
- Include a notification icon in the navigation header. Use the icon-bell.svg file. In the mockup this is the bell in the top right corner of the page.
		
#### Create a Web Traffic widget:

- Use chartjs.org or a similar library to create a line chart line like the top chart pictured in the mockup.

- Display number of visits along the y axis and date/time on the x axis. You will need to make up this data -- you can see the mockup for sample data.

- Create a navigation similar to the one in the mockup to display different data when the Hourly, Daily, Weekly and Monthly button is selected.

- Style the chart to match the style of the overall dashboard.
		
#### Create a Daily Traffic Bar Chart Widget:

- Use chartjs.org or a similar library create a bar chart like the one in the mockup.
- Display number of visits along the y axis and day of the week on the x axis.
- Style the chart to match the style of the overall dashboard.
		
#### Create a Mobile User Pie Chart Widget:

- Use chartjs.org or a similar library create a donut chart like the one in the mockup.

- Add a legend for mobile, tablet and desktop users.

- Style the chart to match the style of the overall dashboard.
		
#### Create a Social Stats Widget:

- Create a widget (or three separate widgets) to display social network stats for Facebook, Twitter and Google+.

- Use the provided SVG icons for each of the social networks.

- Style the social information to match the corresponding social network.

- Style to match the overall look and feel of the dashboard.
		
#### Create a New Members Widget:

- Create a widget that lists out new members in a table.

- Include avatar for each member, member name, email and join date (you can use UI Faces for member images, see Project Resources for the link).

-  Make up the information for the names, e-mail address and dates.

- Style to match the overall look and feel of the dashboard.
		
#### Create a Recent Activity Widget:

- Create a widget to display recent activity from members.

- Include the following types of activity: made a post, commented, new member signup.

- Include SVG icons for each different type of activity.

- Style to match the overall look and feel of the dashboard.
		
#### Create a Message User Widget:

- Create a widget for searching for a member and sending them a message.
- You don't have to add real search functionality, but if you attempt to get the exceeds grade you'll need to make up some user data.

- Add a message textarea field that lets you add a message.

- Use JS to allow you to submit the form and display a confirmation the message was sent. You won't actually submit the form, just simulate the action using JavaScript.

- Use JS to display error messages if user isn’t selected or message field is empty.

- Style to match the overall look and feel of the dashboard.
		
#### Create a Settings Widget:

- Create a settings widget to display various setting options using different form elements.

- Create an on/off widget for whether to send email notifications.

- Create an on/off widget for whether to set profile to public or private.

- Create a dropdown to select timezone.

- Add Save and Cancel buttons (these do not have to do anything functional).

- Style to match the overall look and feel of the dashboard.
