# LAI-Mengyi_TP
PainterPalette Knowledge Graph Project
# Installing and Starting the PainterPalette Application

# Prerequisites

Apache Jena Fuseki 5.6.0: Download and extract the compressed package corresponding to your operating system from the official website. This guide assumes the directory name is apache-jena-fuseki-5.6.0.

RDF Dataset: PainterPalette_csv.ttl, generated from a CSV file, is provided. It contains the ontology (RDFS) and data in Turtle format.

A web browser for serving the HTML file locally.

# Starting the Fuseki Server

Open a terminal and navigate to the Fuseki main directory (apache-jena-fuseki-5.6.0)

Run fuseki-server.bat

# Installing Data in Fuseki

Once the server is running, you can access http://localhost:3030/ to upload PainterPalette_csv.ttl using the Fuseki management interface.

# Starting the Web Interface

Ensure the Fuseki server is running and the dataset is loaded.

Open the paintergraph.html file in VS Code. You can run paintergraph.html locally using the Live Server plugin.
