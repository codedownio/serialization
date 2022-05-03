Results that are within 30% of the best result are displayed in **bold**.

#### deserialization (time)/BinTree Direction (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| **persist**   |     **1.1** |
| **store**     |     **1.3** |
| cereal    |     1.5 |
| serialise |     6.9 |
| binary    |     7.5 |
| aeson     |    62.8 |

#### deserialization (time)/BinTree Int (best first)

| package | performance |
| ---| ---|
| **store**     |     **1.0** |
| **persist**   |     **1.0** |
| **flat**      |     **1.1** |
| cereal    |     2.1 |
| serialise |     4.1 |
| binary    |     4.5 |
| aeson     |    56.7 |

#### deserialization (time)/Iris (best first)

| package | performance |
| ---| ---|
| **store**     |     **1.0** |
| **persist**   |     **1.0** |
| **flat**      |     **1.2** |
| serialise |     2.5 |
| cereal    |     3.3 |
| binary    |     8.0 |
| aeson     |    30.7 |

#### deserialization (time)/[Direction] (best first)

| package | performance |
| ---| ---|
| **persist**   |     **1.0** |
| **flat**      |     **1.1** |
| **cereal**    |     **1.2** |
| **store**     |     **1.2** |
| binary    |     3.0 |
| serialise |     3.2 |
| aeson     |    10.2 |

#### serialization (time)/BinTree Direction (best first)

| package | performance |
| ---| ---|
| **persist**   |     **1.0** |
| **store**     |     **1.1** |
| flat      |     1.3 |
| cereal    |     8.0 |
| binary    |    13.6 |
| serialise |    20.2 |
| aeson     |   109.2 |

#### serialization (time)/BinTree Int (best first)

| package | performance |
| ---| ---|
| **store**     |     **1.0** |
| **persist**   |     **1.0** |
| **flat**      |     **1.0** |
| cereal    |    13.4 |
| binary    |    14.6 |
| serialise |    18.2 |
| aeson     |   127.1 |

#### serialization (time)/Iris (best first)

| package | performance |
| ---| ---|
| **store**     |     **1.0** |
| persist   |     1.3 |
| flat      |     2.4 |
| cereal    |     4.6 |
| serialise |     6.6 |
| binary    |    24.7 |
| aeson     |    74.4 |

#### serialization (time)/[Direction] (best first)

| package | performance |
| ---| ---|
| **persist**   |     **1.0** |
| **store**     |     **1.1** |
| **flat**      |     **1.2** |
| cereal    |     2.4 |
| binary    |     2.8 |
| serialise |     5.4 |
| aeson     |     6.6 |

#### size (bytes)/BinTree Direction (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| binary    |     5.5 |
| cereal    |     5.5 |
| persist   |     5.5 |
| store     |     5.5 |
| serialise |    10.9 |
| aeson     |   112.4 |

#### size (bytes)/BinTree Int (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| serialise |     4.2 |
| binary    |     8.0 |
| cereal    |     8.0 |
| persist   |     8.0 |
| store     |     8.0 |
| aeson     |    45.7 |

#### size (bytes)/Iris (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| **cereal**    |     **1.0** |
| **persist**   |     **1.0** |
| **store**     |     **1.0** |
| **serialise** |     **1.2** |
| aeson     |     2.9 |
| binary    |     3.1 |

#### size (bytes)/[Direction] (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| binary    |     2.4 |
| cereal    |     2.4 |
| persist   |     2.4 |
| store     |     2.4 |
| serialise |     4.7 |
| aeson     |    18.3 |

#### transfer [10 MBits] (time)/BinTree Direction (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| persist   |     4.6 |
| store     |     4.6 |
| cereal    |     5.0 |
| binary    |     6.0 |
| serialise |    10.6 |
| aeson     |   104.1 |

#### transfer [10 MBits] (time)/BinTree Int (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| serialise |     4.4 |
| store     |     7.3 |
| persist   |     7.3 |
| cereal    |     7.6 |
| binary    |     7.8 |
| aeson     |    47.6 |

#### transfer [10 MBits] (time)/Iris (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| **store**     |     **1.0** |
| **persist**   |     **1.0** |
| **cereal**    |     **1.0** |
| **serialise** |     **1.2** |
| binary    |     3.2 |
| aeson     |     3.2 |

#### transfer [10 MBits] (time)/[Direction] (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| persist   |     2.1 |
| store     |     2.1 |
| cereal    |     2.1 |
| binary    |     2.4 |
| serialise |     4.4 |
| aeson     |    16.4 |

#### transfer [100 MBits] (time)/BinTree Direction (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| persist   |     2.4 |
| store     |     2.4 |
| cereal    |     3.6 |
| binary    |     7.5 |
| serialise |     9.9 |
| aeson     |    81.9 |

#### transfer [100 MBits] (time)/BinTree Int (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| store     |     4.4 |
| persist   |     4.4 |
| serialise |     5.4 |
| cereal    |     6.0 |
| binary    |     7.0 |
| aeson     |    56.1 |

#### transfer [100 MBits] (time)/Iris (best first)

| package | performance |
| ---| ---|
| **store**     |     **1.0** |
| **persist**   |     **1.0** |
| **flat**      |     **1.0** |
| **cereal**    |     **1.2** |
| serialise |     1.4 |
| binary    |     3.6 |
| aeson     |     5.4 |

#### transfer [100 MBits] (time)/[Direction] (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| persist   |     1.3 |
| store     |     1.4 |
| cereal    |     1.6 |
| binary    |     2.5 |
| serialise |     3.6 |
| aeson     |    11.3 |

#### transfer [1000 MBits] (time)/BinTree Direction (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| **persist**   |     **1.2** |
| **store**     |     **1.3** |
| cereal    |     3.0 |
| binary    |     8.2 |
| serialise |     9.5 |
| aeson     |    70.5 |

#### transfer [1000 MBits] (time)/BinTree Int (best first)

| package | performance |
| ---| ---|
| **flat**      |     **1.0** |
| store     |     1.6 |
| persist   |     1.6 |
| cereal    |     4.4 |
| binary    |     6.3 |
| serialise |     6.3 |
| aeson     |    64.4 |

#### transfer [1000 MBits] (time)/Iris (best first)

| package | performance |
| ---| ---|
| **store**     |     **1.0** |
| **persist**   |     **1.0** |
| **flat**      |     **1.2** |
| serialise |     2.1 |
| cereal    |     2.1 |
| binary    |     6.5 |
| aeson     |    18.3 |

#### transfer [1000 MBits] (time)/[Direction] (best first)

| package | performance |
| ---| ---|
| **persist**   |     **1.0** |
| **flat**      |     **1.1** |
| **store**     |     **1.2** |
| cereal    |     1.4 |
| binary    |     2.7 |
| serialise |     3.5 |
| aeson     |     9.3 |

