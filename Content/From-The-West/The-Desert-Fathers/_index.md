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
Title = "The Desert Fathers"
BreadcrumbPageLevel = "3"
BreadcrumbHomePage  = "Home"
BreadcrumbParentDir = "From-The-West"
BreadcrumbParentPage = "From The West"
BreadcrumbThisPage = "The Desert Fathers"

# Next item needs to match JSONDataSubjectRoot value
mdMeta_ThisPage_Name = "The-Desert-Fathers"

# SECTION 02: URL / Directory Locations
url = "/From-The-West/The-Desert-Fathers/"

# SECTION 03: Layout Page Directory and Layout Name
type = "Pages-Unique-Layouts"            # Directory = Layouts/Pages-Unique-Layouts
layout = "Page-FTW-The-Desert-Fathers"   # HTML Template = Page-The-Desert-Fathers.html

# SECTION 04: Post Byline Info
author = "Lorenzo Verdi"
date = "2023-12-25"
publishdate = "2023-12-25"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "The Desert Fathers"
mdThisPage_WelcomeLine = "The Fathers"

mdThisPage_Overview = """
   The Desert Fathers None.
"""

# SECTION 06: Additional Information


# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\From-The-West\The-Desert-Fathers\ _index.md)