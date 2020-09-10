# Linux-命令基础  
练习一：    
      Exercise 1：
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise1.png)
      Exercise 2:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise2.png)
      Exercise 3:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise3.png)
      Exercise 4:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise4.png)
      Exercise 5:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise5.png)
      Exercise 6:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise6.png)
      Exercise 7:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise7.png)
      Exercise 8:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise8.png)
      Exercise 9:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise9.png)
      Exercise 10:
      ![image](https://github.com/yzq327/Linux-/blob/master/exercise10.png)
练习二：
mkdir cli-practice
touch readme.md
cat >> ./readme.md << EOF
Hi there,this is a readme file.
EOF
cat >> ./readme.md <<EOF
This is the second line of the readme file.
EOF
mv readme.md readme.txt
mkdir document
mv readme.txt document/introduction.txt
cp introduction.txt readme.txt
echo The quick brown for jumps over a lazy dog > readme.txt
cp -r document docs
rm -r document
mkdir -p parent/child/docs
cp ~/cli-practice/docs/introduction.txt ~/cli-practioce/parent/child/docs/introduction.txt

