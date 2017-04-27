## Getting Started with Elasticsearch

### About Elasticsearch

Elasticsearch is a RESTful API server for storing and processing data
at large scale.

Elasticsearch can run on a single node or as a cluster of many nodes.
The Elasticsearch server scales horizontailly, meaning that as we add nodes
to our cluster, the data

### Getting Started with Elasticsearch

#### Install locally

#### Use AWS Elasticsearch Service.

AWS has a free tier offering for Elasticsearch.


### Using the RESTful API

#### Posting and Getting data

Elasticsearch API endpoints for insert/indexing (POST) and getting (GET) data are
of the format:

```
/<index>/<type>/<id>
```

This will create entries with variables "_index", "_type", "_id" with values
corresponding to the

#### Searching for data

Methods can be added to the URI to preform operations like searching.
These methods start with an underscore.

To search:

```
GET /<index>/<type>/_search
```

must - like logical AND
should - like logical OR
