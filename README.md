# Marango Commerce

[![Twitter: @marangocommerce](https://img.shields.io/badge/contact-%40marangocommerce-blue.svg)](https://twitter.com/marangocommerce)
[![License](https://img.shields.io/badge/license-BSD-green.svg)](https://github.com/marangocommerce/marango/blob/master/LICENSE)

Marango distinctively infuses [Magento](https://magento.com) with [ArangoDB](https://www.arangodb.com).

> Dreaming of Magento without EAV, indexing and its resulting cumbersome overhead but instead providing lightning fast imports and performance? Stop dreaming - Marango is here to make the industrie's most flexible ecommerce solution also the industrie's most performant, and even a little more.


## System Requirements

Marango is based on Magento 2.x, because a switch to something like Marango (In its final stage) is huge enough that it should also go well together with a switch to M2. Of course, that doesn't rule out a backport to M1, but it's probably quite unlikely.


## Roadmap/Implementation Stages

1. Storage of products and their attributes in ArangoDB
    
    > Option to store in either (ArangoDB/MySQL) and sync from one to the other, so we can run performance tests on the very same instance.

2. Storage of all core data in ArangoDB

3. Compatibility layer for native SQL queries of 3rd party extensions

   > It should be considered to natively implement ArangoDB for major extensions which would greatly benefit of a performance boost - E.g. Sweet Tooth Rewards seems to have some index which we could wipe...

4. Replace the search with own ArangoDB native "Moringa Search" ([Moringa Oleifera - Malnutrition relief](https://en.wikipedia.org/wiki/Moringa_oleifera#Malnutrition_relief)) - Yes, we'll relief the malnutritioned Magento search. ^-^

5. Implement fancy and unthinkable stuff not possible or practical before.

  > Hint: Might get some good reads about neural network models.
