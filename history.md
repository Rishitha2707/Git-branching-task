git clone https://github.com/Rishitha2707/Git-branching-task.git
   37  ls
   38  cd Git-branching-task/
   39  ls
   40  git branch
   41  ls
   42  mv README.md mf1
   43  ls
   44  git add mf1
   45  git commit -m "first file in master"
   46  git tag v0.1
   47  git checkout -b develop
   48  ls
   49  touch df1
   50  git add df1
   51  git commit -m "1st file in develop branch"
   52  touch df2
   53  git add df2
   54  git status
   55  git commit -m "2nd file in develop branch"
   56  touch df3
   57  git add df3
   58  git commit -m "3rd file in develop branch"
   59  ls
   60  git checkout -b feature1
   61  ls
   62  touch ff1
   63  git status
   64  git add ff1
   65  git commit -m "1st file in feature1"
   66  ls
   67  touch ff2
   68  git add ff2
   69  git commit -m "2nd file in feature1"
   70  ls
   71  git checkout develop
   72  ls
   73  git branch
   74  git checkout -b feature2
   75  ls
   76  touch f2f1
   77  git add f2f1
   78  git commit -m "1st-feature 2"
   79  touch f2f2
   80  git add f2f2
   81  git commit -m "2nd file- feature 2"
   82  ls
   83  touch f2f3
   84  git add f2f3
   85  git commit -m "3rd file-feature 2"
   86  ls
   87  git checkout main
   88  git branch
   89  ls
   90  git checkout -b hotfix
   91  ls
   92  touch hf1
   93  ls
   94  git add hf1
   95  git commit -m "1st file- hotfix"
   96  ls
   97  git checkout main
   98  git branch
   99  ls
  100  touch mf2
  101  git add mf2
  102  git commit -m "2nd file - main"
  103  git merge hotfix
  104  git merge hotfix -m "merging hotfix into main"
  105  ls
  106  git tag v0.2
  107  git checkout develop
  108  ls
  109  touch df4
  110  git add df4
  111  git commit -m "4th file- develop""

  112  git status
  113  git commit -m "4th file- develop"
  114  ls
  115  touch df5
  116  git add df5
  117  git commit -m "5th file- develop"
  118  ls
  119  git merge hotfix -m "merging hotfix into develop branch"
  120  ls
  121  touch df6
  122  git add df6
  123  git commit -m "6th file- develop"
  124  ls
  125  git branch
  126  git merge feature2 -m "merging feature2 to develop"
  127  ls
  128  git checkout -b release
  129  ls
  130  touch rf1
  131  git add rf1
  132  git commit -m "1st file - release"
  133  touch rf2
  134  git add rf2
  135  git commit -m "2nd file - release"
  136  ls
  137  git branch
  138  git checkout develop
  139  ls
  140  touch df7
  141  git add df7
  142  git commit -m "7th file - develop"
  143  ls
  144  git checkout release
  145  ls
  146  git checkout develop
  147  ls
  148  git merge release -m "merging release into develop"
  149  ls
  150  git branch
  151  git checkout feature2
  152  ls
  153  git branch
  154  touch f2f4
  155  git add f2f4
  156  git commit -m "4th file - feature 2"
  157  git merge develop -m "merging develop into feature 2"
  158  ls
  159  git branch
  160  ls
  161  touch f2f5
  162  git add f2f5
  163  git commit -m "5th file - feature 2"
  164  touch f2f6
  165  git add f2f6
  166  git commit -m "6th file - feature 2"
  167  ls
  168  git checkout release
  169  ls
  170  touch rf3
  171  git add rf3
  172  git commit -m "3rd file - release"
  173  ls
  174  touch rf4
  175  git add rf4
  176  git commit -m "4th file - release"
  177  ls
  178  git checkout main
  179  ls
  180  git branch
  181  touch mf3
  182  git add mf3
  183  git commit -m "3rd file - main"
  184  ls
  185  git merge release -m "merging release into main"
  186  ls
  187  git tag v1.0
  188  git checkout develop
  189  ls
  190  touch df8
  191  git add df8
  192  git commit -m "8th file - develop"
  193  ls
  194  git merge release -m "merging release into develop"
  195  ls
  196  git checkout feature1
  197  ls
  198  touch ff3
  199  git add ff3
  200  git commit -m "3rd file - feature 1"
  201  ls
  202  touch ff4
  203  git add ff4
  204  git commit -m "4th file - feature 1"
  205  ls
  206  git checkout develop
  207  ls
  208  touch df9
  209  git add df9
  210  git commit -m "9th file - developo"
  211  ls
  212  git merge feature2 -m "merging feature 2 into develop"
  213  ls
  214  git merge feature1 -m "merging feature 1 into develop"
  215  ls
  216  git checkout release
  217  ls
  218  touch rf5
  219  git add rf5
  220  git commit -m "5th file - release"
  221  ls
  222  git branch
  223  git merge develop -m "merging develop into release"
  224  ls
  225  git checkout develop
  226  touch df10
  227  git add df10
  228  git commit -m "10th file - develop"
  229  ls
  230  git merge release -m "merging release into develop"
  231  ls
  232  git checkout release
  233  ls
  234  git branch
  235  git checkout main
  236  touch mf4
  237  git add mf4
  238  git commit -m "4th file - main"
  239  ls
  240  git merge release -m "merging release into main branch"
  241  ls
  242  git push --all
  243  git push --tags

