# teeworlds_player_color_value_to_rgb

吧teeworlds/ddnet中有关颜色的值转换到RGB(Convert the value of the color in teeworlds/ddnet to RGB)

安装(install):
 - `pip install teeworlds_player_color_value_to_rgb`

使用/use:
> 我使用了py自带的math和colorsys库(I used the math and colorsys libraries that come with py)

  value到rgb(value to rgb)
 - ```
   from teeworlds_player_color_value_to_rgb import value_to_rgb
   value = 8624384
   rgb = value_to_rgb(value)
   print(rgb)
   ```
  value到hsl(value to hsl)
 - ```
   from teeworlds_player_color_value_to_rgb import value_to_hsl
   value = 8624384
   hsl = value_to_hsl(value)
   print(hsl)
   ```

有什么问题请新建Issues(If you have any questions, please create a new Issues)

PS：Everything in English is generated using Google Translate(一切英文使用谷歌翻译生成)
