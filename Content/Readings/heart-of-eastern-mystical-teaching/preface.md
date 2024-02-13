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

# SECTION 02: URL / Directory Locations
url = "/From-The-East/The-Godly-Qualities/Purity-of-Heart"	# Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Posts-HEMT-Readings"	  # Directory = Layouts/Posts-HEMT-Readings
layout = "post-HEMT-Preface"  # HTML Template = post-HEMT-Chandausi

# SECTION 04: Post Byline Info
PostAuthor = "Chester Catalano"
PostPublishDate = "January 1, 2024"


# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
LandingPage_Name = "Preface"
mdThisPage_Name = "Preface"

mdThisPage_Overview = """
   Purity of Heart None.
"""

# SECTION 06: Additional Information


# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\Readings\Heart-of-Eastern-Mystical-Teaching\Chandausi\Preface.md)
