---
layout: post
title: “Embedded error” when using maven jaxws:wsgen
---

### Problem:
When trying to use maven jaxws plugin for generating wsdl from annotated Java classes, the below error occurs during build.
```
“Embedded error: com/sun/mirror/apt/AnnotationProcessorFactory”
```
### Solution:
Change the plugin version of jaxws-maven-plugin  from 1.10 to 1.11.