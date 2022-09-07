# Design

This header introduces 3 main size variants (SM, M, L) with toggles for:
* Expanded/Condensed (New header item subcomponent)
* Signed in/out
* 12 total main variants

## Subcomponents
~Header/Subcomponents/~

### Left side:
* Logo (for 4 TDOC brands - Current, legacy, legacy LVGO, legacy MyStrength)
* Cobrand placeholder
* Page or site name placeholder
* Tab-item

### Right side:
*  Header-item
    -  Help
    -  Messages
    -  Profile (has condensed and expanded versions)
    -  Hamburger menu (for small & medium sizes)

## Changelog
* Dramatically reduced the amount of variants in this component
### Introduced
* New Menu item subcomponent (multiple states; Editable label)
* New cobranding subcomponent
* Propped Primary brand logo selector
* Header-item subcomponent (propped badge; propped icon, with boolean and propped Label)
* Propped Tab 
* Propped Header-profile subcomponent
    -  Avatar (propped, boolean)
    -  Icon button (propped, boolean)
    -  User Name (propped, boolean)
* Header-sign-in subcomponent (boolean)
* Boolean icons (right side of header)
* Boolean for signed in/signed out
* Introduced hint icons in front of the layer name in actionable layers:
    -  A pointer icon prior to the layer name to indicate where a user can select that layer to further edit a subcomponent
    -  A pencil icon prior to the layer name for editable text layers
* New sizing:
    -  Small - 375
    -  Medium - 768
    -  Large - 1200
* Followed guidance from existing header work using auto-layout to space subcomponents