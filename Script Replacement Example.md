-----
Script Replacement
-----

It's possible to replace the scripts of an entire prefab. I will be using School of Chaos as an example.
Here we are taking an Apple (which is the cheapest health food item) and giving it the script of a Present Gift (an item that gives you a random item).

![image](https://user-images.githubusercontent.com/20654859/229583141-1d082415-87a7-4c96-b09d-f6c08e9c6bc8.png)

Open the Monobehavior and go to the Asset Header Edit Tab, you'll notice a field named "m_Script", this is where the HealthItem script is.

![DevXUnityUnpackerMain_VWjR3qkqHV](https://user-images.githubusercontent.com/20654859/229584236-38d9e4ed-f661-4f4f-962b-d8c7bfd7ac67.png)


Double click this and pick any other script from the game. (In our case, we are looking for PresentGift)

![DevXUnityUnpackerMain_8EaxxFCpLs](https://user-images.githubusercontent.com/20654859/229584833-3e46ad0e-c005-490d-932d-ab75d1317180.png)

Save and you're done.

---
What happens in the game now?
---

Everytime you "eat" an Apple, you will receive a random item.

![ezgif com-optimize](https://user-images.githubusercontent.com/20654859/229594871-1984f090-13e3-4fb2-8d19-d9b8d351e5bf.gif)


With this method in mind, you can do many other things in other games.
