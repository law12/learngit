##README##
**ID attribute values**

*photo*

Applied to a DIV tag. A representation of a single photo with associated data.

*photos*

Applied to a DIV tag. A representation of many photos.

*queries*

Applied to a DIV tag. Valid queries are DIV.concSearch and DIV.dataSearch.

 

**Class attribute values**

*all*

Applied to a UL tag. A list representation. When a descendant of DIV.photos (/) shows all photos in collection. When a descendant of discrete queries, this element shows only those photos.

*birdlist (optional)*

Applied to a UL tag. A list representation of all birds in the collection. This element is a descendant of DIV.leftSide.

*concSearch*

Applied to a DIV tag. Used with the FORM tag for deploying a concatenated search with CLASS.photo-search.

*dataSearch*

Applied to a DIV tag. Used with the FORM tag for deploying a data search with element CLASS.photo-search.

*date*

Applied to a SPAN tag. Denotes the date the photo was taken.

*desc*

Applied to a SPAN tag. Denotes optional text.

*location*

Applied to a SPAN tag. Denotes the location where photo was taken.

*photo*

Applied to a SPAN tag. As a descendant of DIV.photos, shows a representation of photos in a set. As a descendant of DIV.photo, shows one photo and associated data.


*photo-search*

Applied to FORM tag. Used with DIV.concSearch and DIV.dataSearch.  



**NAME attribute values**

*birdname*

Applied to a FORM tag. Denotes the name of the bird associated with a photograph resource.

*date*

Applied to a SPAN tag and FORM tag. Denotes the date the photo was taken.

*desc*

Applied to a FORM tag. Refers to an optional textual description of a photo resource.

*family*

Applied to a FORM tag. Denotes a taxonomic value.

*hierarchies*

Applied to a SPAN tag. The list represents taxonomic metadata associated with an image.


*location*

Applied to a FORM tag. Denotes the location where a photograph was shot.


*order*

Applied to a FORM tag. Denotes a taxonomic value.


*photoname*

Applied to a FORM tag. Denotes the name of a photographic resource.

*photo-text*

Applied to a SPAN tag. Used to specify the title associated with a photo.

*q*

Applied to a FORM tag. Denotes the name of a query. Used with DIV.concSearch and DIV.dataSearch.  

species*

Applied to a FORM tag. Denotes a taxonomic value.


**REL attribute values**

*concSearch*

Applied to an A tag. A reference to a photo-search FORM for queries of multiple folders.

*dataSearch*

Applied to an A tag. A reference to a photo-search FORM for queries by tag data.

*photos-all*

Applied to an A tag. A reference to the starting URI of the program.

*rsrcMod*

Applied to an A tag. A reference to the FORM for adding and modifying resources.

