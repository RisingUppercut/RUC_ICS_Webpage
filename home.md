---
layout: home
title: 主页
nav_order: 1
permalink: /
---
# 操作系统导论Ⅰ
## RUC，2025秋


<div class="staff-grid">
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

### **上课**：周三01-03节；**上机**：周三 11-13节，理工配楼二层

&nbsp;

{: .highlight }
Data_Lab已布置，x月y日截止

# 课表
*以下内容会随课程更新*
{% for module in site.modules %}
{{ module }}
{% endfor %}
