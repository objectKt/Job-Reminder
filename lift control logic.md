``` kotlin
/**
 * 梯控指令收到的廣播數據
 * 梯控逻辑的顺序：
 * 1. 首先 PRESS_FLOOR 指令摁电梯数字前往指定目标楼层 floorGo
 * 2. 电梯行驶过程中不断 GET_FLOOR 指令获取电梯当前运行抵达的楼层 floorNow
 * 3. 根据 floorNow == floorGo 判断电梯已抵达目标楼层，则发送 OPEN_FLOOR 指令维持开门 xx 秒
 * 4. 没有关门指令，只需要在 OPEN_FLOOR 指令的参数 xx 秒后，电梯门会自动关闭
 */
```
