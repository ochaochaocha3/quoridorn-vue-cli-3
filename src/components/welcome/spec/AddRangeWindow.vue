<template>
  <spec-frame property="addRangeWindow" label-str="範囲追加" lastVersion="1.0.0b1" :isSpecFixed="true">
    <!----------------------
     ! 起動操作
     !--------------------->
    <spec-item class-str="operation" label-str="起動操作">
      <li>画面上部メニューの「コマ」を選択</li>
      <li>「範囲追加」を選択</li>
    </spec-item>
    <!----------------------
     ! 仕様
     !--------------------->
    <spec-item class-str="spec" label-str="仕様">
      <li>名前の設定</li>
      <li>「射界」の設定 → 別項「射界」参照</li>
    </spec-item>
    <!----------------------
     ! ユーザ要望
     !--------------------->
    <spec-item class-str="request" label-str="ユーザ要望">
      <li>別項「射界」参照</li>
    </spec-item>
    <!----------------------
     ! 未実装事項
     !--------------------->
    <spec-item class-str="unImplemented" label-str="未実装事項">
      <li>本機能自体が未実装</li>
      <li>中身の処理はキャラクターに簡易実装されているが、バグが数点ある</li>
    </spec-item>
    <!----------------------
     ! 実装しない機能
     !--------------------->
    <spec-item class-str="unSupport" label-str="実装しない機能">
      <li>どどんとふの各システム用に用意された「範囲追加」は対応しない<br>→ 基本機能が全て実装できた後の「個別システム対応」のフェーズで対応するかも</li>
    </spec-item>
    <!----------------------
     ! 関連項目
     !--------------------->
    <spec-item class-str="ref" label-str="関連項目">
      <li><spec-link property="menuBar" title-str="">メインメニュー</spec-link></li>
    </spec-item>
  </spec-frame>
</template>

<script>
import SpecMixin from "./SpecMixin";
export default { mixins: [SpecMixin] };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="./spec.css">
</style>
