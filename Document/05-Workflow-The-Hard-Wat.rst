Workflow the Hard Way
==============================================================================


集中式工作流
------------------------------------------------------------------------------

- 所有人都在Master分支上工作.
- 适合只有一个开发者的项目.


功能分支工作流
------------------------------------------------------------------------------

- 每个人在不同的分支上为不同的功能特性工作.
- 使用Pull Request进行Code Review和讨论.
- 功能开发完成通过后Merge到Master分支.
- 非常灵活, 适合中小型团队.


Gitflow工作流
------------------------------------------------------------------------------

- Gitflow工作流 = Master + Hotfix + Release + Develop + 功能分支工作流.
- 所有的功能分支都是从Develop分支上分出去的.
- 更加严谨, 适合大型项目, 比如Python项目本身.


Forking工作流
------------------------------------------------------------------------------

- 只有代码维护者能够Push到正式仓库.
- 代码贡献者只能Fork一个镜像, 在贡献者自己的镜像上开发后, 提交给代码维护者要求Merge到正式仓库.
- 常用于开源项目, 能接受不信任贡献者的提交.


Reference
------------------------------------------------------------------------------

- Git Workflow Tutorial 中文: https://github.com/xirong/my-git/blob/master/git-workflow-tutorial.md
- Comparing Workflows: https://www.atlassian.com/git/tutorials/comparing-workflows
- Comparing Workflows 翻译: https://github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/README.md