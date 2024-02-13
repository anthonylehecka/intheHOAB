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
BreadcrumbGrandParentDir = "Readings"
BreadcrumbGrandParentPage = "Readings"
BreadcrumbParentDir = "Heart-of-Eastern-Mystical-Teaching"
BreadcrumbParentPage = "The Heart of Eastern Mystical Teaching"
BreadcrumbThisPage = "Chandausi"

# SECTION 02: URL / Directory Locations
url = "/Readings/Heart-of-Eastern-Mystical-Teaching/Chandausi"	# Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Posts-HEMT-Readings"	  # Directory = Layouts/Posts-HEMT-Readings
layout = "post-HEMT-Chandausi"  # HTML Template = post-HEMT-Chandausi

# SECTION 04: Post Byline Info
PostAuthor = "Chester Catalano"
PostPublishDate = "January 1, 2024"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
# This is not a Landing Page but using the variable for the Site Main Menu to work.
LandingPage_Name = "Chandausi"
mdThisPage_Name = "Chandausi"

Post_WelcomeLine = "Post Welcome Line Text Goes Here"
Post_Intro = """
  Post Introductory Remarks Go Here
"""

# SECTION 06: Additional Information


# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\Readings\Heart-of-Eastern-Mystical-Teaching\Chandausi\Chandausi.md)
