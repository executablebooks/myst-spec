Basic node with required node children

- __children*__: _array_ ({ref}`node`) 
- __type*__: _string_ - identifier for node variant - See {ref}`node`
- __data__: _object_ - information associated by the ecosystem with the node; never specified by mdast - See {ref}`node`
- __position__: _object_ ({ref}`position`) - location of node in source file; must not be present for generated nodes - See {ref}`node`