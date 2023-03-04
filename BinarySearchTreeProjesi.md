## Binary Search Tree Projesi

### Proje 3

> [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- **``Root Node``**: **[7]**
    - ``Step1``: **[5]** *left child of* **7**
    - ``Step2``: **[1]** *left child of* **5**
    - ``Step3``: **[8]** *right child of* **7**
    - ``Step4``: **[3]** *right child of* **1**
    - ``Step5``: **[6]** *right child of* **5**
    - ``Step6``: **[0]** *left child of* **1**
    - ``Step7``: **[9]** *right child of* **7**
    - ``Step8``: **[4]** *left child of* **9**
    - ``Step9``: **[2]** *left child of* **4**


```
                         7
                       /   \
                      5     8
                     / \     \
                    1   6     9
                   / \         \
                  0   3         4
                             /
                            2

```