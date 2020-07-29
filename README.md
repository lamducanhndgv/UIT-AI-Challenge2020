# AI CHALLENGE BOOTCAMP 2020

## LAB 01
- Có môi trường tương tự như Google Colab cung cấp bởi Amazon, Microsoft, IBM, etc hay không?
    - Microsoft: Azure Notebook
    - Amazon: Amazon Sagemaker
    - IBM: IBM DataPlatform Notebooks
    - Another: Kaggle kernel
- Code của Google Colab lưu ở đâu?
    - Thư mục "Colab Notebooks" trong Google Drive.
- Khi chương trình chạy trên Google Colab cần đọc dữ liệu thì dữ liệu lưu ở đâu?
    - Dữ liệu nên được lưu trên Google để truy cập.
- Khi chương trình chạy trên Google Colab cần đọc dữ liệu từ máy cục bộ (local computer ví dụ như desktop hay laptop của bạn) thì làm thế nào (gợi ý dùng Form)
    - Sử dụng đoạn code sau để upload file lên colab
    ``` 
        from google.colab import files
        uploaded = files.upload()
    ```
- Cách thực thi các Cell trong Google Colab
    - Ctrl + Enter: để chạy cell
    - Shift + Enter: để chạy cell và thêm một cell bên dưới.
- Cách đổi sang máy dùng GPU
    - tab Runtime > Change Runtime type > Hardware accelerator : GPU > SAVE