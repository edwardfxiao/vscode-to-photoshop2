# vscode-to-photoshop2 README

This extension is a fork of [vscode-to-photoshop](https://github.com/bialikover/vscode-to-photoshop)


### [vscode-to-photoshop](https://github.com/bialikover/vscode-to-photoshop):

```js
// my-phoroshop-javascript.js on macOS

var currentScriptFile = new File($.fileName);
alert(currentScriptFile.toString());

// ~/.vscode/extensions/bialikover.vscode-to-photoshop-0.0.3/out/src/tmp_file.jsx
```

### [vscode-to-photoshop2](https://github.com/edwardfxiao/vscode-to-photoshop2):
```js
// my-phoroshop-javascript.js on macOS

var JSON = {
	 parse: function (str) {
	    return eval('(' + str + ')');
	  }
	};
}
var actualFilename = "";
try {
  var option = JSON.parse(arguments[0]);
  actualFilename = option.filename;
}
catch(e){}
alert(actualFilename);
// ~/my-actual-file-path/my-actual-file.jsx
```



What this new extension does is to provide a actual file path as [this issue states](https://github.com/bialikover/vscode-to-photoshop/issues/3) states.
