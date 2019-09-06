POM OMERO client (deprecated)
=============================

As of OMERO 5.5.0, this parent POM is deprecated. To write a Java client, there
are two options:

-   either declare `org.openmicroscopy:omero-gateway` as a dependency in your
    POM. You will need to declar
    the [OME Artifactory](artifacts.openmicroscopy.org/artifactory/maven) and the
    [Unidata Releases](https://artifacts.unidata.ucar.edu/content/repositories/unidata-releases) in the `repositories` section. See
    https://github.com/ome/minimal-omero-client/ for an example

-   if you want to inherit a parent POM and/or write a client compatible with the Scijava ecosystem (ImageJ), you can inherit
    https://github.com/scijava/pom-scijava
