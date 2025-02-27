(rr-rdm-metadata)=
# Documentation and Metadata

Having data available is of no use if it cannot be understood.
For example, a table of numbers is useless if there are no headings that describe what the columns/rows contain.
Therefore you should ensure that open datasets include documentation.

## Documentation

Documentation provides context for your work. 
It allows your collaborators, colleagues and future you to understand what has been done and why.
Data documentation can be done on different levels. 
All documentation accompanying data should be written in clear, plain language. 
Documentation allows data users have sufficient information to understand the source, strengths, weaknesses, and analytical limitations of the data so that they can make informed decisions when using it. 

## Metadata

Metadata is information about the data, descriptors that facilitate cataloguing data and data discovery. 
Often, metadata are intended for machine reading.
When data is submitted to a trusted data repository, the machine-readable metadata is generated by the repository. 
If the data is not in a repository a text file with machine-readable metadata can be added as part of the documentation.

- The type of research and the nature of the data also influence what kind of documentation is necessary. 
- The level of documentation and metadata [{term}`def<Metadata>`] will vary according to the project, and the range of people the data needs to be understood by.
- Examples of documentation may include items like [data dictionaries](https://help.osf.io/hc/en-us/articles/360019739054-How-to-Make-a-Data-Dictionary) or codebooks, protocols, logbooks or lab journals, README files, research logs, analysis syntax, algorithms and code comments.  
- Variables should be defined and explained using data dictionaries or codebooks.
- Data should be stored in logical and hierarchical folder structures, with a README file used to describe the structure.
The README file is helpful for others and will also help you find your data in the future {cite:ps}`Fuchs2018documentation`.
See the [README template from Cornell](https://cornell.app.box.com/v/ReadmeTemplate) for an example.
- It is best practice to use recognised community metadata standards to make it easier for datasets to be combined.

(rr-rdm-metadata-standards)=
### Community Standards - Metadata

The use of community-defined standards for metadata is vital for reproducible research and allows for the comparison of heterogeneous data from multiple sources, domains and disciplines.
Metadata standards are discipline-specific.
For example, for brain data, the [Brain Imaging Data Structure](https://doi.org/10.25504/FAIRsharing.rd1j6t) is the standard to use.
Not every discipline may use metadata standards, however.
You can see if your discipline uses metadata standards through [FAIRsharing](https://fairsharing.org/), a resource to identify and cite the metadata or identifier schemas, databases or repositories that exist for your data and discipline. 
There are also situations when researchers make use of more general metadata standards, for example when they use a generic archive to store their data they have to adhere to the metadata standards of the archive. 
In this case, a text file with discipline-specific metadata can be added as part of the documentation.
