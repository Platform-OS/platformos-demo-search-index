[WORK IN PROGRESS]
# **Search Index Demo**

## index definitions

based on elasticsearch

https://www.elastic.co/guide/en/elasticsearch/reference/5.6/mapping.html

### types:
- keyword - it is what it is. meaning it's not analyzed during document indexing. useful for sorting
- text - gets analyzed [tokenized] during indexing
  - analyzer: text gets analyzed using selected analyzed, useful when different languages required, german, arabic 
- object - inner document
- date
- integer
- boolean
- float

