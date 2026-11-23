 # hust-open-atom-club/.github

  这个仓库只放俱乐部的**组织主页**和**组织级配置**，不放任何项目代码。

  ## 里面有什么

  | 位置 | 作用 | 影响范围 |
  | --- | --- | --- |
  | `profile/README.md` | 组织主页的内容 | 只影响 github.com/hust-open-atom-club |
  | `profile/assets/` | 主页用到的图片 | 只被主页引用 |
  | `.github/FUNDING.yml` | 赞助（Sponsor）按钮配置 | 组织下所有仓库 |
  | `.github/workflows/` | 自动检查（尚未实现，见[#9](https://github.com/hust-open-atom-club/.github/issues/9)） | 只在这个仓库运行 |

  项目自己的 Issue 模板、CI 和开发文档放在对应仓库里，不要放这里。例如仓库创建和转移申请由
  RepositoryManagement 管理： <https://github.com/hust-open-atom-club/RepositoryManagement/issues/new/choose>

  ## 怎么修改

  1. 从 `main` 创建一个分支；
  2. 修改 `profile/README.md`，新增图片放进 `profile/assets/`；
  3. 本地执行 `git diff --check` 检查格式；
  4. 提交并向 `main` 发起 Pull Request，合并后组织主页才会更新。

  Profile 的自动检查由 [#9](https://github.com/hust-open-atom-club/.github/issues/9)负责，目前还没有合入；在此之前请手动确认新增链接可以正常打开。
