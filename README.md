***MODELS***
# Annotations
- @JsonIgnoreProperties - to prevent specified fields from being serialized or deserialized
- @Enumerated - value should be converted into a string in the database

***SERVICES***
- (JDBC template) a class that contains methods that gives you the ability to interact with database that use SQL
# Annotations

- @Service - class or specifi a class as a service provider
- @Transactional - describes a transaction on a an individual class
- @Autowired - to resolve and inject collaborating beans into other beans which can be used on properties, setters, and constructors

A query is used to extract data from the database, if you need to fetch data then you must write a query in your desired format..

***CONTROLLERS***
# Annotations
- @RestContollers - Types that carry this annotation are treated as controllers where @RequestMapping methods assume @ResponseBody semantics by default
- @CrossOrigin - for permitting cross-origin requests on specific handler classes and/or handler methods
- @PathVariable - which indicates that a method parameter should be bound to a URI template variable




