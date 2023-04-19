> Ensure that the existing component content is saved (duplicated in
> separate tab) before making edits to the tab that is active 

## Overview

### Use case —  items with a lot of metadata

The primary use case for a `Selection Card` is when the item to be selected contains complex and varied information. Current examples include:

- Pharmacy selection where there is more information than a singular label – Name, Address, distance from member, hours of operation; 
- “Who needs care today?” where a member name, age and assigned gender at birth is displayed;
- Payment method – Credit card number, issuing organization (AMEX, MasterCard, Visa, etc) and expiration date (`Selection Card` can display warning and error states "this card will expire in less than 30 days, please update this method of payment"; "This payment method has expired, please update")

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

