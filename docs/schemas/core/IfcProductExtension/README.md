IfcProductExtension
===================

The _IfcProductExtension_ further specialises the concepts of a (physical) product, i.e. a component likely to have a shape and a placement within the project context. The product information is provided for individual product occurrences as subtypes of _IfcProduct_, and for common specific product types as subtypes of _IfcTypeProduct_. Both definitions are rooted in supertypes provided within the _IfcKernel_. Basis concepts, introduced within the _IfcProductExtension_, are:

* the spatial project structure,
* the element,
* the grid,
* the port, and 
* the annotation.

The spatial project structure defines

* the site, 
* the facility (building, bridge, marine, railway, road),
* the facility part (building storey and parts of the above), and 
* the space 

and its decomposition structure. In addition the concepts of system and zone are introduced within the _IfcProductExtension_. Relationships between the spatial structure and the elements are defined, such as spatial containment and space boundaries.

An element is assigned to the spatial project structure and may refer by its placement to a grid. Basic types of elements, which are introduced are

* building element
* opening element
* furnishing element
* distribution element (including heating, ventilation, air conditioning, electrical and equipment elements)
* transportation element

The other concepts introduced are

* a grid, providing a constraint placement for elements, 
* an alignment, providing a linear positioning element to position geographic and civil elements,<br>
  with project geo referencing provided by means of entities from the IfcRepresentationResource domain,
* an annotation to capture any additional annotations to a building model or plan (such as explanatory text, dimensioning, etc.), and
* a port, providing connectivity between elements.
