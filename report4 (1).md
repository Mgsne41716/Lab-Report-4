Lab report 4

PeijinLi

A17552769
# 1. Step4: login using ssh
![img.png](img.png)

# 2. Step5: git clone
`git clone git@github.com:Mgsne41716/lab-report4.git`
![img_7.png](img_7.png)

# 3. Step6: run the original code test
I cd into the lab-report4 directory and run the test.sh. But one of the tests failed.

```bash
cd lab-report4/
bash test.sh
```
![img_2.png](img_2.png)

# 4. Step7: modify the source code
Use this command `vim ListExamples.java` to enter into vim.
In order to see the line number, I pressed `esc:set nu` command to show the line number, which helped me to quickly find the position.
Then I pressed `<up><up><down><down>` to move my cursor to the correct line.
Then I pressed "i" key to enter into edit mode. And I change index1 to index2.Then I pressed `esc:wq` to save the change.
![img_3.png](img_3.png)

# 5. Step 8: run the test
Then I rerun the test. `bash test.sh` .
![img_4.png](img_4.png)

# 6. Step9: 
```bash
git add ListExamples.java
git commit -m "fix bug for merge method"
git push
```

![img_8.png](img_8.png)


# 7. Replenishment:
This is how I add my ieng6 machine public key to my Github:
![img_5.png](img_5.png)

