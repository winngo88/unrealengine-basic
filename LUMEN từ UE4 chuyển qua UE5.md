### Bước 1: Chuyển project từ UE4 sang UE5 bằng cách right click lên file project, chọn Switch Unreal Engine Version... chọn version 5.
### Bước 2: Chuyển Intensity của các loại đèn về giá trị 0.
### Bước 3: Bật Global Illumination bằng cách vào Project Settting, restart lại project.
### Bước 4: Xóa PostProcessVolume
### Bước 5: Chuyển Shading Model của Rèm cửa nếu có từ Unit to Cloth, ngắt kết nối Emissive Color
### Bước 6: Thêm PostProcessVolume, chỉnh Bloom ->Intensity thành giá trị 0.
### Bước 7: Chình tranh, ảnh treo tường bị phai khi nhìn nghiêng: mở chất liệu: Metallic thành 0; Opacity thành 0.1; Refraction thành 1.1; Roughness thành 0.664
### Bước 8: Bật Virtual Shadow Map: Project Setting -> Shadows -> Virtual Shadow Maps; Platform -> Windows -> D3D12 -> Chọn SM6 -> Restart lại project.
