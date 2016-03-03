This is an attempt to break the problem down into a series of design decisions where we can test how much agreement there is on each.

The current breakdown is probably not right and certainly not complete. The summary of status is probably wrong in many cases. Please improve.

All references to _round-tripping_ in the design issues are subject to the caveat that our aims place inverting the mapping back to RDF as non-requirement, just an added bonus. However, where round-tripping breaks that does mean the mapping is ambiguous and that might impact some applications even when full inversion isn't involved.

  * API Design Issues
    * [API result wrapper](DI_API_wrapper.md)
    * [JSONP support](DI_JSONP.md)
    * [Communicating Mapping and context](DI_mapping.md)
    * [Specifying the mapping](DI_mapping_spec.md)
  * JSON format issues
    * [Simple resource description](DI_simple_resource.md)
    * [Property naming](DI_property_naming.md)
    * [bNodes - single reference](DI_bnodes_singeref.md)
    * [Resource references](DI_resource_ref.md)
    * [Multi-valued properties](DI_multivalued_props.md)
    * [List-valued properties](DI_listvalued_props.md)
    * [Language tagged literals](DI_langtagged_literals.md)
    * [Typed literals - XSD types](DI_typed_literals_xsd.md)
    * [Typed literals - others](DI_typed_literals_other.md)
    * [Nesting resource references](DI_nesting_resource_refs.md)
    * [rdf:type shortcut](DI_type_shortcut.md)
    * [bNodes - graphs](DI_bnodes_graph.md)
    * [Named graphs?](DI_named_graphs.md)