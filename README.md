# WPF小作家

2026/11/11

1. **新增 DocumentViewer 視窗**
   - 使用 DocumentViewer 作為文件瀏覽介面。
   - 可以顯示及瀏覽文件內容，方便使用者閱讀文件。

2. **新增開啟文件按鈕**
   - 在 MainWindow 主視窗中新增按鈕。
   - 點擊按鈕後，可以開啟 DocumentViewer 視窗。

3. **新增 RichTextBox 文字編輯區**
   - 在 DocumentViewer 視窗中加入 RichTextBox。
   - 可以顯示文件內容，也能直接輸入及編輯文字。

4. **使用 CommandBinding 實現編輯功能**
   - 透過 CommandBinding 綁定 RichTextBox 的編輯指令。
   - 加入複製、剪下、貼上等基本功能。
   - 讓使用者可以更方便地操作文字。

5. **新增文字格式工具列**
   - 在 EditingToolBar 中加入文字格式按鈕。
   - 提供粗體、斜體、底線及字體顏色等功能。
   - 可以依照使用者需求調整文字外觀。

6. **新增 ColorPicker 顏色選擇器**
   - 使用第三方元件 Extended WPF Toolkit。
   - 加入 ColorPicker 控制項。
   - 讓使用者可以自由選擇文字顏色。

7. **新增字型選擇功能**
   - 使用 ComboBox 顯示不同的字型選項。
   - 使用者可以選擇喜歡的字型。
   - 讓文件呈現不同的文字風格。

8. **新增字體大小選擇功能**
   - 使用 ComboBox 提供不同的字體大小。
   - 使用者可以自行調整文字大小。
   - 讓文件閱讀及編輯更加方便。
