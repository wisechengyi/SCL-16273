# Copyright 2014 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

# trivial example of "generally-useful" thrift to include in other thrift
# (to see how this is included, cd ../precipitation)

java_thrift_library(name='distance-java',
  sources=['distance.thrift'],
)

python_thrift_library(name='distance-python',
  sources=['distance.thrift'],
)

python_thrift_library(name='unexported-distance-python',
  sources=['unexported_distance.thrift'],
)
