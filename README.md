# !! UNDER CONSTRUCTION !!
Please give me a fe months to make this happen :)

# [Vue][0] Controls
Basic controls that work well with [Vue.js][0]

## Thanks
1. [Vuejs.org][0]

## Installation

Node.js
```
$ npm install vue-components
```

CDN
```
<script src="//cloudflare.com/vue-components.js"></script>
```

## Components

### Application
```
<ve-application
    onfocus=""
>
</ve-application>
```

### Button
```
<ve-button
    caption="string"
    onclick="function"
    onfocus="function"
>
</ve-button>
```

### Input
```
<ve-input
    model=""
    suggest=""
    onclick=""
    onfocus=""
>
</ve-input>
```

### Label
```
<ve-label
    onclick=""
    onfocus=""
>
</ve-label>
```

### Panel
```
<ve-panel
    onclick=""
    onfocus=""
>
</ve-panel>
```

## Example
```
<!DOCTYPE html>
<html>
<head>
  <script src="//cloudflare.com/vue-components.js"></script>
</head>
<body>
  <ve-application>
    <ve-input model="textInput"></ve-input>
    <ve-label>{{textInput}}</ve-label>
  </ve-application>
</body>
</html>
```
[0]: http://vuejs.org
