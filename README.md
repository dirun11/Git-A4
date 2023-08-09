# Git-A4


Put master.txt on master branch, stage and commit -->
 Create 3 branches: public 1, public 2 and private -->
 Put public1.txt on public 1 branch, stage and commit -->
 Merge public 1 on master branch -->
 Merge public 2 on master branch -->
 Edit master.txt on private branch, stage and commit -->
 Now update branch public 1 and public 2 with new master code in private -->
 Also update new master code on master -->
 Finally update all the code on the private branch -->


 103  mkdir assignment4
  104  ls
  105  cd assignment4
  106  touch master.txt
  107  gti init
  108  git init
  109  git add master.txt
  110  gti commit -m "commiting master.txt"
  111  git commit -m "commiting master.txt"
  112  git branch public1
  113  git branch public2
  114  git branch private
  115  git checkout public1
  116  touch public1.txt
  117  git add public1.txt
  118  git commit -m "commiting public1.txt"
  119  git checkout master
  120  git branch
  121  git merge public1
  122  git merge public2
  123  git checkout master
  124  git checkout private
  125  ls
  126  nano master.txt
  127  git status
  128  git add master.txt
  129  git commit -m "commiting edited master.txt
  130  git commit -m "commiting edited master.txt"
  131  git branch
  132  ls
  133  cat master.txt
  134  git checkout public1
  135  ls
  136  cat master.txt
  137  git checkout public2
  138  git merge private
  139  ls
  140  cat master.txt
  141  ls
  142  cat master.txt
  143  git merge private
  144  cat master.txt
  145  git remote add https://github.com/dirun11/Git-A4.git
  146  git remote add origin https://github.com/dirun11/Git-A4.git
  147  ls
  148  cd
  149  cd assignment4
  150  git remote add origin https://github.com/dirun11/Git-A4.git
  151  git push origin --all
  152  cd
  153  history
