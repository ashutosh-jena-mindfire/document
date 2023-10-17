---
sidebar_position: 2
---

# Customization Style

Customize the editor's UI style to match your application's requirements.

## Customization Toolbar Style
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
## Customization Tool Style

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
    bold: {
      border: 'black solid 3px',
      background:'blue'
    },
    italic: {
      border: 'black solid 3px',
      background:'blue'
    },
    underline: {
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

## Customization Page
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