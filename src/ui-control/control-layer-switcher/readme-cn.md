如果你想设置多个瓦片图层用于选择作为底图图层，你可以：
1. 初始化地图时，创建一个GroupTileLayer作为底图图层，并将候选图层设为子图层
2. 除了默认的底图图层，将其他子图层的visible属性设为false
3. Layer Switcher控件会自动将所有子图层列出，供你选择底图