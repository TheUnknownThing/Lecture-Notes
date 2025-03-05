# Notes for Mathematical Logic

这是TheUnknownThing的数理逻辑（CS2950, 2024-2025 Spring）笔记。

课程教师是尹强老师： [Qiang Yin](https://cs.sjtu.edu.cn/~qyin/)

使用的Handout来自陈翌佳老师： [Yijia Chen](https://basics.sjtu.edu.cn/~chen/)

## 文件说明
我使用 `Xournal++` 编辑笔记，然后导出为 `pdf` 文件。

- `README.md`：本文件
- `logic*_notes.pdf`：第 * 章的笔记，使用 $\LaTeX$ 批注，并使用 `Xournal++` 导出。
- `logic*.xopp`：第 * 章的 `Xournal++` 源文件。你可以自行编译。

注意：`Xournal++` 的 $\LaTeX$ 批注功能默认使用 `pdfLaTeX` 编译，并不能很好的支持中文。我使用了 `XeLaTeX` 编译，所以你可能需要自行修改。同时，默认的模版我也进行了修改。如果你需要得到一致的编译效果，请将模版修改：

- 在文档头部添加
  ```latex
  \usepackage[UTF8]{ctex}
  \setCJKmainfont{Kaiti SC}
  ```

- 在 `begin document` 上方定义的宏包，修改为：
  ```latex
  \everymath{\displaystyle}

  % User input
  \begin{scontents}[store-env=preview]
      %%XPP_TOOL_INPUT%%
  \end{scontents}
  ```

## Credits

- [Qiang Yin](https://cs.sjtu.edu.cn/~qyin/)
- [Yijia Chen](https://basics.sjtu.edu.cn/~chen/)
- [Xournal++](https://github.com/xournalpp/xournalpp)
