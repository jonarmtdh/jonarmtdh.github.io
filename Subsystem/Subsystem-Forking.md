# Summary
This document is written from the perspective of someone needing to take existing design work and re-theme it with new colors and fonts.
This tutorial will reference Pulse: Components as well as Pulse: Core Styles libraries. 

## Assumptions 
This tutorial assumes:
* You have a knowledge of how Figma structures work areas, projects and working files. If you need to understand this aspect of Figma, you can learn more [#](here). <!-- needs link -->
* You have work that uses Pulse components and styles, with no custom overrides
any overrides will not be affected by a library swap; text doesn't count as an override but text styling does count as an override, so any custom text styling outside of Pulse styles will not be affected by any style library swap
* You have privileges to make a folder, edit files in that folder and Figma privileges to publish libraries
* You save to version history often, especially prior to performing major changes to a given document, whether or not it is a style library; Figma does autosaves, but not always at the best points of activity
* You are making changes to a file that may potentially affect other work, so you are moving carefully through this process
* You know how to edit color styles (colors only, not renaming the colors)
* You have access to a custom Figma plugin called "Semantic Color Sync"
* You are part of Core UX and have editor access to Pulse libraries
* You will not rename any of the colors, styles or components in the Pulse Core Style library; this cannot be stressed enough: DO NOT RENAME ANY STYLES, LAYER NAMES OR COMPONENT NAMES

### Plugins required
`Semantic Color Sync`

## Step 1: Ensure you have edit privileges
Wherever you will be working on the documents that will be themed differently, make sure you have edit access to the appropriate project. You need to create a folder inside of that project. If a client or project already has a folder, make sure you have edit access to that folder. You will follow similar steps to [subsystem-Theming](Subsystem/Subsystem-Theming.md). However, you will want to indicate that you are forking the design system in your files and in your local documentation.


#### Naming tip 
Use "ClientName Theme Style Library". If we were working on a client called CVS, we would name the library:  CVS Theme Style Library. There may be only one file in this project, but this will ensure the style library is easy to locate.

## Step 2: Duplicate the Pulse: Core Styles library
Locate the Select the Pulse Style Library, right click and select duplicate:
![Figma screenshot](/images/211028-full-screen-duplicate.png)

Figma will create a new style library that has a (Copy) at the end of the title:

![Figma screenshot](/images/211028-duplicated.png)

This is the library we will move to our project from Step 1

## Step 3: Move the duplicate Pulse style library 
Simply drag the file to the project in the left hand project navigation rail in Figma:

![Figma screenshot](/images/211028-left-rail.png)

Your left rail will look different, this is just an example for reference.

## Step 4: Rename the new style library 
Right click on the library file and select "Rename":

![Figma screenshot](/images/211028-pulse-style-rename.png)

I've renamed the duplicated library to "Pulse: Neutral".
You should also open the file and edit the Cover page so that it can't be confused with the actual Pulse: Core Styles style library:

![Figma screenshot](/images/211028-renamed-style-library.png)

For the purposes of this tutorial, I have called the duplicated style library "Pulse Neutral" and I updated the cover page with a gray background and changed the title text. I also added my name under the design subheading so that it's clear to others who they need to contact if there are any questions or issues.

Save to version history (File > Save to Version History):

![Figma screenshot](/images/211028-save-to-version-history.png)

When Figma pops up the version history save modal, type "New library start" or something that indicates a human is working on this file and it is the beginning of that work.

## Step 5: Make a copy of your work file 
We need to test our work before we apply the new library, so I suggest that you duplicate your work file(s) and move them to the project from Step 1:

![Figma screenshot](/images/211028-working-file-dupe.png)

Move by dragging the duplicated file:

![Figma screenshot](/images/211028-moving.png)

Renamed:

![Figma screenshot](/images/211028-renamed.png)


## Step 6: Open the new style library and edit

In the new style library, you can now go into the library and make changes to colors (E.g., change primary and secondary color ramps) and font family (e.g., change Effra to Roboto). 

🚫 Do not: 🚫 
* change any colors other than the Primary and Secondary
* change any color names
* change the names of styles

✅ Do: ✅
* edit the primary and secondary color styles
* edit the font family styles if needed

> Technically, you could edit all the colors, but for white label theming, don't change anything but Primary & Secondary colors and font family.

#### Color: Primary and Secondary color ramps
The 50-900 color ramps for the colors in Pulse were developed carefully with an eye toward accessibility and ease of reading as well as a cohesive visual language. Clients requesting white labelling may not have as many colors or shade/tint variants as pulse does. That's fine. Client colors might have differing hue values that don't quite match Pulse's scale. This is not a huge concern as long as there is a Primary color and some suggestion of a light and dark variant for that Primary color. 

It is up to the designer to use the client primary color and change Primary/800 to the client primary color, the dark to Primary/900 and the lightest to Primary/050.

