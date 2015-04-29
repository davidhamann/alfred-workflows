# alfred-workflows
A collection of alfredapp v2 workflows

## alfredosquery
A simple shortcut to the osquery interface (osqueryi).

**osq {query}** Make an osquery and post result to BBEdit
>`osq select * from osx_version`

**osqi** Launch osqueryi
>`osqi`

**osqt {query}** Make an osquery in a new terminal window
>`osq select * from osx_version`

For this workflow to work you need to have a working installation of [osquery](https://osquery.io) and [BBEdit](http://www.barebones.com/products/bbedit/).

Queries are automatically quoted.

## alfredleo
English/German translations; redirect to dict.leo.org

**dict {query}**
>`dict hello`
