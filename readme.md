# Canvas2image #
a tool of saving or converting canvas to images

## Demo ##
[canvas2image](http://hongru.github.com/proj/canvas2image/index.html)

## Code ##
you can just use it like this

    Canvas2Image.saveAsImage(canvasObj, width, height, type)
    Canvas2Image.saveAsPNG(canvasObj, width, height)
    Canvas2Image.saveAsJPEG(canvasObj, width, height)
    Canvas2Image.saveAsGIF(canvasObj, width, height)
    Canvas2Image.saveAsBMP(canvasObj, width, height)
    
    Canvas2Image.convertToImage(canvasObj, width, height, type)
    Canvas2Image.convertToPNG(canvasObj, widht, height)
    Canvas2Image.convertToJPEG(canvasObj, widht, height)
    Canvas2Image.convertToGIF(canvasObj, widht, height)
    Canvas2Image.convertToBMP(canvasObj, widht, height)
    
    
    
## 原理

    function saveFile (strData) {
		document.location.href = strData;
	}
