# Vastopolis Epidemic Analysis - AIT2006-1-2.4

[Tiếng Việt](#tiếng-việt) | [English](#english)

---

## Tiếng Việt

### Cấu trúc thư mục

```
├── raw/                    # Chứa dữ liệu thô
├── processed/              # Chứa dữ liệu đã làm sạch và các bảng thống kê
├── figures/                # Chứa các biểu đồ kết quả (.png)
├── reports/                # Chứa báo cáo PDF và file LaTeX
├── src/                    # Mã nguồn chính
├── requirements.txt        # Các thư viện cần thiết
└── README.md               # Hướng dẫn sử dụng
```

### Yêu cầu hệ thống

- Python: 3.13
- Môi trường: miniconda
- Các thư viện được liệt kê trong `requirements.txt`

### Hướng dẫn chạy lại (Reproducibility)

**Bước 1:** Cài đặt thư viện

```bash
pip install -r requirements.txt
```

**Bước 2:** Chạy các notebook trong thư mục `src/` theo thứ tự sau để tái tạo kết quả:

1. `2_data_cleaning.ipynb`: Đọc dữ liệu thô, làm sạch và chuẩn hóa văn bản.
2. `3_aggregate_data.ipynb`: Nối dữ liệu thời tiết, thống kê từ khóa theo giờ.
3. `4_visualize_data.ipynb`: Vẽ bản đồ và các biểu đồ phân tích.
4. `main_data_visual.ipynb`: Các biểu đồ phân tích nâng cao.

### Kết quả chính

- Báo cáo chi tiết: `reports/report-AIT2006-1-2.4.pdf`
- Commit hash bản nộp: `0c78b600ddd393c869c3a4f76f0983ba6f702fc5`

---

## English

### Folder Structure

```
├── raw/                    # Raw data
├── processed/              # Cleaned data and summary tables
├── figures/                # Output charts (.png)
├── reports/                # PDF reports and LaTeX files
├── src/                    # Main source notebooks
├── requirements.txt        # Required dependencies
└── README.md               # Usage guide
```

### System Requirements

- Python: 3.13
- Environment: miniconda
- Dependencies listed in `requirements.txt`

### Reproducibility Guide

**Step 1:** Install dependencies

```bash
pip install -r requirements.txt
```

**Step 2:** Run notebooks in `src/` in this order:

1. `2_data_cleaning.ipynb`: Load raw data, clean it, and normalize text.
2. `3_aggregate_data.ipynb`: Merge weather data and compute hourly keyword statistics.
3. `4_visualize_data.ipynb`: Generate maps and analysis charts.
4. `main_data_visual.ipynb`: Advanced analysis visualizations.

### Main Outputs

- Detailed report: `reports/report-AIT2006-1-2.4.pdf`
- Submission commit hash: `0c78b600ddd393c869c3a4f76f0983ba6f702fc5`
