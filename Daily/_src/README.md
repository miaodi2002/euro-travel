# 每日行程单源文件

每个 `07-DD.html` 对应 `Daily/` 里的一份 PDF。行程变更时：改对应 HTML → 用下面命令重新生成 PDF（文件名按 `<title>` 命名）。

```bash
cd Daily/_src
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu \
  --no-pdf-header-footer --print-to-pdf="out.pdf" "file://$PWD/07-DD.html"
```

生成于 2026-07-05（行程版本 v5.4）。
