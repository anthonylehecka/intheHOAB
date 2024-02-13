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
BreadcrumbParentDir = "Zen-Stories"
BreadcrumbParentPage = "Zen Stories"
BreadcrumbThisPage = "A Cup of Tea"

# SECTION 02: URL / Directory Locations
url = "/From-The-East/Zen-Stories/A-Cup-of-Tea"	# Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Posts-Zen-Stories"	       # Directory = Layouts/Posts-Zen-Stories
layout = "post-ZS-A-Cup-of-Tea"    # HTML Template = post-GQ-Fearlessness

# SECTION 04: Post Byline Info
PostAuthor = "Chester Catalano"
PostPublishDate = "January 1, 2024"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "A Cup of Tea"
mdThisPage_WelcomeLine = "A Cup of Tea"

mdThisPage_Overview = """
   A Cup of Tea None.
"""
# SECTION 06: Content Variables
Post-Field-A = "Field A"
Post-Field-B = "Field B"

# Note: Anything below these variables will be considered the "Content" of this page

+++
