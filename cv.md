# CV
## Penina Valeria
## телефон: +375444608544 
## telegram: 
## email: sternviktoria36@gmail.com
*  **Skills**
    * C#
    * HTML
    * CSS
    * Unity

* **About** 

I am passionate about web development and consider it more suitable for myself, I like to learn new material and improve my skills.

* **Code example**

```kotlin
static int GenerateCombinationsHelper(int[] S, int length, int index, int[] currentComb, int startIndex, List<int[]> combinations)
    {
        int flag = 0;
        flag += 1;
        if (index == length)
        {
            int[] comb = new int[length];
            Array.Copy(currentComb, comb, length);
            combinations.Add(comb);
            return flag;
        }
        flag += 2;
        for (int i = startIndex; i < S.Length; i++)
        {
            currentComb[index] = S[i];
            flag += 5;
            flag += GenerateCombinationsHelper(S, length, index + 1, currentComb, i + 1, combinations);
        }
        return flag;
    }
```

* **Courses**
    * _.NET Development_
    * _freeCodeCamp_

* **English level**: B1

* **Picture**

<img src="img/kitty.jpg" width="75%" height="75%" />