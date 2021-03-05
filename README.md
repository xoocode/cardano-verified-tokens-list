# cardano-verified-tokens-list

1) Fork repository
2) Add token object to `list.json`
3) Add logo to `\logo` folder with the next pattern `policyId.name.jpg`. Image size should be 512x512px.
4) Push and create Pull Request

# token object

See [list.json](list.json) for working example

``` JS
{
  "policyId": "",  // String:: policy identifier
  "name": "",      // String:: name
  "homepage": "",     // String:: homepage 
  "mintedAt": 0,      // Int:: milliseconds since epoch
  "addedAt": 0        // Int:: milliseconds since epoch
}
```
