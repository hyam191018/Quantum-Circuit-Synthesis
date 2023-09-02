# Quantum Circuit Synthesis


## 動機

基於量子電路的電腦是未來的趨勢，相比於傳統1和0的位元，量子電腦所採用的quantum bit憑藉著"旋轉"這種操作，進行input與output的轉換。然而，量子電路的設計目前還沒有一個最佳的演算法的找出最小數量的quantum gate，故本程式希望藉由暴力法強行生成出一個較少gates的量子電路。

本程式實現了一個真值表到量子電路的轉換，雖然可能不是最佳解，但至少能產生出一個滿足輸出輸入的量子電路。

## 實驗結果

1. Toffoli gate: 目標小於15個gates  Result: 11
2. Peres gate: 目標小於14個gates  Result: 16
3. Fredkin gate: 目標小於17個gates  Result: 33
4. OR gate: 目標小於17個gates  Result: 13
5. Toffoli with one negative control line gate: 目標小於15個gate  Result: 12

