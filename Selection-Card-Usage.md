> Ensure that the existing component content is saved (duplicated in
> separate tab) before making edits to the tab that is active 

## Overview

### Use case —  items with a lot of metadata

The primary use case for a `Selection Card` is when the item to be selected contains complex and varied information. Current examples include:
- Pharmacy selection where there is more information than a singular label –Name, Address, distance from member, hours of operation; 
- “Who needs care today?” where a member name, age and assigned gender at birth is displayed
- Payment method – Credit card number, issuing organization (AMEX, MasterCard, Visa, etc) and expiration date

This component is not restricted to only these use cases. designers should feel free to design their own use cases. To allow for this, we provide a “shell” version of the component. This consists of two slots:

* **Full-width** – extends the full width of the component, minus padding; Should never be used alone, as the selection indicator (radio button or checkbox) will not align appropriately; This is provided as a header for the Selection Card allowing freedom to have elements expand the inner width of the card;
* **Body and Action** – This is the area for content and contains the selection element  which is vertically aligned middle to the Body. No matter how tall the Body is, the Action (`Radio Button`, `Checkbox`) will align to the vertical center of Body

#### Use case —  Large but simple selectable items

There is another, seemingly counterintuitive use case to the Selection Card and that is as a large Radio Button or Checkbox. These are used in lists of items where the design calls for amplifying the visibility and interactivity of selectable items. It is still a card, but consists only of  a label and the selection indicator. 

**Examples for this use case are:**

* **Single select list of types of care:** - Urgent care, primary care, mental health, etc. 
* **Single select OR multiple selection of symptoms/conditions** 
* **Multiple selection of list items** - Member choices for how they are looking for help with chronic condition management such as: eating well, physical fitness, quit smoking, weight management
* **Replacement for dropdown lists with 5 or less items**

### Why use this over regular components?
`Selection Card` is meant to draw attention to the possible items and be easier to use than regular components. Use `Selection Card` when the primary action on a screen is to make a selection and then move on in a flow.

Use `Selection Card` when ease of use and attention to a selection is more important than presenting tons of data or information. The action area/tap target is the entire card and is easier to interact with. This is a benefit for members with mobility and vision issues. Seeing which items have been selected is an easier cognitive lift and the selection itself requires less fine motor precision.

### When do I use regular components instead?
Complex, data dense screens where the selection of items is one of many actions needed to complete a flow or step are more suited to the regular components;
When there is a premium placed on vertical spacing; Selection Cards are meant to be large and easy to interact with and read but take up more vertical real estate than regular radio buttons and checkboxes;

 
### [Selection Card]

[Briefly discuss how component could have potential variants, styles, and options. Include any additional components (optional) if needed.]

It is ideal for [calling out / highlighting / focusing / achieving desired consequence etc].



## Product usage

Some common uses include:

[Flow or page]
[Flow or page]
[Flow or page]


## Component usage

[This section is condition to if component is used in other complex components; if not needed, "Component usage" section can be removed.]

As a basic component, this component is leveraged in other Pulse complex components including:

[Basic-component]
[Basic-component]



## Anatomy

 
Add
[Element / component *ensure name is what is used in eng; add hyperlink to text if available]


**If there are anatomical differences between web and native components...

Add "Web" sub-header (H3) to existing anatomy section above
Duplicate image and paragraph template of anatomy below web section; add "Native" sub-header (H3); if needing iOS and Android specificity, repeat this step and add respective "iOS" and "Android" sub-headers (H3)



## Variants and options

You can inspect each variant and style in the Figma tab. 

**If there are anatomical differences between web and native components...

Add "Web" sub-header (H3) to existing anatomy section above
Duplicate section of Image Upload above and place below; add "Native" sub-header (H3); if needing iOS and Android specificity, repeat this step and add respective "iOS" and "Android" sub-headers (H3)



## Placement

### [Placement guidelines title 1]

This section is an example of when a full-scale image is used to demonstrate placement, alongside an title and description. 

The image can display an entire desktop or mobile view, partial view of a desktop or mobile view, partial view of a desktop or mobile view, full or partial view of a complex component, or a general layout of basic comments. 

Write a general description about what is in the full-width image. May or may not include badging to specify specific parts of the image. 



### [Placement guidelines title 2]

Add another rule
Do
Don't
Caution


Do



Don’t




## Interaction

[This paragraph is a brief description of interaction targets available to the user.]


**If there are interaction differences between web and native components...

Add "Web" sub-header (H3) to existing interaction section above
Duplicate image and paragraph template of interaction below web section; add "Native" sub-header (H3); if needing iOS and Android specificity, repeat this step and add respective "iOS" and "Android" sub-headers (H3)



## Animation 

**If there are animation differences between web and native components...

Add "Web" sub-header (H3) to existing interaction section above
Add "Native" sub-header (H3); if needing iOS and Android specificity, repeat this step and add respective "iOS" and "Android" sub-headers (H3). Content can be broken down as image step-by-step as above OR listed out as simple bullet points.



## Examples 






## Content guidelines

[All of content guides should be broken down as sections (i.e., each guideline, a section). Each section has a bold paragraph title followed by a description as paragraph, followed by using the Rules widget. Content guidelines can be used for SPECIFIC content or icons usage within the component.] 

### [Guideline #1]

Text used in button should generally be one or two words, four at max. Fewer than 20 characters should be used (including spaces).

Avoid using punctuation marks, emojis, or symbols.

Add another rule
Do
Don't
Caution


Do



Don’t

For general guidance on how to write for Teladoc Health products, see Content.




## Accessibility

### General considerations

[Description of any accessibility standards when considering the component. If the guidance applies to all platforms, this section is where to document]

[Subsection title, e.g., "Keyboard shortcuts"]

[Description of specific consideration]
[Description of specific consideration]
[Subsection tite, e.g., "Screen reader considerations" ]

[Description of specific consideration]
[Description of specific consideration]
[Description of specific consideration]


### Web considerations 

[Have "Web considerations" section if there are web-only considerations, such as navigating using the web browser]
[Description of specific consideration]
[Description of specific consideration]


### Native considerations

[Have "Native considerations" if there are native-only considerations, such as swiping between pages]
[Description of specific consideration]
[Description of specific consideration]



## Related 







Add shortcut



## Changelog

Date
Number
Notes
Mon XX, 202X
vX.X.X
Line item
Mon XX, 202X
vX.X.X
Line item
Line item
Mon XX, 202X
vX.X.X
Line item



## Pulse Team Checklist

Checklist legend

📝 = In progress 🔍 = In review✅ = Completed

⛔ = Not in scope

Status
Item
Description

Usage, Overview
Include brief description of intended use, any variant or style descriptions, and possible usage across other components, pages, and flows

Usage, Anatomy
Breakdown of the main component
Breakdown of any optional components

Usage, Variants and options
Include all possible variants 
Include all possible options

Usage, Placement
Show low-to-med fidelity of component placement on UI, surfaces, complex components etc.

Interaction *conditional
Include when component has interaction requirements (click, tap, gesture etc).
⛔
Usage, Animation *conditional
Include when animation is pertinent to the component UX (e.g., toast notification)
⛔
Usage, Examples 
Include when a vetted, production example is readily available
⛔
Usage, Content guidelines
Includes content standards and best practices for how to write for the specific component
Review with Content team
⛔
Usage, Accessibility 
Include specific component considerations as bullet-point guidelines
Review with a11y team
⛔
Usage, Related 
Include other components that broadly relate to the function of the component
Briefly explain how this component differs in usage but addresses similar needs 

Usage, Changelog

Include 2.2.0 and any 3.0.0 versioning
⛔
Figma, 2.2.0
Existing content will need to be reevaluated to provide consistent, comprehensive information

Figma, 3.0.0 Props
Provide overview of component properties used for main component(s) and any conditional sub-components
Provide matrices list of all variants available (as image assets)
Provide conditional "build tips" if rules, guidance, maintenance, or other extra steps is needed to use the component


