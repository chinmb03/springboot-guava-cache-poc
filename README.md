# springboot-guava-cache-poc
sample spring boot application with guava cache implementation .
Guava provides a very powerful memory based caching mechanism by an interface .
sample imports --
import com.google.common.base.MoreObjects;
import com.google.common.cache.CacheBuilder;
import com.google.common.cache.CacheLoader;
import com.google.common.cache.LoadingCache;

will be adding functions to evict cache based on -
1.eviction by size
2.eviction by weight
3.eviction by time
3.eviction by rowversion id
4.weak keys
6soft values
