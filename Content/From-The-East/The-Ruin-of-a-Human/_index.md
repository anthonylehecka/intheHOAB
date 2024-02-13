+++
# This is a TOML markup document as evidenced by the +++ instead of --- for YAML
# Notes for Markup files in content and rendering html in layouts
#    type is the directory to find the layout in. Example type="Pages-OneOff" means look in layouts\Pages-OneOff
#    layout is the filename in the type directory to use. type="Pages-OneOff" with a layout of "about"
#    means to use the about.html file in the layouts\Pages-OneOff. N.B. that layout DOES NOT INCLUDE .html
#
# Notes for assigning front matter variables in TOML
#    variablename = "some string"

# SECTION 00: Configuration
draft = false
debugpage = true

# SECTION 01: Meta Data
Title = "The Ruin of a Human"
BreadcrumbPageLevel = "3"
BreadcrumbHomePage  = "Home"
BreadcrumbParentDir = "From-The-East"
BreadcrumbParentPage = "From The East"
BreadcrumbThisPage = "The Ruin of a Human"

# Next item needs to match JSONDataSubjectRoot value
mdMeta_ThisPage_Name = "The-Ruin-of-a-Human"

# SECTION 02: URL / Directory Locations
url = "/From-The-East/The-Ruin-of-a-Human/"

# SECTION 03: Layout Page Directory and Layout Name
type = "Pages-Unique-Layouts"            # Directory = Layouts/Pages-Unique-Layouts
layout = "Page-FTE-The-Ruin-of-a-Human"  # HTML Template = Page-The-Godly-Qualities.html

# SECTION 04: Post Byline Info
author = "Lorenzo Verdi"
date = "2023-12-25"
publishdate = "2023-12-25"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "The Ruin of a Human"
mdThisPage_WelcomeLine = "The Ruin of a Human"

mdThisPage_Overview = """
   TROFH None.
"""

# SECTION 06: Additional Information


# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\From-The-East\The-Ruin-of-a-Human\ _index.md)