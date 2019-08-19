### orika
---
https://github.com/orika-mapper/orika

```java
// core/src/main/java/ma/glasnost/orika/Filter.java

public interface Filter<A, B> extends MappedTypePair<A, B> {
  boolean appliesTo(Property source, Property destination);
  
  boolean filtersSource();
  
  boolean filtersDestination();
  
  <S extends A, B extends B> boolean shouldMap(Type<S> sourceType, String sourceName, S source, Type<D> destType, string destName,
    D dest, MappingContext mappingContext);
  
}



```

```
```

```
```


