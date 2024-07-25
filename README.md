# 0x0：实验

| 序号  | teacher              | layer | 底模        | 数据增强    | 训练集                                                                                      | 时长  |
|:-----|:---------------------|:------|:------------|:-----------|:-------------------------------------------------------------------------------------------|:------|
| 01   | contentvec           | 12    | contentvec  | Default    | WenetSpeech4TTS                                                                            | 375h  |
| 02   | contentvec           | 12    | contentvec  | Default    | WenetSpeech4TTS + m4singer + opensinger + opencpop + popcs                                 | 375h  |
| 03   | chinese-hubert-large | 12    | None        | Default    | WenetSpeech4TTS + m4singer + opensinger + opencpop + popcs                                 | 375h  |
| 04   | chinese-hubert-large | 12    | None        | + Noise    | WenetSpeech4TTS + m4singer + opensinger + opencpop + popcs                                 | 375h  |
| 05   | contentvec           | 12    | contentvec  | + Noise    | WenetSpeech4TTS + m4singer + opensinger + opencpop + popcs                                 | 375h  |

# 0x1：总结

01. loss可以收敛，效果还行
02. loss可以收敛，效果不错
03. loss可以收敛，效果不行
04. loss可以收敛，效果未知
05. loss不能收敛