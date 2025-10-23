# Even Squares Sum Calculator

一個計算列表中所有偶數平方和的Python程式。

## 功能

- 計算給定列表中所有偶數的平方和
- 包含完整的測試用例
- 支援空列表和各種邊界情況

## 使用方法

```python
from even_squares_sum import even_squares_sum

# 計算偶數平方和
numbers = [1, 2, 3, 4, 5, 6]
result = even_squares_sum(numbers)
print(f"偶數平方和: {result}")  # 輸出: 56
```

## 測試

直接執行檔案來查看測試結果：

```bash
python even_squares_sum.py
```

## 測試用例

1. `[1, 2, 3, 4, 5, 6]` → 56 (2² + 4² + 6²)
2. `[1, 3, 5, 7]` → 0 (沒有偶數)
3. `[2, 4, 6, 8]` → 120 (2² + 4² + 6² + 8²)
4. `[]` → 0 (空列表)
5. `[0, 1, 2, 3, 4]` → 20 (0² + 2² + 4²)

## 作者

HenryLin0914