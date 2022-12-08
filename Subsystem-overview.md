# Pulse Subsystems
{:toc}

#### Usage tab

## Overview
<!-- Hero image -->

In order to talk about subsytems, we need to be able to correctly assess where a product or feature are in the adoption lifecycle. 
There are generally 5 publicly facing adoption levels of Pulse that can involve subsystem usage.

1. **Pulse Toe Dipper**: product or feature is using Effra as the primary font for the screens;
2. **Pulse Starter**: product or feature is beginning to use design tokens; UI Light theme primary/secondary/neutrals
3. **Pulse Adjacent**: Tokens inform product design; coding visual designs into production (hard coded or mix/match actual CSS tokens)
4. **Pulse Legacy**: Pulse adopted! This is likely going to be where most products/features live in the Pulse ecosystem; Pulse will continue to grow and evolve, but most products won't be using newer versions and the adoption may be a version or two behind the latest version
5. **Pulse Latest**: The most current publicly shipping version of Pulse; mostly used for evolving Pulse coded products to include the latest features, themes, componentry; Design will be the first adopters for Latest

**Pulse Alpha**: An offiical sandbox and test for proof of concepts and next generation approaches. This is not something that is supported for use in production, but evaluating what may make it into the Latest branch.

As of this writing, the only complete version in product is for Livongo.com. It is using a legacy version of Pulse 1.*. 

The Teladoc [sales instance base site](https://member.usa.sales.teladoc.io/) could be classified as a Pulse Toe Dipper as it uses Effra and legacy brand colors (but does not refer to the colors or font-family in a tokenized way):

[Sales demo example](/images/220926-sales-instance-rav-mh.png)

However, the WebSDK project uses 

`TK content for WebSDK`

## Anatomy

Subsystems anatomy begins at the product level. 

The first element in a subsystem are the styling tokens. Pulse doesn't try to prescribe as much as it does provide guard rails. Pulse is a global system and should be able to be used to design consumer, provider/clinical and enterprise grade (client) experiences. Spacing, typescale, and grid/layout can be modified to suit a given experience, but Pulse tokens shouldn't be modified directly. 

Matching the adoption pattern, subsystems start with the basic, atomic levels and move up to an entire environment for design and development that is Pulse-first where a developer doesn't have to re-invent universal/global components such as buttons, form elements, or other UI controls.

* Typography - Using brand typeface/font-family(ies) wherever appropriate
* Typescale - Using UI Light theme typescale patterns (t-shirt sizing: Headings XL, L, M; Body Default, small, Input default, Button default, etc.)
* Color - using appropriate hex, rgb, hsl/hsb values; Better adoption would be to use the Pulse color tokens which reference Primary, Secondary, Neutral and Status color tokens.
* Form elements and UI controls - Text inputs, Select, datepicker, checkbox, radio buttons, chips
* 

Most products as of this writing (Monday, September 26, 2022) are either at a Toe Dipper or Starter level. The product screens may be designed using Pulse, but the codebase is hard coded or doesn't reference design tokens. There are a few products that are further along in design and development and they include Healthiest You, the Acme Health subsystem and most recently, the OneApp project. 

## Current examples

### Healthiest You

Historically, this was the first sub-brand to use a design system informed design using Triage (2020-literally a triage design system in Sketch/Abstract) and has recently been using a forked version of Pulse 1.x styles ([Pulse: HY Styles](https://www.figma.com/file/Y1a1opMhm50xF78AJ894yz/Untitled)) and components ([Pulse: HY Styled Components](https://www.figma.com/file/e9aMJT9QTFklORcUF09CPk/Pulse-HY-Components)) for restyling.

Healthiest You features a subset of core Teladoc experiences and the restyling project designs can be seen here: [HY Screens](https://www.figma.com/file/EO15e06sADFG0ofbAdNGm6/HY-Screens-2022).

Design is using forked version of Pulse 1.x and has retained component naming conventions from that fork. 

### Acme

Initially started as a way to give designers and develoeprs a starter pack of components and design tokens they could use to leverage for white label (PLI) work. It became one of the first projects in Figma to use Pulse components, but be styled using a fork of Pulse 1.x Style Library, [Acme White Label Theme](https://www.figma.com/file/u3QAQlnwHibHuONhqHzze0/Acme-White-Label-Theme-(Copy)), a Figma style library. The project also has it's own component library as well, [Acme PLI Component Library](https://www.figma.com/file/tTqYsFKy9D1qw3TY1OGgQf/Acme-PLI-Component-Library).

### One App project

This project is a major integration project slated to launch on 1/1/2023. This project is intended to merge MyStrenght and Livongo legacy products into the core Teladoc experience, including profile, health device data, health history, et al) when a member logs in to member.teladoc.com.



## Path to adoption - Your success roadmap

### For designers: Design system links

### For developers: Dev environment links

### How to move your project to use Pulse Latest





<!-- ## Variants and options
You can inspect each variant and style in the Figma tab. ["Color overrides" as a subsection here].

Variant Name variant 1
Note for variant 1: [Write about the specific use of variant and the role it serves in an interface. Write it in relation to other variants to give context and guidance. Always include specific scenarios that are appropriate, considerations, and any direction on limitations or when not to use variant]
Variant Name variant 2
Note for variant 2: [Write about the specific use of variant and the role it serves in an interface. Write it in relation to other variants to give context and guidance. Always include specific scenarios that are appropriate, considerations, and any direction on limitations or when not to use variant]
Variant Name variant 3
Note for variant 3: [Write about the specific use of variant and the role it serves in an interface. Write it in relation to other variants to give context and guidance. Always include specific scenarios that are appropriate, considerations, and any direction on limitations or when not to use variant]
etc

### Options
Figma upload, annotated in ZH? for each option example

Options title 1, Example: States
Note for Option 1 
[Highlight when a component supports different states.]

[State name 1] [Component name] types
[State name 2] [Component name] types
[State name 3] [Component name] types
[State name 4] [Component name] types
[State name 5] [Component name] types
[State name 6] [Component name] types

[Include any considerations for each state (e.g., Loading) and any platform-unique instances.]

Options 2, Example: Sizing
Note for options 2: [Sections describing sizing options should breakdown all sizing options available and context as to when to use them.]
[Size name] [Component name] size
[Size name] [Component name] size

[Options title 3, Ex: "Icons"] options
[Sections describing an optional feature of a component (e.g., icons support) should be broken down of all different styling options available, when to use said optional feature, best practices, and when or how NOT to use them. Best to clarify if intention of use differs between Pulse kits ]

[Component name] [icon placement description]
[Component name] [icon placement description]
[Component name] [icon placement description]

[Options title 4, Ex: "Destructive"] options
[Write about the specific use of variant and the role it serves in an interface. Write it in relation to other variants to give context and guidance. Always include specific scenarios that are appropriate, considerations, and any direction on limitations or when not to use variant]

## Placement
[use 2 column layout]

Placement guidelines title 1
Hero image(s) of grayscale wireframe with the placement in Color
[This section is an example of when a full-scale image is used to demonstrate placement, alongside an title and description. The image can display an entire desktop or mobile view, partial view of a desktop or mobile view, full or partial view of a complex component, or a general layout of basic comments. Write a general description about what is in the full-width image. May or may not include badging to specify specific parts of the image. Can also discuss how a component RESIZES across all of Placement sections]

Placement guidelines title 2
Img upload for each guideline
[Write a description about the image demonstration of placement. Take notes on what the general behavior is, any exceptional worth demonstrating, how it may alter across different media queries etc.]

[Write a description about the image demonstration of placement. Take notes on what the general behavior is, any exceptional worth demonstrating, how it may alter across different media queries etc.]

Placement guidelines title 3
(This section is an example of when utilizing Rules widget to demonstrate placement guidelines for component). [This is a paragraph description of what this guidance is about]

then do and don't examples and any other Rules

## Interaction (optional)

[Interaction bold title — e.g., explaining tap target specifics of entire, specific, or gesture interaction]

Figma upload annotated Hero
[description of interaction]

## Animation or motion (optional)

Animation frames with descriptive notes for each frame 
Frame 1
Note for frame 1

Frame 2
Note for frame 2

Frame 3
Note for frame 3

## Examples (optional)
Product image upload?
caption 

## Content guidelines
[All of content guides should be broken down as sections (i.e., each guideline, a section). Each section has a bold paragraph title followed by a description as paragraph, followed by using the Rules widget. Content guidelines can be used for SPECIFIC content or icons usage within the component.] 

[Be succinct]

[Text used in button should generally be one or two words, four at max. Fewer than 20 characters should be used (including spaces).

Avoid using punctuation marks, emojis, or symbols.]

Do and don't examples
 -->
