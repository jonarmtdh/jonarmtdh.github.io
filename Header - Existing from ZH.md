# Usage
Headers are generally used for primary or secondary navigation, and to brand experiences. On web, headers may be coupled with sidebar menu navigation and enhanced by dropdown menus.Assembling web headers
  
    Basic Teladoc Health header

   image? 

    All header item types
  Image ?

  
Group header elements by functionality

Though header contents vary widely across the Teladoc Health ecosystem, the functionality of header elements remains fairly consistent. To further increase consistency, header elements should be grouped based on functionality. The functional groups we support are as follows:Branding (and partner co-branding, as applicable)Page title (as applicable to support legacy headers)

Header functional groups
    Insert image here
    
  
    Teladoc Health ecosystem headers with functional group mappings

Spacing and responsive behaviorOn large screens, headers should have a minimum height of 72 pixels and should have 24 pixels of left and right padding.On small screens, headers should have a minimum height of 64 pixels and should have 16 pixels of left and right padding.

Collapsed Header-menu behaviorHeader elements are responsive to changing viewport size. As the viewport shrinks, Header-item-expanded components should be swapped with Header-item-condensed components, horizontal padding should shrink, and header elements may need to be collapsed into a Header-menu element.All header elements may be collapsed into the Header-menu component except any branding or page titles.When tapped or clicked, the Header-menu component opens a drawer containing all collapsed options. Guidance for this drawer layout and componentry is coming soon!

Visual treatment and scroll behaviorIn their default state, headers may be solid or transparent depending on product context. Similarly, headers may or may not have a Horizontal-rule visually dividing the header from the content below. Headers should be separated from content by a minimum of 32px in padding on large screens, and a minimum of 16px in padding on small screens. Headers should not have elevation. Headers may be sticky or scroll with content.On scroll, sticky headers should have a fill with some transparency, a Horizontal-rule dividing the header from the content scrolled behind.

InteractivityIf using Header-item-condensed tools on devices that support hover, a tooltip label may be shown on hover to describe the header item. On tap/click, Header-items may reveal dropdown menus, modals, or drawers.

Brand assetsTeladoc Health brandsTeladoc Health brand logos should have a minimum width of 120 pixels.

Co-branded experiencesWhen products are cobranded with Teladoc Health brands, the branding assets should be combined into one single asset to ensure both logos scale approriately across various viewports.The cobranding partner logo should be no larger than 45 pixels in height. The Teladoc Health brand logos should be separated from the cobranding partner logos by space only; do not use a horizontal rule to divide the logos.

Page titlesPage titles may be appropriate in headers, such as in native mobile subpages. However, page titles are generally discouraged in primary navigation headers.If a page title is required in a primary navigation header to support legacy use, the title should be shown in Body Medium text style in Primary color. The title should be on the same baseline as all other elements in the header. Page titles are not preferred in future web headers and member-facing web headers.

Content guidelinesUse sentence case for page titles, navigation tabs, and header item labels