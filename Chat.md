---
title: ChatToChange
parent: Home
layout: home
nav_order: 4
---

# Interface

![Main Odoo AI Studio workspace](https://openerp-hk-t.github.io/odoo-tool/images/ui_design_kit.png)

*Figure 1. Main Odoo AI Studio workspace and functional areas.*

| **No.** | **Area**                       | **Purpose**                                                                                                                              |
|---------|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | Prototype command bar          | Creates a new prototype, enables annotation mode, changes language, saves versions, confirms the design, and opens confirmed prototypes. |
| 2       | Requirement Session navigation | Creates and searches conversations and lets the user reopen a recent requirement session.                                                |
| 3       | AI requirement chat            | Accepts natural-language requests and sends them to the AI agent to update or explain the current prototype.                             |
| 4       | Prototype canvas               | Displays the generated Odoo form, list, tabs, records, buttons, workflow status, and other UI elements.                                  |
| 5       | Annotation card                | Stores a requirement linked to a numbered marker placed on the prototype.                                                                |
| 6       | Prototype Versions             | Shows the current draft and saved revisions for comparison, recovery, and confirmation.                                                  |

## Top command bar

![Studio Menu](https://openerp-hk-t.github.io/odoo-tool/images/ui_design_kit_menu.png)


| **Control**               | **Typical use**                                                                                                       |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------|
| New Prototype             | Start a separate prototype or requirement case.                                                                       |
| Annotate                  | Enter annotation mode and place requirement markers on the UI.                                                        |
| Language selector         | Switch the interface or working language where supported.                                                             |
| Save Version              | Create a recoverable snapshot of the current prototype and requirements.                                              |
| Save as Confirmed         | Mark the reviewed state as the approved design baseline.                                                              |
| View Confirmed Prototypes | Open previously approved prototypes.                                                                                  |
| Send to Chat              | Send selected interface context or annotations to the AI conversation for interpretation or specification generation. |

### agent对话


功能说明：增加字段，用于保存需要以数值形式录入或参与统计的业务数据；字段将自动出现在表单对应位置，并保持与现有字段一致的样式与布局。

提问示例：Add a number field after the Role field.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/add_number_field.png)

功能说明：按钮新增，用于触发与该标签页相关的扩展操作；按钮位置、名称和点击行为需在原型中清晰呈现，便于后续绑定具体业务逻辑。

提问示例：Add a button named "odoo" after the Email tab.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/add_odoo_button.png)

功能说明：允许 agent 自主判断是否接受本次修改，并自行调整需求。

提问示例：You may choose whether to accept this modification and adjust requirements on your own.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/agent_autonomy_decision.png)

功能说明：调整按钮的视觉样式，可通过agent对话对按钮的底色和字体颜色进行修改，使按钮在界面中具有明确区分度；该样式修改仅作用于按钮外观，不影响按钮位置和功能。

提问示例：Change the background color of the odoo button to pink and the font color to black.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/odoo_button_pink_black_style.png)

功能说明：修改字段字体颜色，可通过与agent对话实现对 Form fields 或 Detail table 中的字段颜色进行自动化修改，使得画面更加美观，修改过程可自主选择修改对象，保证修改的准确性。

提问示例：Change the font color of Role to dark blue.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/role_font_color_dark_blue_1.png)

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/role_font_color_dark_blue_2.png)

功能说明：调整字段的字体大小，改变字段在界面中的显示比例，使关键字段更加醒目。

提问示例：Set the font size of Role to 5.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/role_font_size_5.png)

功能说明：在界面框体的右下角新增统计计数器，用于实时展示汇总数量或关键统计指标；计数器样式与位置需保持稳定，便于用户快速查看统计结果。

提问示例：Add a statistical counter at the bottom right of the box.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/statistical_counter.png)

功能说明：在界面顶部新增状态栏，用于展示当前页面或数据的状态信息，如加载状态、记录数量、操作提示等；状态栏应保持固定位置，不影响主内容区域布局。

提问示例：Add a status bar.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/status_bar_1.png)

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/status_bar_2.png)

功能说明：调整 Detail 表格中字段列的显示顺序，使表格字段顺序更符合业务使用习惯；该修改仅影响列顺序，不改变字段内容与数据。

提问示例：Move the Email field column in Detail after the Role field column.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/detail_email_after_role_1.png)

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/detail_email_after_role_2.png)

功能说明：在 Detail 表格的数据行下方新增统计行，用于汇总展示各列数据的合计或统计结果；统计行随数据动态更新，并与其他数据行在样式上清晰区分。

提问示例：Add a statistics row below the data rows in Detail.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/detail_statistics_row_1.png)

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/detail_statistics_row_2.png)

功能说明：修改 Detail 表格中字段和对应数据项整列的颜色，用于突出显示该列内容或标记重点关注数据；该修改仅影响列颜色，不影响字段值及表格结构。

提问示例：Change the color of the Role field column in Detail to red.

效果图：

![效果图](https://openerp-hk-t.github.io/odoo-tool/images/detail_role_column_red.png)
