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
BreadcrumbGrandParentDir = "Reference"
BreadcrumbGrandParentPage = "Reference"
BreadcrumbParentDir = "Sanskrit-Words"
BreadcrumbParentPage = "Sanskrit Words"
BreadcrumbThisPage = "Austerity"

# SECTION 02: URL / Directory Locations
url = "/Reference/sanskrit-words/austerity"	# Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Posts-Sanskrit-Words"	   # Directory = Layouts/Posts-Sanskrit-Words
layout = "post-Sanskrit-Word"    # HTML Template = Posts-Sanskrit-Word

# SECTION 04: Post Byline Info
PostAuthor = "Chester Catalano"
PostPublishDate = "January 1, 2024"


# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "Austerity"
mdThisPage_WelcomeLine = "Austerity"

mdThisPage_Overview = """
   Absence of Malice None.
"""

# SECTION 06: Content Variables
Post_Sanskrit_Word_Text = "तप"
Post_Sanskrit_Word_Translation = "Austerity"
Post_Sanskrit_Word_Pronunciation = "tapa"
Post_Sanskrit_Word_Definition = """
Warmth, heat, pain, suffering, religious austerity, bodily mortification, penance, severe meditation, special observance
"""

Post_Previous_Sanskrit_Word = "Absence of Malice"
Post_Previous_Sanskrit_Word_URL = "../absence-of-malice"
Post_This_Sanskrit_Word = "Austerity"
Post_Next_Sanskrit_Word = "Compassion for All Beings"
Post_Next_Sanskrit_Word_URL = "../compassion-for-all-being"

# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\Reference\Sanskrit-Words\austerity.md)
