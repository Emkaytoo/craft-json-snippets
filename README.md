# Craft .json snippets Atom package

Snippets for [Atom](https://atom.io/) that help you quickly generate `.json` models for [CraftCMS](http://craftcms.com). They work really well with the [CMS-Generator plugin](http://github.com/Pennebaker/craftcms-generator).

## Install:
You can install this package through the Atom settings menu, or via the command line:

    apm install craft-json-snippets

## Usage:
Install the package and type the name of a snippet. By default, use `tab` to expand.

## Snippets:

### Initializing
Use `CraftJsonInit` in a blank document to begin creating a content model.

### Fields

* `CraftAssets` - Creates a blank **Assets** field.  
* `CraftCategories` - Creates a blank **Categories** field.  
* `CraftCheckboxes` - Creates a blank **Checkboxes** field.  
* `CraftColor`Creates a blank **Color** field.  
* `CraftDate` - Creates a blank **Date** field.  
* `CraftDropdown` - Creates a blank **Dropdown** field.  
* `CraftEntries` - Creates a blank **Entries** field.  
* `CraftLightswitch` - Creates a blank **Lightswitch** field.  
* `CraftMatrix` - Creates an *incomplete* blank **Matrix** field.  
  * `CraftMatrixBlock` - Creates a new blocktype for use in the "blockTypes" array in a Matrix.  
  * `CraftMatrixField` - Creates a new field for use in the "fields" array of a Matrix blocktype.  
* `CraftMultiselect` - Creates a blank **Multiselect** field.  
* `CraftNumber` - Creates a blank **Number** field.  
* `CraftPlainText` - Creates a blank **PlainText** field.  
* `CraftPositionSelect` - Creates a blank **PositionSelect** field.  
* `CraftRadioButtons` - Creates a blank **RadioButtons** field.  
* `CraftRichText` - Creates a blank **RichText** field.  
* `CraftTable`Creates an *incomplete* blank **Table** field.  
  * `CraftTableColumn` - Creates a blank **Columns** subfield for use in a table.  
  * `CraftTableRow` - Creates a blank **Row** subfield for use in a table.  
* `CraftTags`Creates a blank **Tags** field.  
* `CraftUsers` - Creates a blank **Users** field.  
* `CraftFieldNotes` - Creates a blank **FieldNotes** field.  

### Sections
* `CraftHomePage` - Creates a blank **Homepage** section.  
* `CraftSingle` - Creates a blank **Single** section.  
* `CraftChannel` - Creates a blank **Channel** section.  
* `CraftStructure` - Creates a blank **Structure** section.  

### Entry Types
* `CraftEntrySingle` - Creates a blank **Single** entryType.  
* `CraftEntryChannel` - Creates a blank entryType used for both **Channels and Structures**.  

### Asset Sources
* `CraftSourceLocal` - Creates a blank **Local** asset source.  
* `CraftSourceS3` - Creates a blank **Amazon S3** asset source.  
* `CraftSourceGoogleCloud` - Creates a blank **Google Cloud** asset source.  
* `CraftSourceRackspace` - Creates a blank **Rackspace** asset source.  
