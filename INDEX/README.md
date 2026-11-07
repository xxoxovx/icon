# INDEX（图片索引）

`image-index.csv` 是图片素材库的逐文件属性清单。

字段说明：
- `file_name`：英文文件名。
- `relative_path`：仓库内相对路径。
- `format`：图片格式。
- `aspect_ratio`：归档宽高比。
- `width_px`、`height_px`：实际像素宽高。
- `resolution_bucket`：长边分辨率目录。
- `mime_type`：MIME 类型。
- `image_type`：位图、矢量图或动画图像。
- `file_size_bytes`：文件大小（Byte）。
- `blob_sha`：Git Blob SHA，可用于核对内容。
- `notes`：备注。

每次新增、删除、移动或替换图片，都必须同步更新 CSV。
