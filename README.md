# Colors for Applications 
## To Find Colors ( ⌘ + F For Mac , Ctrl + F For Windows)

# Colors For IOS
Extension for Color in IOS
```
extension UIColor {
    public convenience init?(hex: String) {
        let r, g, b, a: CGFloat

        if hex.hasPrefix("#") {
            let start = hex.index(hex.startIndex, offsetBy: 1)
            let hexColor = String(hex[start...])

            if hexColor.count == 8 {
                let scanner = Scanner(string: hexColor)
                var hexNumber: UInt64 = 0

                if scanner.scanHexInt64(&hexNumber) {
                    r = CGFloat((hexNumber & 0xff000000) >> 24) / 255
                    g = CGFloat((hexNumber & 0x00ff0000) >> 16) / 255
                    b = CGFloat((hexNumber & 0x0000ff00) >> 8) / 255
                    a = CGFloat(hexNumber & 0x000000ff) / 255

                    self.init(red: r, green: g, blue: b, alpha: a)
                    return
                }
            }
        }

        return nil
    }
}

 ```
To use the extension  `let gold = UIColor(hex: "#ffe700ff")`


 
# Colors For Android




https://github.com/TheAppWizard/Colors-For-Android/blob/main/footer.png
 
 Color Name : `White`
 ```
 <color name="White">#FFFFFF</color>
 ```
 Color Name : `Ivory`
 ```
 <color name="Ivory">#FFFFF0</color>
  ```
 Color Name : `LightYellow`
 ```
 <color name="LightYellow">#FFFFE0</color>
  ```
  
 Color Name : `Yellow`
 ```
 <color name="Yellow">#FFFF00</color>
  ```

Color Name : `Snow`
 ```
  <color name="Snow">#FFFAFA</color>
  ```
  
 Color Name : `Floral White`
 ```
  <color name="FloralWhite">#FFFAF0</color>
  ```
  
 Color Name : `LemonChiffon`
 ```
 <color name="LemonChiffon">#FFFACD</color>
  ```
 
 Color Name : `Cornsilk`
 ```
 <color name="Cornsilk">#FFF8DC</color>
  ```
  
 Color Name : `Seashell`
 ```
  <color name="Seashell">#FFF5EE</color>
  ```
  
 Color Name : `LavenderBlush`
 ```
<color name="LavenderBlush">#FFF0F5</color>
  ```  
 
 Color Name : `PapayaWhip`
 ```
<color name="PapayaWhip">#FFEFD5</color>
  ```  
  
  Color Name : `BlanchedAlmond`
 ```
 <color name="BlanchedAlmond">#FFEBCD</color>
  ```   
  
 Color Name : `MistyRose`
 ```
<color name="MistyRose">#FFE4E1</color>
  ```   

 Color Name : `Bisque`
 ```
<color name="Bisque">#FFE4C4</color>
  ```  
  
Color Name : `Moccasin`
 ```
<color name="Moccasin">#FFE4B5</color>
  ``` 
  
Color Name : `NavajoWhite`
 ```
 <color name="NavajoWhite">#FFDEAD</color>
  ```   
  
Color Name : `PeachPuff`
 ```
 <color name="PeachPuff">#FFDAB9</color>
  ```  
  
 Color Name : `Gold`
 ```
 <color name="Gold">#FFD700</color>
  ```  
  
 Color Name : `Pink`
 ```
 <color name="Pink">#FFC0CB</color>
  ```  
  
 Color Name : `LightPink`
 ```
 <color name="LightPink">#FFB6C1</color>
  ```
  
 Color Name : `Orange`
 ```
  <color name="Orange">#FFA500</color>
  ``` 
  
  Color Name : `LightSalmon`
 ```
  <color name="LightSalmon">#FFA07A</color>
  ```

  Color Name : `DarkOrange`
 ```
 <color name="DarkOrange">#FF8C00</color>
  ```

  Color Name : `Coral`
 ```
 <color name="Coral">#FF7F50</color>
  ```
  
  Color Name : `HotPink`
 ```
 <color name="HotPink">#FF69B4</color>
  ```
  
 Color Name : `Tomato`
 ```
 <color name="Tomato">#FF6347</color>
  ```
  
 Color Name : `OrangeRed`
 ```
 <color name="OrangeRed">#FF4500</color>
  ```
  
 Color Name : `DeepPink`
 ```
 <color name="DeepPink">#FF1493</color>
  ```
  
 Color Name : `Fuchsia / Magenta`
 ```
 <color name="Fuchsia">#FF00FF</color>
 <color name="Magenta">#FF00FF</color>
  ```
  
 Color Name : `Red`
 ```
 <color name="Red">#FF0000</color>
  ```
  Color Name : `OldLace`
 ```
 <color name="OldLace">#FDF5E6</color>
  ```
  
  Color Name : `LightGoldenrodYellow`
 ```
 <color name="LightGoldenrodYellow">#FAFAD2</color>
  ```
  
  Color Name : `Linen`
 ```
 <color name="Linen">#FAF0E6</color>
  ```
  
 Color Name : `AntiqueWhite`
 ```
 <color name="AntiqueWhite">#FAEBD7</color>
  ```
  
 Color Name : `Salmon`
 ```
  <color name="Salmon">#FA8072</color>
  ```

 Color Name : `GhostWhite`
 ```
  <color name="GhostWhite">#F8F8FF</color>
  ```
  
 Color Name : `MintCream`
 ```
<color name="MintCream">#F5FFFA</color>
  ```
 
 Color Name : `WhiteSmoke`
 ```
<color name="WhiteSmoke">#F5F5F5</color>  
```

 Color Name : `Beige`
 ```
<color name="Beige">#F5F5DC</color>
```

 Color Name : `Wheat`
 ```
 <color name="Wheat">#F5DEB3</color>
```

 Color Name : `SandyBrown`
 ```
<color name="SandyBrown">#F4A460</color>
```

Color Name : `Azure`
 ```
 <color name="Azure">#F0FFFF</color>
```

Color Name : `Honeydew`
 ```
 <color name="Honeydew">#F0FFF0</color>
```
 
 Color Name : `AliceBlue`
 ```
  <color name="AliceBlue">#F0F8FF</color>
```

 Color Name : `khaki`
 ```
  <color name="Khaki">#F0E68C</color>
```
 
 Color Name : `LightCoral`
 ```
  <color name="LightCoral">#F08080</color>
```
 
 
 Color Name : `PaleGoldenrod`
 ```
  <color name="PaleGoldenrod">#EEE8AA</color>
```


 Color Name : `Violet`
 ```
  <color name="Violet">#EE82EE</color>
```


 Color Name : `DarkSalmon`
 ```
 <color name="DarkSalmon">#E9967A</color>
 ```
 
 Color Name : `Lavender`
 ```
 <color name="Lavender">#E6E6FA</color>
 ```
 
  Color Name : `LightCyan`
 ```
  <color name="LightCyan">#E0FFFF</color>
 ```
 
  Color Name : `BurlyWood`
 ```
  <color name="BurlyWood">#DEB887</color>
 ```
 
 
  Color Name : `Plum`
 ```
  <color name="Plum">#DDA0DD</color>
 ```
 
   Color Name : `Gainsboro`
 ```
  <color name="Gainsboro">#DCDCDC</color>
 ```

 Color Name : `Crimson`
 ```
   <color name="Crimson">#DC143C</color>
 ```
 
  Color Name : `Crimson`
 ```
   <color name="Crimson">#DC143C</color>
 ```

  Color Name : `PaleVioletRed`
 ```
   <color name="PaleVioletRed">#DB7093</color>
 ```
 
  Color Name : `Goldenrod`
 ```
    <color name="Goldenrod">#DAA520</color>
 ```
 
  Color Name : `Orchid`
 ```
   <color name="Orchid">#DA70D6</color>
 ```
  Color Name : `Thistle`
 ```
   <color name="Thistle">#D8BFD8</color>
 ```
 
 Color Name : `LightGrey`
 ```
  <color name="LightGrey">#D3D3D3</color>
 ```
 
  
 Color Name : `Tan`
 ```
   <color name="Tan">#D2B48C</color>
 ```
 
 Color Name : `Chocolate`
 ```
 <color name="Chocolate">#D2691E</color>
 ```
 
  Color Name : `Peru`
 ```
  <color name="Peru">#CD853F</color>
 ```
 
  Color Name : `IndianRed`
 ```
 <color name="IndianRed">#CD5C5C</color>
 ```

 Color Name : `MediumVioletRed`
 ```
 <color name="MediumVioletRed">#C71585</color>
 ```
 
 Color Name : `Silver`
 ```
 <color name="Silver">#C0C0C0</color>
 ```

  Color Name : `DarkKhaki`  
 ```
 <color name="DarkKhaki">#BDB76B</color>
 ```
 
  Color Name : `RosyBrown`  
  ```
 <color name="RosyBrown">#BC8F8F</color>
 ```
 
 Color Name : `MediumOrchid`  
  ```
 <color name="MediumOrchid">#BA55D3</color>
 ```
 
  Color Name : `DarkGoldenRod`  
  ```
  <color name="DarkGoldenrod">#B8860B</color>
 ```
 
  Color Name : `FireBrick`  
  ```
 <color name="FireBrick">#B22222</color>
 ```
 
  Color Name : `PowderBlue`  
  ```
 <color name="PowderBlue">#B0E0E6</color>
 ```
 
 Color Name : `LightSteelBlue`  
  ```
 <color name="LightSteelBlue">#B0C4DE</color>
 ```
 
 Color Name : `PaleTurquoise`  
  ```
 <color name="PaleTurquoise">#AFEEEE</color>
 ```
 
 Color Name : `GreenYellow`  
  ```
<color name="GreenYellow">#ADFF2F</color>
 ```
 
 Color Name : `LightBlue`  
  ```
<color name="LightBlue">#ADD8E6</color>
 ```
 
 Color Name : `DarkGray`  
  ```
<color name="DarkGray">#A9A9A9</color>
 ```
 
 Color Name : `Brown`  
  ```
<color name="Brown">#A52A2A</color>
 ```
 
 Color Name : `Sienna`  
  ```
<color name="Sienna">#A0522D</color>
 ```
 
 Color Name : `YellowGreen`  
  ```
 <color name="YellowGreen">#9ACD32</color>
 ```
 
 Color Name : `DarkOrchid`  
  ```
 <color name="DarkOrchid">#9932CC</color>
 ```
 
 Color Name : `PaleGreen`  
  ```
<color name="PaleGreen">#98FB98</color>
 ```
 
  Color Name : `DarkViolet`  
  ```
 <color name="DarkViolet">#9400D3</color>
 ```
 
  Color Name : `MediumPurple`  
  ```
  <color name="MediumPurple">#9370DB</color>
 ```
 
  Color Name : `LightGreen`  
  ```
 <color name="LightGreen">#90EE90</color>
 ```
 
   Color Name : `DarkSeaGreen`  
  ```
 <color name="DarkSeaGreen">#8FBC8F</color>
 ```
  
 Color Name : `SaddleBrown`  
  ```
<color name="SaddleBrown">#8B4513</color>
 ```
 
 Color Name : `DarkMagenta`  
  ```
 <color name="DarkMagenta">#8B008B</color>
 ```
 
  Color Name : `DarkRed`  
  ```
  <color name="DarkRed">#8B0000</color>
 ```
 
  Color Name : `BlueViolet`  
  ```
 <color name="BlueViolet">#8A2BE2</color>
 ```
 
   Color Name : `Olive`  
  ```
 <color name="Olive">#808000</color>
 ```
 
   Color Name : `LightSkyBlue`  
  ```
 <color name="LightSkyBlue">#87CEFA</color>
 ```
 
   Color Name : `SkyBlue`  
  ```
<color name="SkyBlue">#87CEEB</color>
 ```
 
   Color Name : `Gray`  
  ```
 <color name="Gray">#808080</color>
 ```
   
   
 Color Name : `Purple`  
  ```
<color name="Purple">#800080</color>
 ```
 
Color Name : `Maroon`  
  ```
<color name="Maroon">#800000</color>
 ```
Color Name : `Aquamarine`  
  ```
<color name="Aquamarine">#7FFFD4</color>
 ```
 
 Color Name : `Chartreuse`  
  ```
<color name="Chartreuse">#7FFF00</color>
 ```
  Color Name : `LawnGreen`  
  ```
 <color name="LawnGreen">#7CFC00</color>
 ```
 
  Color Name : `MediumSlateBlue`  
  ```
 <color name="MediumSlateBlue">#7B68EE</color>
 ```
 
  Color Name : `LightSlateGray`  
  ```
 <color name="LightSlateGray">#778899</color>
 ```
 
  Color Name : `SlateGray`  
  ```
  <color name="SlateGray">#708090</color>
 ```
 
  Color Name : `OliveDrab`  
  ```
 <color name="OliveDrab">#6B8E23</color>
 ```
 
  Color Name : `SlateBlue`  
  ```
  <color name="SlateBlue">#6A5ACD</color>
 ```
 
 Color Name : `DimGray`  
  ```
  <color name="DimGray">#696969</color>
 ```
  
  Color Name : `MediumAquamarine`  
  ```
  <color name="MediumAquamarine">#66CDAA</color>
 ```
 
  Color Name : `CornflowerBlue`  
  ```
  <color name="CornflowerBlue">#6495ED</color>
 ```
 
  Color Name : `CadetBlue`  
  ```
 <color name="CadetBlue">#5F9EA0</color>
 ```
 
 Color Name : `DarkOliveGreen`  
  ```
<color name="DarkOliveGreen">#556B2F</color>
 ```
 
Color Name : `Indigo`  
  ```
<color name="Indigo">#4B0082</color>
 ```
 
 Color Name : `MediumTurquoise`  
  ```
 <color name="MediumTurquoise">#48D1CC</color>
 ```
 
  Color Name : `DarkSlateBlue`  
  ```
  <color name="DarkSlateBlue">#483D8B</color>
 ```
   Color Name : `DarkSlateBlue`  
  ```
  <color name="DarkSlateBlue">#483D8B</color>
 ```
 
   Color Name : `SteelBlue`  
  ```
 <color name="SteelBlue">#4682B4</color>
 ```
 
  Color Name : `SteelBlue`  
  ```
 <color name="SteelBlue">#4682B4</color>
 ```
 
 
 Color Name : `RoyalBlue`  
  ```
<color name="RoyalBlue">#4169E1</color>
 ```
 
Color Name : `Turquoise`  
  ```
 <color name="Turquoise">#40E0D0</color>
 ```
 
 Color Name : `MediumSeaGreen`  
  ```
 <color name="MediumSeaGreen">#3CB371</color>
 ```

Color Name : `LimeGreen`  
  ```
 <color name="LimeGreen">#32CD32</color>
 ```
 
 Color Name : `DarkSlateGray`  
  ```
<color name="DarkSlateGray">#2F4F4F</color>
 ```

 Color Name : `SeaGreen`  
  ```
 <color name="SeaGreen">#2E8B57</color>
 ```

 Color Name : `ForestGreen`  
  ```
 <color name="ForestGreen">#228B22</color>
 ```
 
  Color Name : `LightSeaGreen`  
  ```
 <color name="LightSeaGreen">#20B2AA</color>
 ```
 
 Color Name : `DodgerBlue`  
  ```
 <color name="DodgerBlue">#1E90FF</color>
 ```

Color Name : `MidnightBlue`  
  ```
  <color name="MidnightBlue">#191970</color>
 ```
 
 Color Name : `Aqua`  
  ```
  <color name="Aqua">#00FFFF</color>
 ```
 
  Color Name : `Cyan`  
  ```
 <color name="Cyan">#00FFFF</color>
 ```
 
 Color Name : `SpringGreen`  
  ```
<color name="SpringGreen">#00FF7F</color>
 ```

 Color Name : `Lime`  
  ```
 <color name="Lime">#00FF00</color>
 ```

Color Name : `MediumSpringGreen`  
  ```
<color name="MediumSpringGreen">#00FA9A</color>
 ```
 Color Name : `DarkTurquoise`  
  ```
 <color name="DarkTurquoise">#00CED1</color>
 ```
 
  Color Name : `DeepSkyBlue`  
  ```
 <color name="DeepSkyBlue">#00BFFF</color>
 ```
 
   Color Name : `DarkCyan`  
  ```
 <color name="DarkCyan">#008B8B</color>
 ```
 
  Color Name : `Teal`  
  ```
 <color name="Teal">#008080</color>
 ```
 
 Color Name : `Green`  
  ```
 <color name="Green">#008000</color>
 ```
 
  
 Color Name : `DarkGreen`  
  ```
  <color name="DarkGreen">#006400</color>
 ```


Color Name : `Blue`
 ```
  <color name="Blue">#0000FF</color>
  ```



Color Name : `MediumBlue`
 ```
  <color name="MediumBlue">#0000CD</color>
 ```
Color Name : `DarkBlue`
 ```
 <color name="DarkBlue">#00008B</color>
  ```
 
 
 Color Name : `Navy`
 ```
 <color name="Navy">#000080</color>
  ```
 
 Color Name : `Black`
 ```
<color name="Black">#000000</color>
  ```

# Color Transparency (R G B A)
How to use ??

Select Color
  ```
<color name="Black">#000000</color>
  ```
Add Transparency  
 
   ```
<color name="Black">#000000 FF</color>
  ```

```
100% — FF
95% — F2
90% — E6
85% — D9
80% — CC
75% — BF
70% — B3
65% — A6
60% — 99
55% — 8C
50% — 80
45% — 73
40% — 66
35% — 59
30% — 4D
25% — 40
20% — 33
15% — 26
10% — 1A
5% — 0D
0% — 00
```

![Image of Footer](https://github.com/TheAppWizard/Colors-For-Android/blob/main/footer.png)

  
 
 
