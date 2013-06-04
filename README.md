Easer
=====
イージングするやつ。

    var ease =EaseName.EXPONENTIAL.make(EaseMode.IN_OUT, frames, 5);
で 0 - 1 をイージングした配列が返る。
    var start = 100;
    var end = 300;
    Ease.compute(start, end, ease);
で 100 - 300 間のイージングの配列が返る。
