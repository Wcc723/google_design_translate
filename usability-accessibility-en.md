Usability > Accessibility

Accessibility


Contents
Accessibility


Accessibility
A product is accessible when all people—regardless of ability—can navigate it, understand it, and use it to achieve their goals. A truly successful product is accessible to the widest possible audience.





These general guidelines are a good starting point for designers who want to learn about accessibility.
Designing fully accessible products is a complex topic that requires in-depth study. For more info, visit the Google accessibility site.







How can your product best serve a user with disabilities?

To start, think about how users will interact with your product using assistive technologies. Imagine using your product in the following ways:

Without sound
Without color
With high contrast mode enabled
With the screen magnified
With a screen reader (no visible screen)
With voice control only
With a combination of the above
Then consider the following key areas that affect accessibility: navigation, readability, and guidance & feedback.

NAVIGATION

Help users to be fast and efficient. How easy is it to navigate the page quickly and efficiently (for example, jumping to key sections or getting back to primary navigation)? Present the most important information first. Small changes, like bringing a "create" button to the top, can make navigation much faster.



Make touch targets at least 48x48 pixels. 48x48 (px, dp) is the recommended minimum touch target size for any on-screen element. Also check how much space is between the elements of your mobile design. In most cases it should be 8 dp or more.



Support mouse-free and standard gesture navigation. Is every part of your design, any user task and every use case keyboard-accessible on web interfaces and accessible with the basic interaction gestures on mobile devices? Blind users can’t use a mouse to explore your interface in a visual way. Instead of a mouse, they will use their keyboard to navigate or swipe through elements on their mobile devices. Ensure that mouseover information is also accessible to users who don’t use a mouse. Make sure that the keyboard shortcuts are consistent with platform standards.

Manage the focus of your user. Are you sure that your user and their focus never get lost when navigating between pop ups, alerts, and various screens? Also think about how users will return to a screen after closing a pop-up window. Make sure that their focus will return to where it was before the pop-up opened.

READABILITY

Ensure the product is still usable with larger font sizes.

Is your text still legible when a user magnifies the screen or enlarges the font? Are the essential elements still visible, usable, and not overlapping? See it for yourself by using any of the built-in OS/Browser/App accessibility tools for zoom and large fonts.

Ensure critical text has enough contrast. In most cases, “sufficient contrast” means having a contrast ratio of 4.5:1. Enough contrast between the background and the text or critical elements allows all users and those with poor vision in particular to read your message more easily. Smaller text needs lots of contrast, while big headings can tolerate a wider range of colors and backgrounds.

Use more than just color to convey critical information. This is especially crucial for all color blind users. If colors in the design communicate specific information (for example, visualizing traffic: red = high traffic, green = no traffic) it is important to offer an alternate way for the user to get the same information. In addition to using color, add other elements like shapes, patterns, texture, or text.

Provide clues about spatial relationships. Is any information conveyed spatially or by layout that wouldn't be apparent to a blind user who navigates one element at a time? Since assistive technologies don't indicate the distance between elements, provide some additional clue that elements are related, like sharing a common heading.

Give visual alternatives to sound and vice versa. If you have audio elements, do you provide closed captions, a transcript, or another visual alternative? This guideline also applies to system alert sounds. Any flashing or blinking needs to be translated into a sound, and vice versa.

GUIDANCE AND FEEDBACK

Make interactive controls clear and discoverable. 
Do all interactive controls have associated text labels, tooltips, or placeholder text to indicate their purpose? Are you consistent in your terminology throughout the entire app? Provide the most relevant information first to the assistive technologies. When naming elements, make sure you're consistent in your terminology throughout your app.

Provide alternative text for images and video. Are you relying on graphical elements to convey information that isn't also provided in a written format? Do labels provide sufficient semantic context for the task (for example, not just "download" but "download dinner menu")? Provide alternative text for all images and icons, and avoid using images of text in cases where a standard widget would work.

Offer guidance and help. Can the user find help quickly when s/he does not know what an element is supposed to mean? If a critical element times out, is there a way for the user to reactivate it? Include clear and easy-to-find help and provide contextual help so that your user can look up what keyboard shortcuts or gestures are available and how to access and use features.

Give meaning to your links. Is the purpose of each link clear? Generic anchor text like “click here” does not explain a link’s purpose. Put the purpose of the link in the link text itself. A better solution to “click here” is a concrete link like "Device settings." Some assistive technology modes let the user scan just the links, ignoring other content, to make navigation more efficient.