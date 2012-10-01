console.io-client is package required to connect your node.js applications with
[console.io](https://github.com/TellagoDevLabs/node-console.io)

## Adding console.io to your node.js app

You will find that integrating console.io to your node.js apps is ridiculously
simple.

### Example

```js
	ncc.connect({
			endpoint: "http://localhost:8080/console.io-log",
			name: "marketplace"
		}, function(err, result){
	});
```

### Installation

```
	npm install console.io-client
```

### Usage

Add this once in every node.js process:

```js
	ncc.connect(options, callback);
```

### Options

* `endpoint`: url to the dashboard.
* `name`: unique name of this particular node.js process.
* `disableExec`: disable the remote execution of code.

### Contributors
[Silvio Massari](https://github.com/silviom)
[Gustavo Machado](https://github.com/machadogj)

## License 

[MIT License](http://www.opensource.org/licenses/mit-license.php)