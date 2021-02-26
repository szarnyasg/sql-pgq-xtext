# SQL/PGQ Xtext grammar

## Getting started

* Grab the **Eclipse IDE for Java and DSL Developers** package from <https://www.eclipse.org/downloads/packages/>, decompress and start Eclipse.
* Import the projects.
* Select the `org.ldbcouncil.pgq/src/org/ldbcouncil/pgq/GenerateSqlPgq.mwe2` file, right click and select **Run As** | **MWE2 workflow**.
* Right click the `org.ldbcouncil.pgq` project and select **Run As** | **Eclipse Application**.

## Troubleshooting

You might encounter a warning upon launch:

* java.xml.bind 
  * Missing Constraint: Import-Package: javax.xml.stream; version="0.0.0"

To fix it, go to **Help** | **Install software**, add the repository <http://download.eclipse.org/tools/orbit/downloads/drops/R20190226160451/repository>, and install Java XML Stream, then restart Eclipse ([source](https://stackoverflow.com/questions/18420283/launching-plugin-fails-missing-constraint-javax-xml-bind)).
