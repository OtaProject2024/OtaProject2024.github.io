<script setup>
import { ref } from "vue";
import card from "../globals/card.vue";

const path = ref("https://github.com/OtaProject2024/PyDoch");
const img = ref("./assets/general/logo.png");
</script>

<template>
  <div class="hov-hl animate-part-in rounded-lg p-3 mt-2 mb-12">
    <p>
      開発プロセスを効率化するためにGitHubを活用し、ソースコードの開発を行いました。 GitHubを使用することで、バージョン管理や問題追跡などが容易に行えます。
      進行状況やコードの変更履歴を透明にし、より効果的な開発プロセスを実現しています。
    </p>
    <card title="OtaProject2024 / PyDoch" text="GitHub is where OtaProject2024 builds software." :path="path" :img="img" />
    <p>
      PyDochリポジトリは、ロボットを制御するためのPythonスクリプト群です。 PyYAMLを使用した柔軟な設定管理、RPi.GPIOによるRaspberry PiのGPIOピン制御、adafruit_bno055を活用したセンサーデータの取得、そしてPyGameによる音声制御を実現しています。
      さらに、マルチスレッディングを駆使して、リアルタイムの応答性を損なわずに効率的な処理を可能にしている点が特徴です。
    </p>
  </div>
</template>
