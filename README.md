App demo chức năng lựa chọn món ăn và xác nhận, sử dụng viewmodel và livedata để lưu trữ và quan sát dữ liệu các món và trạng thái checkbox.
Cấu trúc: 1 Activity tổng chứa NavHostFragment để quản lí 5 Fragment khác, 1 nav_graph để quản lí thông tin điều hướng các fragment( chứa name, id, và action)
4 fragment MainDish, SideDish,Dessert,Beverage là các màn chứa danh sách món.
-> Fragemnt cuối cùng là SelectedFood hiển thị list được tích chọn checkbox.
