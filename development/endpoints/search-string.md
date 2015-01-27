# Get search/string

Returns matches to words in query_string from Volley tags.

## Resource URL

https://api.volley.works/search/string

## Resource Information

<table style="width:100%">
  <tr>
    <th>Response Formats </th>
    <td> JSON </td>
  </tr>
  <tr>
    <th> Requires authentication? </th>
    <td> Yes </td>
  </tr>
  <tr> 
    <th> Rate Limited? </th>
    <td> No </th>
</table>

## Parameters

<table style="width:100%">
  <tr>
    <th>string_query</th>
    <td>A white-space delimited string containg words that are searched to for matches. </td>
  </tr>
</table>

## Example Request

https://api.volley.works/search/string?string_query=Looking%20for%20CEO%27s%20interested%20in%20marketing%20turtles

API response in JSON format:
```javascript
[
  {
    "tag_id": 133,
    "tag_word": "MARKETING",
    "tag_key": "MARKETING",
    "tag_category": "strategy",
    "tag_used": 0,
    "tag_active": 1
  }
]
