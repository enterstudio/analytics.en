---
description: When you schedule a report, you can choose a publishing list to use for distribution.
seo-description: When you schedule a report, you can choose a publishing list to use for distribution.
seo-title: Allow Publishing List Overrides
solution: Analytics
title: Allow Publishing List Overrides
topic: Report builder
uuid: cad3ab27-56ec-4605-98f3-8e4bdc1b8178
index: y
internal: n
snippet: y
---

# Allow Publishing List Overrides

When you schedule a report, you can choose a publishing list to use for distribution.

Publishing lists are set up in Analytics Admin tools.

See [Publishing List Manager](http://marketing.adobe.com/resources/help/en_US/reference/index.html?f=publishing_list) in the Analytics Reference.

To enable this feature, navigate to the [!UICONTROL Request Wizard: Step 1] window.

If you enable [!UICONTROL Allow Publishing List Override], the report suite assigned to each recipient in the publishing list replaces the report suite for this request. In addition, if the workbook contains several report suites, the report suite ID associated to the publishing list is used.

This option is not available for report suites that you select from cells.

>[!NOTE]
>
>If you send the scheduled report to multiple publishing lists, the report runs once for each list. Variable report suites are replaced by the report suite assigned to the publishing list.
