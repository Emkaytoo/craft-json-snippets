# Craft .json snippets Atom package

Snippets for [Atom](https://atom.io/) that help you quickly generate `.json` models for [CraftCMS](http://craftcms.com). They work really well with the [Architect plugin](http://github.com/Pennebaker/craftcms-thearchitect).

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
* `CraftFieldCategories` - Creates a blank **Categories** field.  
* `CraftCheckboxes` - Creates a blank **Checkboxes** field.  
* `CraftColor`Creates a blank **Color** field.  
* `CraftDate` - Creates a blank **Date** field.  
* `CraftDropdown` - Creates a blank **Dropdown** field.  
* `CraftEntries` - Creates a blank **Entries** field.  
* `CraftLightswitch` - Creates a blank **Lightswitch** field.
* `CraftLinkIt` - Creates a blank **[FruitLinkIt](https://github.com/fruitstudios/LinkIt)** field.  
* `CraftMatrix` - Creates an *incomplete* blank **Matrix** field.  
  * `CraftMatrixBlock` - Creates a new blocktype for use in the "blockTypes" array in a Matrix.  
  * `CraftMatrixAssets` - Creates a new **Assets** field within a Matrix.  
  * `CraftMatrixCategories` - Creates a new **Categories** field within a Matrix.  
  * `CraftMatrixCheckboxes` - Creates a new **Checkboxes** field within a Matrix.  
  * `CraftMatrixColor` - Creates a new **Color** field within a Matrix.  
  * `CraftMatrixDate` - Creates a new **Date** field within a Matrix.  
  * `CraftMatrixDropdown` - Creates a new **Dropdown** field within a Matrix.  
  * `CraftMatrixEntries` - Creates a new **Entries** field within a Matrix.  
  * `CraftMatrixLightswitch` - Creates a new **Lightswitch** field within a Matrix.  
  * `CraftMatrixLinkIt` - Creates a blank **[FruitLinkIt](https://github.com/fruitstudios/LinkIt)** field within a Matrix.   
  * `CraftMatrixMultiselect` - Creates a new **Multiselect** field within a Matrix.  
  * `CraftMatrixNumber` - Creates a new **Number** field within a Matrix.  
  * `CraftMatrixPlainText` - Creates a new **PlainText** field within a Matrix.  
  * `CraftMatrixPositionSelect` - Creates a new **PositionSelect** field within a Matrix.  
  * `CraftMatrixRadioButtons` - Creates a new **RadioButtons** field within a Matrix.  
  * `CraftMatrixRichText` - Creates a new **RichText** field within a Matrix.  
  * `CraftMatrixTable` - Creates a new **Table** field within a Matrix.  
  * `CraftMatrixTags` - Creates a new **Tags** field within a Matrix.  
  * `CraftMatrixUsers` - Creates a new **Users** field within a Matrix.  
  * `CraftMatrixFieldNotes` - Creates a new **FieldNotes** field within a Matrix.  
* `CraftMultiselect` - Creates a blank **Multiselect** field.  
* `CraftNeo` - Creates an *incomplete* blank **Neo** field.  
  * `CraftNeoBlock` - Creates a new blocktype for use in the "blockTypes" array in a Neo field.  
* `CraftNumber` - Creates a blank **Number** field.  
* `CraftPlainText` - Creates a blank **PlainText** field.  
* `CraftPositionSelect` - Creates a blank **PositionSelect** field.  
* `CraftRadioButtons` - Creates a blank **RadioButtons** field.  
* `CraftRichText` - Creates a blank **RichText** field.  
* `CraftSEOmatic`- Creates a blank **[SEOmatic](https://github.com/nystudio107/seomatic)** field.  
* `CraftSuperTable`- Creates a blank **SuperTable** field.  Use the `CraftMatrix` subfields to configure SuperTable.
* `CraftTable`Creates an *incomplete* blank **Table** field.  
  * `CraftTableColumn` - Creates a blank **Columns** subfield for use in a table.  
  * `CraftTableRow` - Creates a blank **Row** subfield for use in a table.  
* `CraftTags`Creates a blank **Tags** field.  
* `CraftFieldUsers` - Creates a blank **Users** field.  
* `CraftFieldNotes` - Creates a blank **FieldNotes** field.  

### Globals
* `CraftGlobals` - Creates a new **Global set**.

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

### Categories
* `CraftCategories` - Creates a blank category model.  

### Users
* `CraftUsers` - Creates a blank **user** template.  
