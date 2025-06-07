# 🛒 Website bán hàng nội thất Thiên Ân – Cần Thơ

📌 **Đồ án môn Hệ thống thông tin 1**  
📍 Trường Đại học Kỹ thuật – Công nghệ Cần Thơ (CTUT)  
👨‍🏫 Giảng viên hướng dẫn: TS. Nguyễn Trung Việt

👨‍💻 Nhóm sinh viên thực hiện:  
- Huỳnh Như Ý – HTTT2211015  
- Nguyễn Thành Đạt – HTTT2211003  
- Nguyễn Trần Anh Khoa – HTTT2211026  

---

## 🎯 Mục tiêu của hệ thống

Hệ thống được xây dựng nhằm hỗ trợ Công ty Thiên Ân tại Cần Thơ trong quá trình chuyển đổi từ mô hình kinh doanh truyền thống sang mô hình thương mại điện tử, giúp:

- Tăng khả năng tiếp cận khách hàng tiềm năng.
- Tự động hóa quy trình bán hàng, quản lý đơn hàng và sản phẩm.
- Cung cấp trải nghiệm mua sắm tiện lợi, hiện đại cho khách hàng.

---

## 🧩 Các chức năng chính

### 👤 Quản lý tài khoản
- Đăng nhập/đăng xuất
- Cập nhật thông tin cá nhân
- Phân quyền: Admin, Nhân viên, Khách hàng

### 🛍️ Quản lý sản phẩm
- Thêm, sửa, xóa sản phẩm
- Quản lý danh mục sản phẩm
- Xem chi tiết sản phẩm

### 📦 Quản lý đơn hàng
- Đặt hàng, xác nhận đơn hàng
- Theo dõi tình trạng đơn hàng
- Lịch sử mua hàng

### 🧑‍🤝‍🧑 Quản lý người dùng
- Quản lý thông tin khách hàng
- Quản lý nhân viên bán hàng

### 🏭 Quản lý nhà cung cấp & nhập hàng
- Thêm, sửa, xóa nhà cung cấp
- Ghi nhận lô hàng nhập kho

### 📊 Dashboard & thống kê
- Tổng quan khách hàng, sản phẩm, đơn hàng, doanh thu
- Thống kê sản phẩm sắp hết hàng
- Báo cáo doanh thu theo thời gian

---

## 🛠️ Công nghệ sử dụng

| Thành phần             | Công nghệ                   |
|------------------------|-----------------------------|
| Ngôn ngữ lập trình     | C#, HTML/CSS, JavaScript    |
| Framework chính        | ASP.NET Core MVC            |
| ORM                    | Entity Framework Core       |
| Cơ sở dữ liệu          | Microsoft SQL Server        |
| Thiết kế giao diện     | Razor Pages, Bootstrap      |
| Mô hình hóa            | PlantUML (Use Case, Class)  |

---

## 👥 Đối tượng sử dụng

- **Quản lý cửa hàng (Admin)**: Quản lý toàn bộ hệ thống, nhân viên, sản phẩm, đơn hàng, thống kê.
- **Nhân viên bán hàng**: Quản lý khách hàng, đơn hàng, đặt hàng cho khách.
- **Khách hàng**: Đăng ký tài khoản, duyệt sản phẩm, mua hàng, xem lịch sử.

---

## 💡 Các điểm nổi bật

- 🧠 Ứng dụng mô hình MVC giúp dễ dàng mở rộng và bảo trì.
- 🔐 Phân quyền người dùng rõ ràng theo vai trò.
- 📈 Dashboard thống kê trực quan.
- 🛒 Giao diện thân thiện, hỗ trợ thao tác nhanh gọn.
- 💾 Lưu trữ dữ liệu an toàn với SQL Server.

---

## 📌 Ghi chú

Đây là đồ án học phần Hệ thống thông tin 1, được thực hiện tại Trường Đại học Kỹ thuật – Công nghệ Cần Thơ, nhằm mô phỏng và hiện thực hóa quy trình bán hàng thực tế tại **công ty bán hàng nội thất Thiên Ân – Cần Thơ**.

---

## 📬 Liên hệ

- 👩‍💻 Sinh viên: **Huỳnh Như Ý** – HTTT2211015  
- 📞 Hotline: 0982 147 252  
- 📧 Email: huynhnhuy.tech@gmail.com
- 🔗 GitHub: [https://github.com/NhuYtech](https://github.com/NhuYtech)

---

💻 *Source code hiện đang được phát triển và cập nhật thường xuyên tại:*  
🔗 [https://github.com/NhuYtech/ThienAnFuni_aspnet](https://github.com/NhuYtech/ThienAnFuni_asp.net)

---

# Account:
- `Admin`: 
  - `Username`: `sinoo`
  - `Password`: `123456`

- `SaleStaff 1`:
  - `Username`: `tramanh`
  - `Password`: `123456`

- `Customer 1`:
  - `Username`: `teoemcus`
  - `Password`: `123456`
  
# `Work Assignment`
### Anh Khoa
- Viết báo cáo
- Chọn template Customer + Admin
- Thiết kế Database
- Cắt template: Admin, Shop
- Account: Đăng nhập
- Xây dựng module Admin: POS bán hàng, Nhân viên, Sản phẩm, Nhập hàng, Nhà cung cấp
- Xây dựng module Customer: Shop, Giỏ hàng(Session), Đặt hàng(Send Email)


### Thành Đạt
- Viết báo cáo
- Thiết kế Database
- Cắt template: Trang chủ
- Xây dựng module Admin: Dashboad quản trị, Danh mục sản phẩm
- Xây dựng module Customer: Trang chủ, Đơn hàng(Chi tiết đơn hàng), Liên hệ
- Style UI: Pagination
- Thiết kế UI/UX: Bông tuyết, Panel, Logo 


### Như Ý
- Sửa báo cáo
- Account: Đăng ký, Đổi mật khẩu
- Xây dựng module Admin: Khách hàng
- Xây dựng module Customer: Profile
- Nhập dữ liệu mẫu: Sản phẩm, Đơn hàng
- Chỉnh sửa logic code: Nhân viên, Chi tiết sản phẩm, Chi tiết đơn hàng
- Lấy dữ liệu hình ảnh, Mô tả sản phẩm


# Lần pull đầu tiên
```
- Tạo database thienanFuni
- mở file appsettings.json đổi tên server
```
# Fresh 
```
dotnet ef database drop --force

dotnet ef migrations remove

dotnet ef migrations add InitialCreate

```

### 1. Tạo Dự Án ASP.NET Core 8.0 MVC

### 2. Cài Đặt Thư Viện Identity và setup môi trường như này

- **Identity** giúp bạn quản lý xác thực, phân quyền và đăng nhập/đăng xuất một cách dễ dàng.

   ```powershell
    dotnet add package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore
    dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
    dotnet add package Microsoft.AspNetCore.Identity.UI
    dotnet add package Microsoft.EntityFrameworkCore.Sqlite
    dotnet add package Microsoft.EntityFrameworkCore.SqlServer
    dotnet add package Microsoft.EntityFrameworkCore.Tools
    dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
   ```

### 3. Cấu Hình Database Context

- Tạo **ApplicationDbContext** kế thừa từ `IdentityDbContext` để Identity quản lý cơ sở dữ liệu.

1. **Tạo lớp ApplicationDbContext**:
   ```csharp
   using Microsoft.AspNetCore.Identity;
   using Microsoft.AspNetCore.Identity.EntityFrameworkCore;
   using Microsoft.EntityFrameworkCore;

   public class ApplicationDbContext : IdentityDbContext<User>
   {
       public ApplicationDbContext(DbContextOptions<ApplicationDbContext> options) : base(options) { }

       public DbSet<Manager> Managers { get; set; }
       public DbSet<SaleStaff> SaleStaffs { get; set; }
       public DbSet<Customer> Customers { get; set; }
   }
   ```

2. **Cấu hình chuỗi kết nối trong `appsettings.json`**:
   ```json
   "ConnectionStrings": {
       "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=YourDatabaseName;Trusted_Connection=True;MultipleActiveResultSets=true"
   }
   ```

3. **Thêm ApplicationDbContext vào `Program.cs`**:
   ```csharp
   builder.Services.AddDbContext<ApplicationDbContext>(options =>
       options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection")));

   builder.Services.AddIdentity<User, IdentityRole>()
       .AddEntityFrameworkStores<ApplicationDbContext>()
       .AddDefaultTokenProviders();

   builder.Services.AddControllersWithViews();
   ```

### 4. Cập Nhật Model Người Dùng Với Identity

- Để phù hợp với cấu trúc của Identity, cập nhật các model `User`, `Manager`, `SaleStaff`, và `Customer` theo định nghĩa của bạn ở trên.

### 5. Thiết Lập Bảng Role Cho Người Dùng

- Tạo một `RoleInitializer` để thêm các role cơ bản vào hệ thống khi chạy lần đầu:

   ```csharp
   using Microsoft.AspNetCore.Identity;
   using System.Threading.Tasks;

   public class RoleInitializer
   {
       public static async Task SeedRolesAsync(RoleManager<IdentityRole> roleManager)
       {
           if (!await roleManager.RoleExistsAsync("Manager"))
           {
               await roleManager.CreateAsync(new IdentityRole("Manager"));
           }
           if (!await roleManager.RoleExistsAsync("SaleStaff"))
           {
               await roleManager.CreateAsync(new IdentityRole("SaleStaff"));
           }
           if (!await roleManager.RoleExistsAsync("Customer"))
           {
               await roleManager.CreateAsync(new IdentityRole("Customer"));
           }
       }
   }
   ```

- **Thêm lệnh gọi SeedRoles** trong `Program.cs`:
   ```csharp
   using Microsoft.AspNetCore.Identity;

   var app = builder.Build();

   using (var scope = app.Services.CreateScope())
   {
       var roleManager = scope.ServiceProvider.GetRequiredService<RoleManager<IdentityRole>>();
       await RoleInitializer.SeedRolesAsync(roleManager);
   }
   ```

### 6. Tạo AccountController

Tạo `AccountController` để quản lý các `Action` đăng ký, đăng nhập, và đăng xuất.



### 7. Phân Quyền Cho Các Controller

- Dùng `[Authorize(Roles = "RoleName")]` để phân quyền. Ví dụ:
   ```csharp
   [Authorize(Roles = "Manager")]
   public class AdminController : Controller
   {
       // Chỉ có Manager mới truy cập được
   }

   [Authorize(Roles = "SaleStaff")]
   public class SaleController : Controller
   {
       // Chỉ có SaleStaff mới truy cập được
   }
   ```

### 8. Migrate và Chạy Ứng Dụng (Fresh) ở đầu file

### ====================================================================

# 1. Cách setup send mail (Thủ công)

### **Gửi Email Sau Khi Đặt Hàng Thành Công**  

**Tích hợp gửi email miễn phí bằng SMTP** sử dụng dịch vụ Gmail.  

---

### **Bước 1: Cấu hình dịch vụ gửi email**  

**Thêm cài đặt SMTP trong `appsettings.json`:**  
```json
 "EmailSettings": {
    "SmtpServer": "smtp.gmail.com",
    "SmtpPort": 587,
    "SenderName": "Thiên Ân Store",
    "SenderEmail": "Khoalmht0@gmail.com",
    "SenderPassword": "jfka bvsp wvlp rzlb" (Phần này tạo bằng các bật FA2 và Create Application Password trên tài khoản google)
  }
```

---

### **Bước 2: Đăng ký dịch vụ gửi email trong `Program.cs`**  

```csharp
builder.Services.Configure<EmailSettings>(builder.Configuration.GetSection("EmailSettings"));
builder.Services.AddTransient<ThienAnFuni.Services.IEmailSender, EmailSender>();
```

**Tạo lớp `EmailSettings.cs`:**  
```csharp
public class EmailSettings
{
    public string SmtpServer { get; set; }
    public int SmtpPort { get; set; }
    public string SenderName { get; set; }
    public string SenderEmail { get; set; }
    public string SenderPassword { get; set; }
}
```

**Tạo giao diện `IEmailSender.cs`:**  
```csharp
public interface IEmailSender
{
    Task SendEmailAsync(string toEmail, string subject, string message);
}
```

**Tạo lớp `EmailSender.cs`:**  
```csharp
public class EmailSender : IEmailSender
    {
        private readonly EmailSettings _emailSettings;

        public EmailSender(IOptions<EmailSettings> emailSettings)
        {
            _emailSettings = emailSettings.Value;
        }

        public async Task SendEmailAsync(string toEmail, string subject, string message)
        {
            using (var smtpClient = new SmtpClient(_emailSettings.SmtpServer, _emailSettings.SmtpPort))
            {
                smtpClient.Credentials = new NetworkCredential(
                    _emailSettings.SenderEmail,
                    _emailSettings.SenderPassword
                );

                smtpClient.EnableSsl = true;
                smtpClient.UseDefaultCredentials = false;
                smtpClient.DeliveryMethod = SmtpDeliveryMethod.Network; // Thêm dòng này

                var mailMessage = new MailMessage
                {
                    From = new MailAddress(_emailSettings.SenderEmail, _emailSettings.SenderName),
                    Subject = subject,
                    Body = message,
                    IsBodyHtml = true,
                };

                mailMessage.To.Add(toEmail);

                try
                {
                    await smtpClient.SendMailAsync(mailMessage);
                }
                catch (SmtpException ex)
                {
                    Console.WriteLine($"Lỗi khi gửi email: {ex.Message} - {ex.StatusCode}");
                    Console.WriteLine($"Chi tiết lỗi: {ex.InnerException?.Message}");
                    throw;
                }

            }
        }

    }
```

---

### **Bước 3: Cập Nhật Controller Đặt Hàng**  

**Thêm vào `CheckOutSV`:**  
```csharp
 if (order != null)
            {
                string subject = "💕💕💕 Đặt Hàng Thành Công - Thiên Ân Store 💕💕💕";
                string message = $@"
                <h2>💌Cảm ơn bạn đã đặt hàng tại Thiên Ân Store!💌</h2>
                <p>🎁 Đơn hàng #{order.Id} đã được tạo thành công.</p>
                <p>🎁 Địa chỉ giao hàng: {order.Address}</p>
                <p>🎁 Tổng số lượng: {order.TotalQuantity}</p>
                <p>🎁 Tổng giá: {order.TotalPrice:n0}đ</p>
                <p>Chúng tôi sẽ liên hệ với bạn sớm nhất để giao hàng ❤️.</p>";

                await _emailSender.SendEmailAsync(user.Email, subject, message);
            }
```

---

