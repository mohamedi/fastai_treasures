
<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#How-to-do-PR-for-Docs-Source" data-toc-modified-id="How-to-do-PR-for-Docs-Source-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>How to do PR for Docs Source</a></span><ul class="toc-item"><li><span><a href="#Step-1-Get-idea-support-from-the-forum" data-toc-modified-id="Step-1-Get-idea-support-from-the-forum-1.1"><span class="toc-item-num">1.1&nbsp;&nbsp;</span>Step 1 Get idea support from the forum</a></span></li><li><span><a href="#Step-2-Fork-and-download-repo" data-toc-modified-id="Step-2-Fork-and-download-repo-1.2"><span class="toc-item-num">1.2&nbsp;&nbsp;</span>Step 2 Fork and download repo</a></span></li><li><span><a href="#Step-3-Sync-your-fork-and-local-repo-with-official-repo" data-toc-modified-id="Step-3-Sync-your-fork-and-local-repo-with-official-repo-1.3"><span class="toc-item-num">1.3&nbsp;&nbsp;</span>Step 3 Sync your fork and local repo with official repo</a></span></li><li><span><a href="#Step-4-delete-and-create-branches" data-toc-modified-id="Step-4-delete-and-create-branches-1.4"><span class="toc-item-num">1.4&nbsp;&nbsp;</span>Step 4 delete and create branches</a></span></li><li><span><a href="#Step-5-Make-your-edits" data-toc-modified-id="Step-5-Make-your-edits-1.5"><span class="toc-item-num">1.5&nbsp;&nbsp;</span>Step 5 Make your edits</a></span></li><li><span><a href="#Step-6-Push-the-changes" data-toc-modified-id="Step-6-Push-the-changes-1.6"><span class="toc-item-num">1.6&nbsp;&nbsp;</span>Step 6 Push the changes</a></span></li><li><span><a href="#Step-7-Make-a-PR" data-toc-modified-id="Step-7-Make-a-PR-1.7"><span class="toc-item-num">1.7&nbsp;&nbsp;</span>Step 7 Make a PR</a></span></li><li><span><a href="#Step-8-Coming-back-to-Documentation-improvements" data-toc-modified-id="Step-8-Coming-back-to-Documentation-improvements-1.8"><span class="toc-item-num">1.8&nbsp;&nbsp;</span>Step 8 Coming back to Documentation improvements</a></span></li></ul></li></ul></div>

# How to do PR for Docs Source

This is a visual guide to do a pull request (PR) on fastai library document source files (ipybn), which will walk you through every step of pushing a PR. 

I learnt to do PR from [fastai PR guides](https://docs.fast.ai/gen_doc_main.html#process-for-contributing-to-the-docs) and [branch update](https://docs.fast.ai/dev/git.html#how-to-keep-your-feature-branch-up-to-date), but more importantly I can't get here without tons of help and support from @stas Stas Bekman on [Documentation improvements](https://forums.fast.ai/t/documentation-improvements/32550). Many thanks to @stas ! This visual guide is one of my little contributions back to fast.ai community.

Before you start, you should first take a few minutes to learn the very basics of terminal and git. You can learn it from [the terminal guide](https://course.fast.ai/terminal_tutorial.html) on fastai course site. Then you are free to move on.

## Step 1 Get idea support from the forum

When you have an idea on PR, please go to [Documentation improvements](https://forums.fast.ai/t/documentation-improvements/32550) to share your thought and get support.

![image.png](PRimages/PR01.png)

## Step 2 Fork and download repo

Click to fork the official repo as shown in the visual instruction below.

![](PRimages/PR00.png)

Then on your fork repo on github, copy the link.

![](PRimages/PR00a.png)

The last step to clone fastai repo to your local computer is to run the following code in your terminal.
```
cd your-fastai-fork-directory
git clone paste-your-copied-link-here
```

## Step 3 Sync your fork and local repo with official repo

First, go to your fork on github to check whether it is updated. If not (seen image below), then you need to sync.

![image.png](PRimages/PR02.png)

Then you can go to your terminal and step into your local repo directory (fastai-fork, in this visual example), and sync your local repo and official repo by following the steps in the image below.
You can sync your repo with official repo using the following codes:
```
cd my-cool-feature # your fastai fork clone directory
git fetch upstream
git checkout master
git merge --no-edit upstream/master
git push --set-upstream origin master
```
See my demo below

![image.png](PRimages/PR03.png)

Then you can go to your fork to see whether the sync is a success or not.

![image.png](PRimages/PR03.5.png)

## Step 4 delete and create branches

If you have done PR before, you may want to delete your previous branch locally and on github. In this example, I have a branch called update-freeze-docsrc (see the blue box in the image below).

![image.png](PRimages/PR04.png)

You can delete this branch locally and on github by following the first four steps in the image below.     
```
git branch # to see which branch you are in
git branch master # make sure to step out of the branch you want to delete
git branch -d branch-you-want-to-delete
git push origin --delete branch-you-want-to-delete
```
see my demo with 'update-freeze-docsrc' as the branch to be deleted.

To create a new branch for your PR, you can run the following code in your terminal
```
git branch your-new-feature-branch
git checkout your-new-feature-branch
git merge origin/master
git push --set-upstream origin your-new-feature-branch 
```
see my demo with 'freeze_to' as the branch to be created.

![image.png](PRimages/PR06.png)

If you refresh the previous branch page on github, it won't be found.

![image.png](PRimages/PR05.png)

Also you will find a new branch created on your fork, see the box below.

![image.png](PRimages/PR07.png)

## Step 5 Make your edits

You can make your edits of documentation and make it public with Kaggle kernels, so that people on Documentation improvement thread can see and give suggestions.

If you finally decided to make it a PR, then you can proceed to copy the changes onto the original ipynb file in your local repo.

![image.png](PRimages/PR08.png)

## Step 6 Push the changes

You can check the changes you made to the original doc source ipynb by running the two lines of codes below.
```
git status
git diff the-file-you-edited
```

![image.png](PRimages/PR09.png)

Then if the changes seem ok, you can run the following three lines of codes to push the changes to your fork.
```
git add .
git commit -a -m 'your message'
git push
```

![image.png](PRimages/PR10.png)

## Step 7 Make a PR

On your fork in github, you can see your push and click the blue box on the right to make a PR.

![image.png](PRimages/PR11.png)

You can also add some notes to your PR.

![image.png](PRimages/PR12.png)

## Step 8 Coming back to Documentation improvements

Finally and optionally, you could come back to the thread for follow-ups, as you may encounter some errors before your PR merged. 

![image.png](PRimages/PR13.png)
