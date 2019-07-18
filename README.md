# TextformatterExternalRedirect
ProcessWire TextFormatter for rewriting external links

Allows you to rewrite external links in textarea fields at rendering time,
prepending a custom url (implementation of that URL is not subject of this
module). Optionally also adds a ```target='blank'``` attribute to the links.

## Compatibility

ProcessWire 3

## Stability

Stable

## Installation

- Download the zip archive of this module and extract it to the site/templates
  directory of your ProcessWire installation
- Rename the module folder to TextformatterExternalRedirect
- Go into the backend and click "Modules" -> "Refresh"
- Find "External Link Redirect" in the list of new modules and click "Install"
- Go into the module settings, enter your target link and optionally check the
  box to open all external links in a new window
- Configure the textarea fields to use the External Link Redirector textformatter

## Config Options

The following options can be configured in the module's configuration settings:

- Link to prepend (mandatory for module to work)
- Open in new window (optional): will add ```target='_blank'``` to every link
- CSS class (optional): will append the entered class(es) if a class attribute is
  already present or add the class attribute if not

## License

This module is released under Mozilla Public Lincense. See LICENSE file for details.
