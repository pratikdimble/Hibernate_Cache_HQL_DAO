# Hibernate_Cache_HQL_DAO
Hibernate also implements a cache for query resultsets that integrates closely with the second-level cache.  This is an optional feature and requires two additional physical cache regions that hold the cached query results and the timestamps when a table was last updated. This is only useful for queries that are run frequently with the same parameters. To use the query cache, you must first activate it using the hibernate.cache.use_query_cache="true" property in the configuration file. By setting this property to true, you make Hibernate create the necessary caches in memory to hold the query and identifier sets.
