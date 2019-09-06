POM OMERO client (deprecated)
=============================

As of OMERO 5.5.0, this parent POM is deprecated. To write a Java client, there
are two options:

-   either declare `org.openmicroscopy:omero-gateway` as a dependency in your
    `pom.xml` (Maven) or `build.gradle` (Gradle). You will also need to declare
    the [OME Artifactory](artifacts.openmicroscopy.org/artifactory/maven) and the
    [Unidata Releases](https://artifacts.unidata.ucar.edu/content/repositories/unidata-releases) in the `repositories` section of the file. See
    https://github.com/ome/minimal-omero-client/ for an example.

-   if you want to use a parent POM and/or write a client compatible with
    the SciJava ecosystem e.g. ImageJ, you can inherit the
    [SciJava parent POM](https://github.com/scijava/pom-scijava)
