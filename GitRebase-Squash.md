Rebasing allows you to maintain a clean commit history showing the exact chain of development for your product.
After Rebasing you will end up with a unchanged Master branch while the Features brunch will end up with a base identical to the Master brunch and on top of it, it will add the Feature Branch commits.

Example: 
         //MASTER commit1 => commit2 => commit3
 //Feature Branch commitA => commitB

After Branch: 
         //MASTER commit1 => commit2 => commit3
 //Feature Branch commit1 => commit2 => commit3 => commitA => commitB

---------------------------------------------------------------------------------------------------------------------------------------------

 Merging in difference, you can merge all of your commits from a feature branch into a single commit, which can then be added to the end of the main branch.

 Example: 
         //MASTER commit1 => commit2 => commit3
 //Feature Branch commitA => commitB

After Merge: 
         //MASTER commit1 => commit2 => commit3
 //Feature Branch commit1 => commit2 => commit3 => commitA/B