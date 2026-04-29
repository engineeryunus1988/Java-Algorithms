/**
 * Problem: 1. Two Sum (LeetCode)
 * Çözüm Tarihi: 29 Nisan 2026
 * Zorluk: Kolay
 */
# Java-Algorithms
LeetCode üzerinde çözdüğüm Java algoritmaları ve veri yapıları çalışmaları.
/**
 * @author engineer-yunus (Senin GitHub adın)
 * @description LeetCode - 1. Two Sum Cozumu
 * @date 2026-04-29
 */
public class Solution {
    //class Solution {
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
}
