# jquery-touch
在jquery的基础上扩展触摸事件，由百度Touch.js改进而来

使用：

    $('#id').on('pinchstart pinchend pinch pinchin pinchout rotateleft rotateright rotate swipestart swiping swipeend swipeleft swiperight swipeup swipedown swipe drag dragstart dragend hold tap doubletap', function(event) {
        // 事件详细信息在：event.detail
        console.log(event.detail);
    });
