# Java Algoritmaları
LeetCode üzerinde çözdüğüm Java uygulamaları ve veri yapıları çalışmaları.

### 1. Two Sum (İki Toplam)
- **Zorluk:** Kolay
- **Tarih:** 29 Nisan 2026

```java
public int[] twoSum(int[] nums, int target) {
    for (int i = 0; i < nums.length; i++) {
        for (int j = i + 1; j < nums.length; j++) {
            if (nums[i] + nums[j] == target) {
                return new int[] { i, j };
            }
        }
    }
    return new int[] {};
}
