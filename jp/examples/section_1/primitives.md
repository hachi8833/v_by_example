# プリミティブ型

Vのプリミティブ型は、Go言語よりも少なくなっています。

## 基本型

- bool型（`true`または`false`）

- string型

- integer型（`int`）

- float型（`float`）

- rune型（Unicodeコードポイント）-- `0xf09f9880`など

## 複合型

- array型（`[]`）

- map型（`{}`）

- struct型

## integer型

integer（整数）型はさらに`signed`（符号あり）と`unsigned`（符号なし）に分けられます。`signed`は正または負の値を表しますが、`unsigned`は正の値だけを表します。

### 符号あり整数

| 型名      |   サイズ  |                                 値の範囲 |
| -------- | :------: | --------------------------------------:|
| `int8`   |  8ビット  |             -128 〜 2<sup>7</sup> -1    |
| `int16`  | 16ビット  |  -2<sup>15</sup> 〜 2<sup>15</sup> - 1  |
| `int`    | 32ビット  |  -2<sup>31</sup> 〜 2<sup>31</sup> - 1  |
| `int64`  | 64ビット  |  -2<sup>63</sup> 〜 2<sup>63</sup> - 1  |
| `int128` | 128ビット | -2<sup>127</sup> 〜 2<sup>127</sup> - 1 |

### 符号なし整数

| 型名   |   サイズ   |                  値の範囲 |
| ------ | :------: | -----------------------: |
| `byte` |  8ビット  |  0 〜 2<sup>7</sup> -1   |
| `u16`  | 16ビット  |  0 〜 2<sup>15</sup> - 1 |
| `u32`  | 32ビット  |  0 〜 2<sup>31</sup> - 1 |
| `u64`  | 64ビット  |  0 〜 2<sup>63</sup> - 1 |
| `u128` | 128ビット |  0 〜 2<sup>127</sup> - 1|