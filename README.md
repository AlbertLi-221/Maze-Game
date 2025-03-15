# Maze-Game

This is a maze generation game using the depth first search algorithm.

## Feature

```Enhanced Vision``` - Your vision expands by 2 tiles for the next 3 steps

```Restricted Vision``` - Your vision is reduced to 1 tile for the next 5 steps

```Wall Pass``` - You can pass through one wall

```Return to Start``` - You are teleported back to the start, clearing your recorded path and checkpoint

```Fog Mode``` - Added fog mode to limit the player's vision

```Record Mode``` - Record your walk, auto-navigate back to start

## Pending bug fix 

#### Fog Mode

- [X] ```Restricted_Vision``` 事件觸發後，事件圖片覆蓋在迷霧之上
      
- [X] ```Restricted_Vision``` 觸發後，終點迷霧沒有消失的問題
      
- [X] ```Fog Mode``` 開啟時終點迷霧沒有消失的問題
      
- [X] ```Return to Start``` 事件觸發後，角色殘影存留在原本位置上
      
- [ ]  ```Enhanced Vision``` 事件觸發後，若短時間內觸發 ```Return to Start```事件，有機率導致玩家視野突破限制 ( 3x3 )

- [ ] ```Wall Pass``` 事件觸發後，往地圖邊緣走有機率會使玩家走出地圖外 ( 導致遊戲無法進行 )

- [ ] ```Return to Start``` 事件觸發後，會導致 Record 功能沒有作用 ( 暫存點消失 )

- [ ] ```Wall Pass``` 事件觸發後，使用 Record 功能時，角色不會自動穿越牆壁

#### Normal Mode 

- [ ] ```Wall Pass``` 事件觸發後，使用 Record 功能時，角色不會自動穿越牆壁
      
- [ ] ```Wall Pass``` 事件觸發後，往地圖邊緣走有機率會使玩家走出地圖外 ( 導致遊戲無法進行 )

## Resources

[devression Maze-Game](https://github.com/devression/Maze-Game)


## Contributors

<table>
  <tr align="left">
  <td align="center">
  <a href="https://github.com/Xiang511" style="display:inline-block;width:110px"><img src="https://avatars.githubusercontent.com/u/120042360?v=4" width="88px;"alt="Xiang511"/><br/><sub><b>Xiang511</b></sub></a><br/>
  </td> 
    
  <td align="center">
    <a href="https://github.com/a0979551728"  style="display:inline-block;width:110px"><img src="https://avatars.githubusercontent.com/u/182858325?v=4" width="88px;" alt="a0979551728"/><br/><sub><b>a0979551728</b></sub></a><br/>
  </td>
    
  </tr>
</table>

