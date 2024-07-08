# Vertion Control Day 2 Lab writen task

## Task No. 4 

1. how to remove the branch locally 
 using the following command 
 >> git branch -d test
 >> git branch -d dev

If the brach has not been merged use the following commane
>> git branch -D test
>> git branch -D dev

2. how to remove the remote branch

>> git push origin --delete div
>> git push origin --delete test


## task No. 5  ==> how to checkout to anouther branch without commiting
1. first step to hide the changes use the following command
>>git stash

2. then checkout normally
>> git checkout test

3. (optional) if we want to apply the changes to the current branch afte checkout
>> git stash apply
