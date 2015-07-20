---
layout: page
subheadline: "Configuration"
title: "Comparison of Java apps configuration options"
teaser: ""
header: no
image:
    thumb:  typewriter_thumb.jpg
    homepage: homepage_typewriter.jpg
categories:
    - soa
tags:
    - soa
    - configuration
comments: true
show_meta: false
---

### Contenders
* [cfg4j](http://www.cfg4j.org) - fairly young project, targeting distributed apps. Supports modern configuration stores like Consul
and git repositories. Offers interface binding and strongly-typed configuration properties.

* [Commons Configuration](https://commons.apache.org/proper/commons-configuration/) - old and well-known configuration library for Java.
Focused on reading from local files.

### Feature comparison

| Feature | cfg4j | commons configuration |
| --- | --- | --- |
| website | [cfg4j.org](http://www.cfg4j.org) | [commons.apache.org](https://commons.apache.org/proper/commons-configuration/) |
| license | Apache 2.0 | Apache 2.0 |
| version used | 3.3.2 | 2.0 beta 1 | 
| supported configuration stores | Consul, Git repository, Files, Classpath | JDBC, Files |
| supported file formats | yaml, properties  | properties, xml, ini, openstep |
| supported data types | BigDecimal, BigInteger, URI, URL, File, Class, Enum, Number, String, most Collection interfaces and classes, most Map interfaces and classes, primitive types, boxed types, arrays | BigDecimal, BigInteger, String, primitive types, boxes types |
| accessing configuration | single properties, interface binding | single properties |
| configuration reload | periodical, manual | no |
| caching | yes | yes |
| merge multiple sources | yes | yes |
