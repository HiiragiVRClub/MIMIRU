# 使っている部品・モデルのライセンス

MIMIRU は次の部品・モデルを使っています。それぞれの作者に感謝します。

## zip に入っているもの
| 名前 | 用途 | ライセンス |
|---|---|---|
| LINE Seed JP | 画面の文字（フォント） | SIL Open Font License 1.1（`fonts\OFL.txt`） |

## セットアップのときに入れる部品（Python のパッケージ）
| 名前 | 用途 | ライセンス |
|---|---|---|
| faster-whisper | 文字起こし | MIT |
| CTranslate2 | 文字起こし・翻訳を動かす | MIT |
| ONNX Runtime | 話者の聞き分け | MIT |
| tokenizers | 翻訳の文字の区切り | Apache 2.0 |
| huggingface_hub | モデルのダウンロード | Apache 2.0 |
| NumPy | 計算 | BSD 3-Clause |
| Pillow | 画像 | MIT-CMU（HPND） |
| mss | 画面の撮影 | MIT |
| sounddevice（PortAudio） | 音声 | MIT |
| keyboard | ショートカットキー | MIT |
| pywebview | 画面（Edge WebView2） | BSD 3-Clause |
| openvr（pyopenvr） | VR の表示（SteamVR） | BSD 3-Clause |
| NVIDIA CUDA の部品（cuBLAS・cuDNN・NVRTC） | GPU で動かす（NVIDIA の GPU のときだけ） | NVIDIA のソフトウェア使用許諾 |

## はじめての起動でダウンロードするモデル
| 名前 | 用途 | ライセンス |
|---|---|---|
| Whisper large-v3-turbo / small（faster-whisper 用に変換したもの） | 文字起こし | MIT |
| NLLB-200 distilled 600M（Meta。CTranslate2 用に変換したもの） | PC の中の翻訳 | **CC BY-NC 4.0（非商用）** |
| CAM++（3D-Speaker。sherpa-onnx 用） | 話者の聞き分け | Apache 2.0 |

## 別に入れるもの（任意）
| 名前 | 用途 | ライセンス |
|---|---|---|
| AivisSpeech | 回答の読み上げ | AivisSpeech の利用規約（声のモデルはそれぞれの規約） |
| SteamVR | VR | Valve の利用規約 |
