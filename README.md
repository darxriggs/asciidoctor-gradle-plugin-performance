asciidoctor-gradle-plugin-performance
=====================================

```gradle run```

```
Thu Oct 03 15:07:30 CEST 2013 create Asciidoctor object - before
org.asciidoctor.internal.JRubyAsciidoctor@1c8cd5c
Thu Oct 03 15:07:37 CEST 2013 create Asciidoctor object - after
```
Gradle 1.7 and 1.8 - 7 seconds execution time


```gradle asciidoctorPerformance```

```
Thu Oct 03 15:15:24 CEST 2013 asciidoctor: apply plugin - begin
Thu Oct 03 15:15:24 CEST 2013 asciidoctor: apply plugin - end
Thu Oct 03 15:15:24 CEST 2013 asciidoctor: execute task - begin
Thu Oct 03 15:15:24 CEST 2013 asciidoctor: execute task - end
```

Gradle 1.7 and 1.8 - 0 seconds execution time
