# zxy-notes
常练习；不要问自己会啥，要问自己能干啥；纸上得来终觉浅，绝知此事要躬行。爆碎牙才是自己的。
vscode markdown 更换字体
包含中文的等宽字体,实际上只有前两款可以在 VSCode 中正常等宽
VSCode 是基于 Electron 的，前端由 Chromium 渲染，这种字体渲染问题很可能是 Chromium 导致的，VSCode 侧无能为力
在 issue Monospacing broken by Chinese character #14589 中找到了答复
![](image/Snipaste_2023-09-12_17-25-47.png)
```json
{
    "[markdown]": {
        "editor.fontFamily": "'Sarasa Mono SC'"
    }
}
```