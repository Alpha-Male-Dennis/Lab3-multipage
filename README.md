Contributors: Dennis Chipman - 2021532097

PAGE DESCRIPTIONS

index.html (Home Page)

Hero banner (text + welcome + button)

Includes two sections in main horizontally-oriented flexbox layout:

Left part: Rich "About Us" text with the info about a company and some core services list

I notice your left sidebar ( "AF Blog" ) which has some promotional content and images of the latest news on the right sidebar.

The Home link in the navigation bar active

– Footer with copyright notice

services.html (Services Page)

A services introduction section

Comes with a responsive grid of service cards (6 total)

Each card includes:

Emoji icon for the service

Service name heading

Brief service description

Services link in the navigation bar should have active class

Copyright Footer

contact.html (Contact Page)

Includes a section to introduce the contact

Custom contact form with styles:

Name field (text input)

Email (Validating email input)

Subject field (text input)

Message field (textarea)

Submit button

Form has HTML5 Validation (required fields)

Active class on Contact link in the navbar

Copyright notice in the footer

SHARED ELEMENTS ACROSS ALL PAGES:

Same header with logo and navigation

Responsive design that works on all device sizes

Highlights state for current page in the menu

Footer match with copyright year

CSS FEATURES SUMMARY

SELECTORS:

Universal selector (*)

Type selectors (body, header, nav, ul, li, a, etc.)

Class selectors (. logo,. nav-links,. hero,. btn, etc.)

ID selectors (none used)

Attribute selectors (none applied)

Pseudo-class selectors (e.g., :hover, :focus, :active)

Descendant combinators (line)

Child combinators (none employed)

Adjacent sibling combinators (none used)

Sibling combinator general ([none used])

FLEXBOX:

Used in navigation (nav)

Used in main layout (. flex-container)

Properties used:

display: flex

justify-content

align-items

flex-direction

flex

gap

CSS GRID:

Used in services layout (. grid-container)

Properties used:

display: grid

grid-template-columns

repeat()

auto-fit

minmax()

gap

MEDIA QUERIES:

3 breakpoints:

max-width: 1024px

max-width: 768px

max-width: 480px

Used to modify:

Navigation layout

Flex direction

Grid columns

Font sizes

Padding/margins

Component layouts

ANIMATIONS & TRANSITIONS:

Fade In Animation using @keyframes

Transition effects:

color transitions

transform transitions

box-shadow transitions

all-property transitions

Applied to:

Navigation links

Buttons

Service cards

Form inputs

Hero section

OTHER FEATURES:

– Box model excluding properties (padding, margin, border-radius)

Box-shadow effects

Positioning (sticky header)

– Responsive images (max-width: 100%)

Viewport relative units (rem used throughout)

CSS variables (none used)

Custom font family

z-index usage

CSS VARIABLES:

Defined in :root

Variables used everywhere for colors, shadows, transitions

SPECIAL EFFECTS:

Gradient text (.logo)

Gradient borders (::before pseudo-elements)

Custom bullets (::before on p)

Box shadows (var(--shadow))

Text shadows

Background-clip: text

Properties transform (scale, translateY)

Linear gradients

Border-radius

RESPONSIVE TECHNIQUES

Fluid typography (using relative units: rem)

Fluid grids (auto-fit minmax)

Mobile first (max-width queries)

Responsive Images (max-width: 100%)

Responsive spacing (adjustments to padding/margins)

ORGANIZATION

CSS custom properties:

Sectioned comments

Related styles that are logically grouped

Media queries with mobile styles sequestered inside