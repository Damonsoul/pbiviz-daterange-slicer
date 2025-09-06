<p align="center">
  <strong><a href="#english-version">English</a></strong> | <strong><a href="#chinese-version">中文</a></strong>
</p>

---



#  <a name="english-version"></a> Date Range Slicer for Power BI

![License](https://img.shields.io/badge/license-MIT-blue.svg)[![Latest Release](https://img.shields.io/github/v/release/Damonsoul/pbiviz-daterange-slicer)](https://github.com/Damonsoul/pbiviz-daterange-slicer/releases)

A simple, intuitive, and highly customizable date range slicer visual for Microsoft Power BI. This visual allows users to easily filter their reports by selecting a start and end date from calendar inputs.

![Screenshot of the Visual](https://raw.githubusercontent.com/Damonsoul/pbiviz-daterange-slicer/main/assets/DateRangeSlicer_screenshot.png) 


## ✨ Features

*   **Intuitive Date Selection**: Provides separate input fields for start and end dates, complete with familiar calendar pop-ups.
*   **One-Click Clear Filter**: A convenient button appears on hover to instantly clear the date filter and reset to the full range.
*   **Dynamic Default Dates**: Set a default start date, end date, or both using measures, allowing for dynamic filtering based on your data model (e.g., show the last 30 days by default).
*   **Fully Customizable Appearance**:
    *   **Header**: Toggle visibility, customize the title text, font color, and text size.
    *   **Date Inputs**: Control the font color, text size, background color, and border color to match your report's theme.
*   **Accessibility Ready**: Supports Power BI's high-contrast modes for better readability.
*   **Localized**: Available in English and Chinese (中文).

## 🚀 How to Use

1.  **Download**: Go to the [Releases page](https://github.com/Damonsoul/pbiviz-daterange-slicer/releases) and download the latest `.pbiviz` file.
2.  **Import**: In Power BI Desktop, go to the Visualizations pane, click the `...` icon, and select `Import a visual from a file`. Select the downloaded `.pbiviz` file.
3.  **Add to Report**: Click the new Date Range Slicer icon in your Visualizations pane to add it to your report.

### Data Roles

| Field              | Required | Description                                                                                             |
| ------------------ | :------: | ------------------------------------------------------------------------------------------------------- |
| **Category**       | **Yes**  | Drag and drop the date column from your data model that you want to filter.                             |
| **Default Start Date** |    No    | An optional measure that returns a single date value to be used as the default start date.              |
| **Default End Date** |    No    | An optional measure that returns a single date value to be used as the default end date.                |

## 🎨 Formatting Options

You can customize the visual extensively through the Formatting Pane:

*   **Header**: Settings for the slicer's main title.
*   **Date Inputs**: Settings for the appearance of the two date input boxes.

## 👨‍💻 About the Author

This visual is developed and maintained by **Damon Chen**. I provide professional services in the data analytics space, including:

*   Custom Power BI Visual Development
*   Power BI Consulting & Report Building
*   Corporate Power BI Training
*   General Data Analytics Solutions

Feel free to reach out for collaboration or inquiries:

*   **wechat**: 
    ![wechat](https://raw.githubusercontent.com/Damonsoul/pbiviz-daterange-slicer/main/assets/wechat.jpg.png)
*   **GitHub**: [@Damonsoul](https://github.com/Damonsoul)
*   **Bilibili**: [Space](https://m.bilibili.com/space/217497711)
*   **Email**: `chenmaowei96@gmail.com`



## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---




# <a name="chinese-version"></a> Power BI 日期范围切片器

![License](https://img.shields.io/badge/license-MIT-blue.svg)
[![Latest Release](https://img.shields.io/github/v/release/Damonsoul/pbiviz-daterange-slicer)](https://github.com/Damonsoul/pbiviz-daterange-slicer/releases)

一个为 Microsoft Power BI 设计的简单、直观且高度可定制的日期范围切片器视觉对象。该视觉对象允许用户通过日历输入框轻松地选择开始和结束日期，从而对报告进行筛选。

![视觉对象截图](https://raw.githubusercontent.com/Damonsoul/pbiviz-daterange-slicer/main/assets/DateRangeSlicer_screenshot.png)


## ✨ 功能特性

*   **直观的日期选择**: 提供独立的开始日期和结束日期输入框，并配有用户熟悉的日历弹出窗口。
*   **一键清除筛选**: 鼠标悬停时会出现一个便捷的清除按钮，可立即清除日期筛选并恢复到完整范围。
*   **动态默认日期**: 可通过度量值设置默认的开始日期、结束日期或两者，从而实现基于数据模型的动态筛选（例如：默认显示最近30天）。
*   **完全可定制的外观**:
    *   **标题**: 可切换可见性、自定义标题文本、字体颜色和大小。
    *   **日期输入框**: 可控制字体颜色、文本大小、背景颜色和边框颜色，以匹配您报告的主题。

*   **辅助功能支持**: 支持 Power BI 的高对比度模式，以获得更好的可读性。
*   **本地化**: 支持英语 (English) 和中文 (中文)。

## 🚀 如何使用

1.  **下载**: 前往 [Releases 页面](https://github.com/Damonsoul/pbiviz-daterange-slicer/releases) 并下载最新的 `.pbiviz` 文件。
2.  **导入**: 在 Power BI Desktop 中，前往“可视化”窗格，点击 `...` 图标，然后选择 `从文件导入视觉对象`。选择已下载的 `.pbiviz` 文件。
3.  **添加到报告**: 在您的“可视化”窗格中点击新的“日期范围切片器”图标，将其添加到报告中。

### 数据角色

| 字段           | 是否必需 | 描述                                                                    |
| -------------- | :------: | ----------------------------------------------------------------------- |
| **类别**       | **是**   | 拖入您数据模型中希望用于筛选的日期列。                                  |
| **默认开始日期** |    否    | (可选) 一个返回单个日期值的度量值，用作切片器的默认开始日期。             |
| **默认结束日期** |    否    | (可选) 一个返回单个日期值的度量值，用作切片器的默认结束日期。             |

## 🎨 格式化选项

您可以通过“格式化”窗格对视觉对象进行深度定制：

*   **标题 (Header)**: 设置切片器主标题的样式。
*   **日期输入框 (Date Inputs)**: 设置两个日期输入框的外观。

## 👨‍💻 关于作者

本视觉对象由 **Damon Chen** 开发和维护。我专注于在数据分析领域提供专业服务，包括：

*   Power BI 自定义视觉对象开发
*   Power BI 咨询与报表构建
*   企业 Power BI 培训
*   通用数据分析解决方案

欢迎通过以下方式联系我进行合作或咨询：

*   **微信公众号**: 
    ![微信公众号](https://raw.githubusercontent.com/Damonsoul/pbiviz-daterange-slicer/main/assets/wechat.jpg.png)
*   **GitHub**: [@Damonsoul](https://github.com/Damonsoul)
*   **Bilibili**: [个人空间](https://m.bilibili.com/space/217497711)
*   **邮箱**: `chenmaowei96@gmail.com`



## 📄 许可证

本项目基于 MIT 许可证。详情请参阅 [LICENSE](LICENSE) 文件。