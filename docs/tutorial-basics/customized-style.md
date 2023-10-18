---
sidebar_position: 2
---

# How to Customize Style

Customize the editor's UI style to match your application's requirements.

## Customize Toolbar Style
```javascript
const toolbarClass: any = {
  container: {
    backgroundColor: "red"
  },
  primaryToolbar: {
    justifyContent: "center"
  }
}

return (
    <DocumentEditor 
        toolbarClass={toolbarClass} 
    />)

```
## Customize Toolbar components Style

```javascript
const toolbarClass: any = {
  item: {
    undo: {
      border: 'red solid 2px',
      background:'yellow'
    },
    redo: {
      border: 'black solid 3px',
      background:'blue'
    },
    image: {
      border: 'black solid 3px',
      background:'blue'
    }
    
  }
}

return (
    <DocumentEditor 
        toolbarClass={toolbarClass} 
    />)
```

## Customize Editor Page
```javascript
const canvasClass = {
  editorMain: {
    background:'antiquewhite'
  },
  margin: {}
}

return (
    <DocumentEditor 
        canvasClass={canvasClass} 
    />)
```