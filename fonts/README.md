# Font Awesome 本地化说明

为了完全本地化Font Awesome字体，您需要下载以下字体文件并放置在本目录中：

1. 从CDN下载字体文件:
   - fontawesome-webfont.woff2 - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff2
   - fontawesome-webfont.woff - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff
   - fontawesome-webfont.ttf - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.ttf
   - fontawesome-webfont.eot - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.eot
   - fontawesome-webfont.svg - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.svg

2. 下载完成后确保文件名与上面列出的完全一致

3. 所有文件都应该放在本目录（即`fonts/`目录）下

## 下载方法

您可以通过以下方式下载这些文件：

### 方法1：通过浏览器
1. 复制上面的URL
2. 在浏览器中打开URL
3. 右键点击页面，选择"另存为"
4. 将文件保存到`fonts/`目录

### 方法2：通过PowerShell（Windows）
使用以下命令下载所有文件：

```powershell
Invoke-WebRequest -Uri "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff2" -OutFile "fontawesome-webfont.woff2"
Invoke-WebRequest -Uri "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff" -OutFile "fontawesome-webfont.woff"
Invoke-WebRequest -Uri "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.ttf" -OutFile "fontawesome-webfont.ttf"
Invoke-WebRequest -Uri "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.eot" -OutFile "fontawesome-webfont.eot"
Invoke-WebRequest -Uri "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.svg" -OutFile "fontawesome-webfont.svg"
```

### 方法3：一次性下载全部
您也可以从Font Awesome官方网站下载完整包，然后提取需要的字体文件：
https://fontawesome.com/v4.7.0/assets/font-awesome-4.7.0.zip 