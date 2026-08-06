---
title: ChatToChange
parent: Home
layout: home
nav_order: 4
---

### Examples:


Functionality: Adds a field to store business data that requires numerical input or is used in statistical analysis; the field automatically appears in the corresponding position on the form, maintaining the same style and layout as existing fields.

Example question: Add a number field after the Role field.

Screenshot:

![demo1](https://openerp-hk-t.github.io/odoo-tool/images/add_number_field.png)

Functional Description: A new button is being added to trigger extension operations related to the current tab. The button's position, label, and click behavior must be clearly defined in the prototype to facilitate the subsequent binding of specific business logic.

Example question: Add a button named "odoo" after the Email tab.

Screenshot:

![demo2](https://openerp-hk-t.github.io/odoo-tool/images/add_odoo_button.png)

Function Description: Allows agents to independently determine whether to accept this modification and adjust their requirements accordingly.

Example Question: You may choose whether to accept this modification and adjust requirements on your own.

Screenshot:

![demo3](https://openerp-hk-t.github.io/odoo-tool/images/agent_autonomy_decision.png)

Functionality: Adjusts the visual style of the button. You can modify the button's background and font colors via the agent chat to ensure it stands out clearly within the interface. These style changes affect only the button's appearance; its position and functionality remain unchanged.

Example prompt: Change the background color of the Odoo button to pink and the font color to black.

Screenshot:

![demo4](https://openerp-hk-t.github.io/odoo-tool/images/odoo_button_pink_black_style.png)

Functionality: Modify field font colors. You can automatically change the color of fields in forms or detail tables by interacting with the agent, resulting in a more visually appealing interface. You can select specific targets for modification, ensuring accuracy.

Example prompt: Change the font color of Role to dark blue.

Screenshot:

![demo5](https://openerp-hk-t.github.io/odoo-tool/images/role_font_color_dark_blue_1.png)

![demo6](https://openerp-hk-t.github.io/odoo-tool/images/role_font_color_dark_blue_2.png)

Function Description: Adjust the font size of a field and change its display scale within the interface to make key fields stand out.

Example Query: Set the font size of Role to 5.

Screenshot:

![demo7](https://openerp-hk-t.github.io/odoo-tool/images/role_font_size_5.png)

Function Description: Add a statistical counter to the bottom right corner of the interface frame to display the total quantity or key statistical indicators in real time. The counter's style and position should remain stable for easy user viewing of statistical results.

Example Question: Add a statistical counter at the bottom right of the box.

Screenshot:

![demo8](https://openerp-hk-t.github.io/odoo-tool/images/statistical_counter.png)

Functional Description: Add a status bar at the top of the interface to display status information for the current page or data—such as loading status, record counts, or operation prompts. The status bar should remain in a fixed position and not affect the layout of the main content area.

Example Query: Add a status bar.

Screenshot:

![demo9](https://openerp-hk-t.github.io/odoo-tool/images/status_bar_1.png)

![demo10](https://openerp-hk-t.github.io/odoo-tool/images/status_bar_2.png)

Function Description: Adjusts the display order of columns in the Detail table to better align with business workflows; this change affects only the column order and does not alter field content or data.

Example Query: Move the Email field column in Detail after the Role field column.

Screenshot:

![demo11](https://openerp-hk-t.github.io/odoo-tool/images/detail_email_after_role_1.png)

![demo12](https://openerp-hk-t.github.io/odoo-tool/images/detail_email_after_role_2.png)

Function Description: Adds a statistics row below the data rows in the Detail table to summarize and display the totals or statistical results of the data in each column. The statistics row updates dynamically with the data and is clearly distinguishable in style from other data rows.

Example Question: Add a statistics row below the data rows in Detail.

Screenshot:

![demo13](https://openerp-hk-t.github.io/odoo-tool/images/detail_statistics_row_1.png)

![demo14](https://openerp-hk-t.github.io/odoo-tool/images/detail_statistics_row_2.png)

Function Description: Changes the color of an entire column (including the field header and corresponding data items) in the Detail table to highlight the column's content or mark key data; this modification affects only the column color and does not alter field values ​​or the table structure.

Example Query: Change the color of the Role field column in Detail to red.

Screenshot:

![demo15](https://openerp-hk-t.github.io/odoo-tool/images/detail_role_column_red.png)
