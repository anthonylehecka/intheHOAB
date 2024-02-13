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
BreadcrumbThisPage = "Chapter 16 Verse 1"

# SECTION 02: URL / Directory Locations
url = "/From-The-East/The-Godly-Qualities/Introduction-C16-V1"	# Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Posts-Godly-Qualities"	 # Directory = Layouts/Posts-Godly-Qualities
layout = "post-GQ-Introduction"  # HTML Template = post-GQ-Introduction

# SECTION 04: Post Byline Info
PostAuthor = "Chester Catalano"
PostPublishDate = "January 1, 2024"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
# This is not a Landing Page but using the variable for the Site Main Menu to work.
LandingPage_Name = "Introduction"
mdThisPage_Name = "Chapter 16 Verse 1 Introduction"

Post_WelcomeLine = "Post Welcome Line Text Goes Here"
Post_Intro = """
  Post Introductory Remarks Go Here
"""

# SECTION 06: Additional Information


# Note: Anything below these variables will be considered the "Content" of this page

+++

I am <u><i>content\From-The-East\The-Godly-Qualities\Introduction-C16-V1.md</i></u>
