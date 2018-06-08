

## JavaScript Snippet Pack for Visual Studio Code

## DOM

https://github.com/xiangjun9988/vscode-javascript-snippet-pack

### [ae] addEventListener

```javascript
${1:document}.addEventListener('${2:load}', function(e) {
	${3:// body}
});
```

### [ac] appendChild

```javascript
${1:document}.appendChild(${2:elem});
```

### [rc] removeChild

```javascript
${1:document}.removeChild(${2:elem});
```

### [cel] createElement

```javascript
${1:document}.createElement(${2:elem});
```

### [cdf] createDocumentFragment

```javascript
${1:document}.createDocumentFragment();
```

### [ca] classList.add

```javascript
${1:document}.classList.add('${2:class}');
```

### [ct] classList.toggle

```javascript
${1:document}.classList.toggle('${2:class}');
```

### [cr] classList.remove

```javascript
${1:document}.classList.remove('${2:class}');
```

### [gi] getElementById

```javascript
${1:document}.getElementById('${2:id}');
```

### [gc] getElementsByClassName

```javascript
${1:document}.getElementsByClassName('${2:class}');
```

### [gt] getElementsByTagName

```javascript
${1:document}.getElementsByTagName('${2:tag}');
```

### [ga] getAttribute

```javascript
${1:document}.getAttribute('${2:attr}');
```

### [sa] setAttribute

```javascript
${1:document}.setAttribute('${2:attr}', ${3:value});
```

### [ra] removeAttribute

```javascript
${1:document}.removeAttribute('${2:attr}');
```

### [ih] innerHTML

```javascript
${1:document}.innerHTML = '${2:elem}';
```

### [tc] textContent

```javascript
${1:document}.textContent = '${2:content}';
```

### [qs] querySelector

```javascript
${1:document}.querySelector('${2:selector}');
```

### [qsa] querySelectorAll

```javascript
${1:document}.querySelectorAll('${2:selector}');
```

## Loop

### [fe] forEach

```javascript
${1:array}.forEach(function(item) {
	${2:// body}
});
```

## Function

### [fn] function

```javascript
function ${1:methodName} (${2:arguments}) {
	${3:// body}
}
```

### [afn] anonymous function

```javascript
function(${1:arguments}) {
	${2:// body}
}
```

### [pr] prototype

```javascript
${1:object}.prototype.${2:method} = function(${3:arguments}) {
	${4:// body}
}
```

### [iife] immediately-invoked function expression

```javascript
(function(${1:window}, ${2:document}) {
	${3:// body}
})(${1:window}, ${2:document});
```

### [call] function call

```javascript
${1:method}.call(${2:context}, ${3:arguments})
```

### [apply] function apply

```javascript
${1:method}.apply(${2:context}, [${3:arguments}])
```

### [ofn] function as a property of an object

```javascript
${1:functionName}: function(${2:arguments}) {
	${3:// body}
}
```

## JSON

### [jp] JSON.parse

```javascript
JSON.parse(${1:obj});
```

### [js] JSON.stringify

```javascript
JSON.stringify(${1:obj});
```

## Timer

### [si] setInterval

```javascript
setInterval(function() {
	${0:// body}
}, ${1:1000});
```

### [st] setTimeout

```javascript
setTimeout(function() {
	${0:// body}
}, ${1:1000});
```

### [al] alert

```javascript
alert('${1:msg}');
```