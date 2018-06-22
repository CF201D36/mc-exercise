The first big probem came when Carol & Bob pushed changes on a branch and didn't wait for Ted & Alice to approve the changes. The pull requests have to be solid before people attempt to PUSH to branch that ACP'd changes.

The next big problem was that everyone pushed to master instead of their own branch. This led to additional conflicts between North and South :) The resolution to this was to use "git fetch origin" to update our local copy. Then we performed a "git merge" to attempted to weave what was on the Origin Master with what is stored locally. We then performed edits in VSCode to make sure the code reflected the features we were implementing. We then "tested" the code to see if it executed properly.

Once confirmed we did an ACP to the branch origin. The pull request is then able to happen. 

Stray observations: it was harder to create aritifical additional problems than it was to create real problems. Getting all 5 group memebers to follow the "breaking Git" directions simultaneously was challenging. 

