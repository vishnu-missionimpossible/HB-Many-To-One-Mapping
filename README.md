# HB-Many-To-One-Mapping

Many-One Association Mapping
-----------------------------------------
It refers to relationship b/w 2 entities where mulitple instance of an entity
should be mapped with exactly one instance of
another entity.

eg: Multiple Students have joined with Single Branch

Annotation used is :: @ManytoOne(cascade = CascadeType.ALL)
