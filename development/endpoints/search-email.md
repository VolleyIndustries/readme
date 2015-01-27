# GET search/email

Returns the number of Volley memebrs who have email_query as a contact.

## Resource URL

https://api.volley.works/search/email

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
    <th>email_query</th>
    <td>The email of Contact to be searched.</td>
  </tr>
</table>

## Example Request

https://api.volley.works/search/email?email_query=shervin@volley.works

API response:
```javascript
{
"count": 5
}
```


