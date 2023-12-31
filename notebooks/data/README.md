# Demo Notebooks for Data Ingestion



---
## 1.0 - Geographic Index Demo

In this demo notebook, we demonstrate how to initialize a mini-database based on a query of coordinates. This will showcase how we can get a class which contains the filepaths and associated meta-data.

[Source](./geographic_index_demo.ipynb)


---
## 2.0 - Creating Dataclasses

This demo notebook demonstrates how we can create a dataclass given an image and the associated metadata. The dataclass contains all of the relevant information necessary to load the file when needed as well as the relevant metadata.

[Source](./creating_dataclasses.ipynb)

---
## 3.0 - Query to DataClass Pipeline

In this short demo notebook, we showcase a simple query followed by constructing a dataclass.

[Source](./query_2_dataclass.ipynb)

---
## 4.0 Full Ingeston from CopernicusEMS and Sentinel-2

This demo shows how to query Copernicus EMS to download floodmaps, how later we could visualize those and query the closest in time Sentinel-2 images and display them using interactive folium maps.

[Source](https://github.com/spaceml-org/ml4floods/blob/main/notebooks/data/full_data_ingest.ipynb)
