# BGM Loop Editor / BGMループ編集

**https://aoechan.github.io/bgm-loop-editor/**

Pick a seamless loop point for game music by ear while looking at the waveform, then export the intro and loop as WAV.

- Drop a track → the tempo is estimated → move the loop start / end markers (snap to bars or beats) → "Hear the seam" plays across the join on repeat → export `_intro.wav`, `_loop.wav` (crossfade baked in) and a JSON with tempo and loop points.
- Seam candidates can be suggested automatically (pairs of similar-sounding bars) — your ears decide.
- **No sign-up, no install. Everything runs in your browser; your files are never uploaded.** It is a single static HTML file with no external scripts, fonts or analytics.

### Your music stays yours
Files you make with this tool keep the rights of the original track. Neither this tool nor its author claims any rights over your music or loops, or puts any conditions on how you use them. You are free to use the exported loops however you like — including in commercial games you sell — within the license of the original track (make sure the original music allows that use).

### License
The tool itself is released under the [MIT License](LICENSE). The license covers the tool's code only; it does not apply to, or place any requirement on, the audio you process with it.

---

ゲーム用のBGMのループのつなぎ目を、波形を見ながら耳で選んで、イントロとループをWAVで書き出すツールです。

- 曲を入れる → テンポを自動で推定 → ループの始まり・終わりの印を動かす（小節や拍に吸着） → 「つなぎ目を聞く」でつなぎ目を繰り返し確認 → `_intro.wav`、`_loop.wav`（重ねは焼き込み済み）と、テンポとループ位置のJSONを書き出し。
- つなぎ目の候補を自動で探すこともできます（似た小節同士の組み合わせ。最後は耳で決める）。
- **登録不要・インストール不要。すべてブラウザの中だけで動き、ファイルはどこにも送信しません。** 外部のスクリプト、フォント、解析ツールを一切読み込まない、HTMLファイル1つです。

### 曲の権利はそのまま
このツールで作ったファイルの権利は、元の曲の権利のままです。このツールやその作者が、あなたの曲やループに何かの権利を主張したり、利用に条件を付けたりすることはありません。書き出したループは、ゲームに組み込んで販売することも含めて、自由に使えます。ただし、元の曲の利用許諾の範囲内でお使いください（元の曲がその使い方を認めているか確認してください）。

### ライセンス
ツール本体は [MITライセンス](LICENSE) です。このライセンスはツールのコードにだけ適用され、ツールで加工した音声には適用されず、何の条件も付けません。
