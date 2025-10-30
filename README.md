# How to Customize the Line Height in Markdown Content in .NET MAUI Markdown Viewer

This article explains how to customize the line height of Markdown content rendered in the .NET MAUI [MarkdownViewer](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.SfMarkdownViewer.html) control.

By default, the [MarkdownViewer](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.SfMarkdownViewer.html) applies a standard line height that may not suit all design or readability requirements. While the control offers flexible styling options, adjusting line spacing requires a clear understanding of how Markdown is parsed and rendered within the .NET MAUI framework.

Follow the step-by-step guidance to fine-tune line height using styles, and platform-specific tweaks ensuring consistent layout and improved text legibility across devices.

**Step 1:** Check out this [User Guide documentation]((https://help.syncfusion.com/maui/markdownviewer/gettingstarted)) to add and initialize [MarkdownViewer](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.SfMarkdownViewer.html) control. Use the Source property to load markdown content as a string or from a file path.

**Step 2:** By default, the .NET MAUI [MarkdownViewer](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.SfMarkdownViewer.html) applies a standard line height based on its internal rendering engine and platform-specific text layout. This default spacing is designed to ensure consistent readability across devices, but it may not align with all design requirements especially when integrating Markdown content into custom layouts or branded UI themes.

**Step 3:** While the [SfMarkdownViewer](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.SfMarkdownViewer.html) does not expose a direct **LineHeight** property, you can override the default spacing by applying custom styles using CSS-like rules through the [CssStyleRules](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.MarkdownStyleSettings.html) property in [MarkdownStyleSettings](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.MarkdownViewer.MarkdownStyleSettings.html). These styles target the internal Markdown-rendered elements such as headings, paragraphs, and lists, allowing you to control line height, font size, and spacing with familiar CSS syntax.

**Output:**

![Customized_LineHeight_Demo](https://github.com/user-attachments/assets/1b286962-a6f6-444c-be54-d2b1c9742c75)

## Troubleshooting

**Path too long exception**

If you are facing a "Path too long" exception when building this example project, close Visual Studio and rename the repository to a shorter name before building the project.

Refer to the KB article on [how to customize the line height in markdown content in .NET MAUI Markdown Viewer](https://support.syncfusion.com/agent/kb/21718) for better understanding along with relevant code snippets.
