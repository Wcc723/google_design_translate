Settings

Contents
Settings





Settings

Application settings allow users to indicate their preferences for how your app should behave. They grant the user a genuine sense of control, and can be useful in avoiding repeated interruptions with the same question.
Accessing Settings

Settings are given low prominence in the UI because they’re not frequently needed by users. When your app uses settings: In all cases, the action for accessing “Settings” should be simply labelled “Settings”. If the current screen supports a left nav bar, place “Settings” in the bar, below all other items except “Help & feedback”. Otherwise, if there is a toolbar for this screen, place “Settings” in the toolbar’s action overflow, below all other items except “Help & feedback”.
Using Settings Appropriately

When users visit Settings—however infrequently—they’ll hold this screen to the same expectations as the rest our your experience. It should be well-organized and predictable. In particular, it should avoid overwhelming the user with too many options. Avoid the temptation to punt on difficult product decisions by giving in to the urge to “just make it a setting”. For each control you’re considering adding to Settings, make sure it’s appropriate by asking the following questions: Is this actually a user preference? Information and actions are not user preferences.If not, don’t make it a setting. If it’s static information about the app (e.g. version number, terms of service, open source licenses), organize it into a Help screen. If it’s an action (e.g. refresh, change account), find an appropriate place for it within the main flow of your app. Is this very infrequently changed by users? Would users feel burdened by taking multiple actions to access this control each time?If not, don’t make it a setting. Make the control more readily available, possibly via a toolbar or action overflow. Would less than 20% of users change the value of this control? If not, don’t make it a setting. These same questions should be applied to both new and existing settings. For existing settings, the last question may be tempered: If the setting were removed, would it cause harm to the minority who would no longer be able to change it? If so, if you’re not note, then maintaining it as a settings is appropriate.
Grouping Settings

When you have many settings, turn one long list into multiple shorter lists by clustering them. Your strategy for arranging them will depend on the total number of settings.

7 or fewer settings
Don’t group at all. 



8 to 10 settings
Try grouping related settings under 1 or 2 section dividers. If you have any "singletons" (settings that don't relate to any other settings and can't be grouped under your section dividers), treat them as follows:

If they include some of your most important settings, list them at the top without a section divider.
Otherwise, list them at the bottom with a section divider called "OTHER", in order of importance.


11 to 15 settings
Same advice as above, but try 2 to 4 section dividers.

Also, look for "doubles": two settings that relate to one another, but not to any other settings. Try to combine them into one setting. For example, you might be able to redesign two related checkbox settings into one multiple choice setting. 



16 or more settings
If you have any instances of 4 or more related settings, group them under a subscreen. Apply the guidance above to each subscreen.
Choosing defaults

Users will expect the initial value for each setting to be sensible. The following questions can help inform your decisions: Which choice would most users be likely to choose on their own if there were no default? Which choice is the most neutral or middle-of-the-road? Which choice is the least risky, controversial, or over-the-top? Which choice uses the least amount of battery or mobile data? Which choice most respects the user’s attention, and only interrupts when it is important?
 