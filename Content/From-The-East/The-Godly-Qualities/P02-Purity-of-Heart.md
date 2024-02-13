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
BreadcrumbThisPage = "Purity of Heart"

PostNav_hasPrev = true
PostNav_prevPost_URL = "/Fearlessness"
PostNav_prevPost_Name = "Fearlessness"

PostNav_thisPost_Name = "Purity of Heart"

PostNav_hasNext = true
PostNav_nextPost_URL = "/Steadfastness-in-Knowledge"
PostNav_nextPost_Name = "Steadfastness in Knowledge"

# SECTION 02: URL / Directory Locations
url = "/From-The-East/The-Godly-Qualities/Purity-of-Heart"  # Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Pages-Shared-Layouts"   # Directory = Layouts/Pages-Shared-Layouts
layout = "Post-Godly-Quality"      # HTML Template = Page-Series-TOC.html

# SECTION 04: Post Byline Info
author = "Chiestro Catalano"
date = "2024-02-01"
publishdate = "2024-02-01"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "Purity of Heart"
mdThisPage_WelcomeLine = "Purity of Heart"

# SECTION 06: YouTube Block
mdYouTube_numofVideos = "2"
mdYouTubeV1Name = "Video: Purity of Heart (Part 1)"
mdYouTubeV1Link = "https://youtu.be/-RBxV5p7Ewc"
mdYouTubeV2Name = "(Part 2)"
mdYouTubeV2Link = "https://youtu.be/StsHcnPvEf4"

# SECTION 07: Sanskrit Block
Post_Sanskrit_Text = "सत्त्वसं शुद्धिर्"
Post_Sanskrit_Translation = "Purity of Heart (or of Being)"

# SECTION 08: Page Specific Info
mdHasImageAttribution = true
mdImageAttribution = "Image Attribution"

# Note: Anything below these variables will be considered the "Content" of this page

+++
{{< rawhtml >}}
  <raised-content-box class="rcb-shadow-upper-left">

I am (content\From-The-East\The-Godly-Qualities\Purity-of-Heart\P02-Purity-of-Heart.md)

  </raised-content-box>
{{< /rawhtml >}}