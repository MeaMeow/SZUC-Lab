# 协作规范

## 1. 任务文件夹创建  
每次任务我将新建一个文件夹，文件夹名为本次任务名称。例如，任务名称为“状态条渲染”，则文件夹名应为“Bar Render”。

## 2. 环境配置文件  
在任务文件夹的根目录下，我会提前放置以下两个文件来指定开发环境：
- `build.gradle`
- `gradle.properties`

请各位拉取到本地后以此为环境标准开始任务。

## 3. 个人文件夹命名及内容  
每位开发人员应在任务文件夹（例如“Bar Render”）内创建以自己ID命名的子文件夹。在该文件夹中只需包含`src`文件夹，用于存放代码和资源。

## 4. 提交流程
- 完成任务后，准备好本地 Git 仓库文件结构。
- 将更改推送至个人克隆的仓库中。
- 创建 Pull Request（PR）申请，PR 标题格式为：  
  `[任务名称] 你的ID`

## 5. 仓库同步  
注意保持克隆仓库与主仓库的同步，在主仓库更新时及时拉取更新。