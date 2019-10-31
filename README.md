This is a list of public p2p and API endpoints for the WORBLI blockchain. It is maintained by the WORBLI Foundation.

If you wish to add your node to the list, edit endpoints.json and add a new JSON object with your node, then open a pull request. The format is:
```
{
	"name": "",
	"p2pEndpoint": "",
	"apiEndpoint": "",
	"history": ""
}
```

Each of the above keys should be present in the JSON object you add, but the ones that are not relevant can be empty. For example, if you only have an API endpoint, you can leave the p2pEndpoint value empty. The "history" key refers to the API endpoint and indicates whether it is running a history plugin or not.

UPDATE: testnet-endpoints.json has been added to list the public endpoints for the WORBLI testnet.
