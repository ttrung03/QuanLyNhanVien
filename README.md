# QuanLyNhanVien

# Cấu trúc dự án
| 📁 Thư mục        | Mô tả                                                                       |
| ----------------- | --------------------------------------------------------------------------- |
| `Controllers/`    | Nơi viết các controller như `EmployeeController.cs`, `AuthController.cs`    |
| `Models/`         | Chứa các entity như `Employee.cs`, `Department.cs`,...                      |
| `DTOs/`           | Các class DTO cho input/output như `CreateEmployeeDto.cs`, `EmployeeDto.cs` |
| `Repositories/`   | Xử lý thao tác với DB: `IEmployeeRepository`, `EmployeeRepository`          |
| `Services/`       | Chứa nghiệp vụ xử lý như `EmployeeService`, `AuthService`                   |
| `Data/`           | DbContext + các file SeedData hoặc Migrations                               |
| `Helpers/`        | Các hàm tiện ích như JWT helper, Token generator, pagination logic          |
| `Middleware/`     | Custom middleware như xử lý exception toàn cục                              |
| `Configurations/` | Extension method cho DI, AutoMapper, Swagger...                             |
