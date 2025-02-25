# Document-Template

![](https://img.shields.io/badge/Generator-mdbook-black?logo=mdbook&logoColor=black&labelColor=white)

本專案是{{ Lorem ipsum dolor }}。

使用 Markdown 來撰寫。

## 文件目錄

文件目錄放置於 [`src/SUMMARY.md`](./src/SUMMARY.md)

## 將文件轉為 HTML 網站

### 手動編譯

請先取得 mdbook（可以在[其專案](https://github.com/rust-lang/mdBook)的 [releases](https://github.com/rust-lang/mdBook/releases) 中找到已編譯好的執行檔 ）

然後到本專案的資料夾，執行 `mdbook build` 即可。

完整的指令如下：

```shell
C:\> cd {{專案資料夾}}
C:\{{專案資料夾}}> mdbook build
```

### By Github Actions

本專案已經有撰寫好 github action，每次更新都會觸發，進去 **Actions** > **Build book to html files** ，選擇最新一次執行任務。

任務執行完成後，**Artifacts**會把編譯好的 HTML 網站打包成 .zip 壓縮檔。


