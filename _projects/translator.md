---
layout: project
permalink: /projects/translator
title: Троичный калькулятор
---

<div class="machine-translator" data-behavior="trinary-translator">
    <div class="input-group">
        <label class="label-inline input-group-addon translator-label" for="number_bin" title="binary">
          Binary
        </label>
        <input class="input-sm form-control" type="text" data-kind="binary" id="number_bin" placeholder="0 1">
    </div>
    <div class="input-group">
        <label class="label-inline input-group-addon translator-label" for="number_tri" title="trinary">
          Trinary
        </label>
        <input class="input-sm form-control" type="text" data-kind="trinary" id="number_tri" placeholder="- 0 +">
    </div>
    <div class="input-group">
        <label class="label-inline input-group-addon translator-label" for="number_oct" title="octonary">
          Octonary
        </label>
        <input class="input-sm form-control" type="text" data-kind="octonary" id="number_oct" placeholder="0 1 2 3 4 5 6 7">
    </div>
    <div class="input-group">
        <label class="label-inline input-group-addon translator-label" for="number_non" title="nonary">
          Nonary
        </label>
        <input class="input-sm form-control" type="text" data-kind="nonary" id="number_non" placeholder="w x y z 0 1 2 3 4">
    </div>
    <div class="input-group">
        <label class="label-inline input-group-addon translator-label" for="number_dec" title="decimal">
          Decimal
        </label>
        <input class="input-sm form-control" type="text" data-kind="decimal" id="number_dec" placeholder="0 1 2 3 4 5 6 7 8 9">
    </div>
    <div class="input-group">
        <label class="label-inline input-group-addon translator-label" for="number_hex" title="hexadecimal">
          Hexadecimal
        </label>
        <input class="input-sm form-control" type="text" data-kind="hexadecimal" id="number_hex" placeholder="0 1 2 3 4 5 6 7 8 9  a b c d e f">
    </div>
</div>