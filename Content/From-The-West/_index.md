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
Title = "From The East"
BreadcrumbPageLevel  = "2"
BreadcrumbHomePage   = "Home"
BreadcrumbThisPage   = "From The West"

# Next item needs to match JSONDataSubjectRoot value
mdMeta_ThisPage_Name = "From-The-West"

# SECTION 02: URL / Directory Locations
url = "/From-The-West"

# SECTION 03: Layout Page Directory and Layout Name
type = "Pages-Shared-Layouts"   # Directory = Layouts/Pages-Shared-Layouts
layout = "Page-Series-TOC"      # HTML Template = Page-Series-TOC.html

# SECTION 04: Post Byline Info
author = "Lorenzo Verdi"
date = "2023-12-25"
publishdate = "2023-12-25"

# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "From The West"
mdThisPage_WelcomeLine = "From The West"

mdThisPage_Overview = """
  Here we present selections from the wisdom of the West.
"""

# SECTION 06: Additional Information


# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\From-The-West\ _index.md)