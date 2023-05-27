
# Hype Scroll

The AutoHide Scrollbar project is a custom React component designed to enhance the user experience of scrolling within a web application. Unlike the default scrollbars, this component offers auto-hiding functionality, which means the scrollbar remains hidden until the user hovers over it, providing a cleaner and more immersive interface.




## Usage/Examples
ezy like this
```javascript
 <ScrollArea>
    {children}
 </ScrollArea>
```


## Props
| Parameter | Type     | Description                | Default                |
| :-------- | :------- | :------------------------- | :--------------------- |
| as | `string` | tag name for wrapper | div |
| scrollY | `boolean` | enable vertical scroll | true |
| scrollX | `boolean` | enable horizontal scroll | false |
| autoHideDuration | `number` | timer before it hide, unit as millisecond | 1000 |
| width | `CSSProperties["width"]` | wrapper height | 100% |
| height | `CSSProperties["height]` | wrapper width | 100% |
| trackSize | `number` | as px unit | 14 |
| trackColor | `CSSProperties["background"]` | css background value even gradient | 14 |
| thumbColor | `CSSProperties["background"]` | css background value even gradient | 14 |

