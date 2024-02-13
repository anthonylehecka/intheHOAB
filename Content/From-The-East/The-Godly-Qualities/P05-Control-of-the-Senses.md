+++
# This is a TOML markup document as evidenced by the +++ instead of --- for YAML
# Notes for Markup files in content and rendering html in layouts
#    type is the directory to find the layout in. Example type="Pages-OneOff" means look in layouts\Pages-OneOff
#    layout is the filename in the type directory to use. type="Pages-OneOff" with a layout of "about"
#    means to use the about.html file in the layouts\Pages-OneOff. N.B. that layout DOES NOT INCLUDE .html
#
# Notes for assigning front matter variables in TOML
#    variablename = "some string"

# SECTION 01: Meta Data
draft = false
debugpage = true

BreadcrumbPageLevel = "4"
BreadcrumbHomePage  = "Home"
BreadcrumbGrandParentDir = "From-The-East"
BreadcrumbGrandParentPage = "From The East"
BreadcrumbParentDir = "The-Godly-Qualities"
BreadcrumbParentPage = "The Godly Qualities"
BreadcrumbThisPage = "Control of the Senses"

PostNav_hasPrev = true
PostNav_prevPost_URL = "/Giving"
PostNav_prevPost_Name = "Giving"

PostNav_thisPost_Name = "Control of the Senses"

PostNav_hasNext = true
PostNav_nextPost_URL = "/Worship"
PostNav_nextPost_Name = "Worship"

# SECTION 02: URL / Directory Locations
url = "/From-The-East/The-Godly-Qualities/Control-of-the-Senses"  # Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Pages-Shared-Layouts"   # Directory = Layouts/Pages-Shared-Layouts
layout = "Post-Godly-Quality"      # HTML Template = Page-Series-TOC.html

# SECTION 04: Post Byline Info
author = "Chiestro Catalano"
date = "2024-02-01"
publishdate = "2024-02-01"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "Control of the Senses"
mdThisPage_WelcomeLine = "Control of the Senses"

# SECTION 06: YouTube Block
mdYouTube_numofVideos = "1"
mdYouTubeV1Name = "Video: Control of the Senses"
mdYouTubeV1Link = "https://youtu.be/_v_C-UbclNY"

# SECTION 07: Sanskrit Block
Post_Sanskrit_Text = "दम"
Post_Sanskrit_Translation = "Control of the Senses"

# SECTION 08: Page Specific Info
mdHasImageAttribution = true
mdImageAttribution = "Image Attribution"

# Note: Anything below these variables will be considered the "Content" of this page

+++
{{< rawhtml >}}
  <raised-content-box class="rcb-shadow-upper-left">

I am (content\From-The-East\The-Godly-Qualities\Control-of-the-Senses\P05-Control-of-the-Senses.md)

  </raised-content-box>
{{< /rawhtml >}}