---
title: 更正您的信息以获得更好的贡献
---

通过 Issue、评论、Pull Request 等方式为 [karmada-io](https://github.com/karmada-io) 做出贡献后，
您可以在[此处](https://karmada.devstats.cncf.io/d/66/developer-activity-counts-by-companies)查看您的贡献。

如果您发现公司栏中的信息不正确或为空白，我们强烈建议您进行更正。

例如，应使用 `Huawei Technologies Co. Ltd` 而不是 `HUAWEI`：
![错误信息](../resources/contributor/contributions_list.png)

以下是解决此问题的步骤。

## 在 CNCF 系统中验证您的组织 {##verify-your-organization-in-the-cncf-system}

首先，访问您的个人资料[页面](https://openprofile.dev/edit/profile)并确保您的组织准确无误。
![组织信息检查](../resources/contributor/organization_check.png)

* 如果组织不正确，请选择正确的组织。
* 如果您的组织不在列表中，请单击**添加**以添加您的组织。

## 更新用于计算贡献的 CNCF 存储库 {#update-the-cncf-repository-used-for-calculating-your-contributions}

当您在 CNCF 系统中验证您的组织后，您必须在 gitdm 中创建更新的从属关系的 Pull Request。
为此，您需要修改两个文件：`company_developers*.txt` 和 `developers_affiliations*.txt`。
作为参考，请参阅此 Pull Request 示例：[PR 示例](https://github.com/cncf/gitdm/pull/1257)。

成功合并 Pull Request 后，最长可能需要四个星期的时间才能完成同步更改。
