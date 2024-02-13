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
BreadcrumbThisPage = "Absence of Malice"

# SECTION 02: URL / Directory Locations
url = "/Reference/Sanskrit-Words/Absence-of-Malice"	# Generate to this (public) directory

# SECTION 03: Layout Page Directory and Layout Name
type = "Posts-Sanskrit-Words"	   # Directory = Layouts/Posts-Sanskrit-Words
layout = "post-Sanskrit-Word"    # HTML Template = Posts-Sanskrit-Word

# SECTION 04: Post Byline Info
PostAuthor = "Chester Catalano"
PostPublishDate = "January 1, 2024"


# SECTION 05: Page Name / Welcome Line / Introductory Paragraph(s)
mdThisPage_Name = "Absence of Malice"
mdThisPage_WelcomeLine = "Absence of Malice"

mdThisPage_Overview = """
   Absence of Malice None.
"""

# SECTION 06: Content Variables
Post_Sanskrit_Word_Text = "अपैशुन"
Post_Sanskrit_Word_Translation = "Absence of Malice"
Post_Sanskrit_Word_Pronunciation = "apaiṡuna"
Post_Sanskrit_Word_Definition = """
Absence of, or not having the traits of (backbiting, slanderous, 
calumnious, treacherous, malignant, base, wicked; a backbiter, 
informer, betrayer)"""

Post_Previous_Sanskrit_Word = "Absence of Anger"
Post_Previous_Sanskrit_Word_URL = "../Absence-of-Anger"
Post_This_Sanskrit_Word = "Absence of Malice"
Post_Next_Sanskrit_Word = "Austerity"
Post_Next_Sanskrit_Word_URL = "../Austerity"

# Note: Anything below these variables will be considered the "Content" of this page

+++

I am (content\Reference\Sanskrit-Words\Absence-of-Malice.md)
