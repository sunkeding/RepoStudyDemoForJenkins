## RepoStudyDemoForJenkins

主仓库 ：https://github.com/sunkeding/RepoStudyDemo.git

子module仓库 ：https://github.com/sunkeding/common_ui.git

子module仓库 ：https://github.com/sunkeding/util.git

## 拉代码

1、cd到项目根目录

2、repo init -u https://github.com/sunkeding/RepoStudyDemo.git --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo

3、repo sync --force-sync

4、repo start master --all

## 发布release版本后对所有仓库打上git tag

1、cd到项目根目录

2、repo -forall -c git tag  release_tag_0.0.1
