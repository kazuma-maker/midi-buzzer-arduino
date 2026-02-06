★ MIDI ArduinoIDE PRO
Easily convert MIDI files into Arduino code and play music using a passive buzzer.


## 🎥 Demo Video
Arduino passive buzzer playing MIDI converted data.

[![MIDI Buzzer Demo](https://img.youtube.com/vi/tG08ZIrSq70/0.jpg)](https://www.youtube.com/watch?v=tG08ZIrSq70)

Polyphonic Synthesizer Generator for Arduino with Passive Buzzers.

[Open Application ](https://kazuma-maker.github.io/midi-buzzer-arduino/)

★★ Overview
This tool runs entirely in your web browser. It converts standard MIDI files (.mid) into optimized C++ source code for --Arduino UNO R4-- and --ESP32--.

Its main feature is the ability to perform rich --polyphonic music (chords & harmony)-- using multiple passive buzzers. By connecting buzzers to the microcontroller's GPIO pins, you can create an ensemble without needing expensive audio shields.

★★ Key Features

- --Multi-Buzzer Polyphony--
    Supports up to 12 voices simultaneously. The tool analyzes the MIDI file and automatically assigns tracks (Melody, Bass, Backing) to available pins.
- --Real-time Editor--
    Adjust playback speed, volume balance, and octave shift directly in the browser. It also features a visual trimming tool to select specific parts of the song.
- --Advanced Tuning Systems--
    Supports  20 tuning systems beyond standard 12-TET, including Just Intonation, Pythagorean, Gamelan (Slendro/Pelog), and Microtonal scales.
- --High Performance--
    - --UNO R4:-- Uses direct register manipulation for high-speed software PWM.
    - --ESP32:-- Uses Hardware LEDC PWM for clear sound.

★★ Wiring Guide

Connect the positive (+) pin of the passive buzzers to the following GPIO pins, and connect all negative (-) pins to GND.

| Voice No. | Arduino UNO R4 Pin | ESP32 Pin |
| :---: | :---: | :---: |
| 1 | D2 | GPIO 26 |
| 2 | D3 | GPIO 25 |
| 3 | D4 | GPIO 27 |
| 4 | D5 | GPIO 32 |
| 5 | D6 | GPIO 33 |
| 6 | D7 | GPIO 19 |
| 7 | D8 | GPIO 18 |
| 8 | D9 | GPIO 21 |
| 9 | D10 | GPIO 22 |
| 10 | D11 | GPIO 23 |
| 11 | D12 | GPIO 13 |
| 12 | D13 | GPIO 12 |

★★ How to Use

1. --Open the App:-- Access the GitHub Pages URL provided above.
2. --Load MIDI:-- Drag & drop your .mid file (or use the built-in sample).
3. --Settings:-- Select your board (R4 or ESP32) and the number of buzzers you have connected.
4. --Edit:-- Adjust volume, tuning, and trim the timeline if needed.
5. --Generate:-- Click "GENERATE SKETCH".
6. --Flash:-- Copy the generated code into the Arduino IDE and upload it to your board.

★★ License
MIT License

---

★ MIDI ArduinoIDE PRO (Japanese)

複数のパッシブブザーを使用して、Arduinoを多重和音シンセサイザーに変身させるWebツールです。

[アプリを開く ](https://kazuma-maker.github.io/midi-buzzer-arduino/)

★★ 概要
このツールはブラウザ上で動作し、標準的なMIDIファイル (.mid) を --Arduino UNO R4-- または --ESP32-- 用のC++ソースコードに変換します。

最大の特徴は、複数のパッシブブザーをGPIOピンに接続することで実現する--「和音（ポリフォニック）演奏」--です。高価なDACやシールドを使用することなく、ブザーだけで重厚なアンサンブル再生を可能にします。

★★ 主な機能

- --多重和音演奏--
    最大12音（12個のブザー）の同時発音に対応しています。MIDIトラックを解析し、メロディ・ベース・伴奏を自動的に各ピンへ割り当てます。
- --リアルタイム編集--
    再生速度、各パートの音量バランス、オクターブ変更をブラウザ上で調整できます。波形を見ながら再生範囲を指定できるトリミング機能も搭載しています。
- --高度な音律対応--
    平均律（12-TET）だけでなく、純正律、ピタゴラス音律、ガムラン（スレンドロ/ペロッグ）、微分音など20種類の音律プリセットに対応しています。
- --高性能なコード生成--
    - --UNO R4:-- レジスタ直接操作による高速ソフトウェアPWMを使用。
    - --ESP32:-- ハードウェアLEDC PWM機能を使用し、クリアな音質を実現。

★★ 配線ガイド

パッシブブザーのプラス側を以下のピンに接続し、マイナス側をすべてGNDに接続してください。

| ボイス番号 | Arduino UNO R4 ピン | ESP32 ピン |
| :---: | :---: | :---: |
| 1 | D2 | GPIO 26 |
| 2 | D3 | GPIO 25 |
| 3 | D4 | GPIO 27 |
| 4 | D5 | GPIO 32 |
| 5 | D6 | GPIO 33 |
| 6 | D7 | GPIO 19 |
| 7 | D8 | GPIO 18 |
| 8 | D9 | GPIO 21 |
| 9 | D10 | GPIO 22 |
| 10 | D11 | GPIO 23 |
| 11 | D12 | GPIO 13 |
| 12 | D13 | GPIO 12 |

★★ 使い方

1. --アプリを開く:-- 上記のGitHub PagesのURLにアクセスします。
2. --MIDI読み込み:-- .midファイルを画面にドラッグ＆ドロップします（または内蔵サンプルを使用）。
3. --設定:-- 使用するマイコンボード（R4またはESP32）と、接続したブザーの数を選択します。
4. --編集:-- 必要に応じて音量バランスや音律、再生範囲（トリミング）を調整します。
5. --生成:-- "GENERATE SKETCH" ボタンをクリックします。
6. --書き込み:-- 生成されたコードをArduino IDEにコピーし、マイコンに書き込みます。

★★ ライセンス

MIT License



