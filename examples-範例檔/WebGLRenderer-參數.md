WebGLRenderer()中有一些參數我們可以設置，以下這些參數來自於官方文檔：

 antialias:

　　值：true/false

　　含義：是否開啟反鋸齒，設置為true開啟反鋸齒。

 precision:

　　值：highp/mediump/lowp

　　含義：著色精度選擇。

  alpha:

　　值：true/false

　　含義：是否可以設置背景色透明。

 premultipliedAlpha:

　　值：true/false

　　含義：表示是否可以設置像素深度（用來度量圖像的分辨率）

  stencil:

　　值：true/false

　　含義：表示是否使用模板字體或圖案

 preserveDrawingBuffer:

　　值：true/false

　　含義：是否保存繪圖緩衝，若設為true，則可以提取canvas繪圖的緩衝。

  maxLights:

　　值：數值int

　　含義：最大燈光數，我們的場景中最多能夠添加多少個燈光。

範例:
const renderer = new THREE.WebGLRenderer( { antialias: true } );
const renderer = new THREE.WebGLRenderer( { 
  antialias: true,
  alpha: flase,
  precision: 'hihghp',
  maxLight: 3
 } );

