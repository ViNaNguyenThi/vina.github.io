# Portfolio Website - Web Developer & Tester

Một portfolio website hiện đại và responsive được xây dựng bằng ASP.NET Core MVC, HTML, CSS và JavaScript.

## 🚀 Tính năng

### Frontend
- **Responsive Design**: Tương thích với mọi thiết bị
- **Modern UI/UX**: Thiết kế hiện đại với animations mượt mà
- **Interactive Elements**: Hover effects, smooth scrolling, mobile menu
- **Contact Form**: Form liên hệ với validation và AJAX submission
- **Portfolio Sections**: Hero, About, Skills, Projects, Experience, Contact

### Backend
- **ASP.NET Core MVC**: Framework backend mạnh mẽ
- **Contact Form Processing**: Xử lý form liên hệ
- **Static File Serving**: Phục vụ CSS, JS và assets
- **RESTful API**: Endpoint cho contact form

## 🛠️ Công nghệ sử dụng

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern styling với Flexbox và Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Poppins)

### Backend
- **ASP.NET Core 8.0**: Web framework
- **C#**: Programming language
- **MVC Pattern**: Architecture pattern

## 📁 Cấu trúc dự án

```
PORTFOLIO/
├── Controllers/
│   └── HomeController.cs          # Main controller
├── Models/
│   └── ErrorViewModel.cs          # Error model
├── Views/
│   ├── Home/
│   │   ├── Index.cshtml          # Main portfolio page
│   │   ├── About.cshtml          # About page
│   │   └── Privacy.cshtml        # Privacy page
│   └── Shared/
│       └── _Layout.cshtml        # Main layout
├── wwwroot/
│   ├── css/
│   │   ├── site.css              # Default styles
│   │   └── portfolio.css         # Portfolio styles
│   └── js/
│       ├── site.js               # Default scripts
│       └── portfolio.js          # Portfolio scripts
├── Program.cs                     # Application entry point
└── PORTFOLIO.csproj              # Project file
```

## 🎨 Sections trong Portfolio

### 1. Hero Section
- Giới thiệu cá nhân
- Call-to-action buttons
- Profile card với thông tin chính

### 2. About Section
- Thông tin chi tiết về bản thân
- Statistics (kinh nghiệm, dự án, satisfaction)
- Skills overview

### 3. Skills Section
- **Frontend Development**: HTML5, CSS3, JavaScript, React, Bootstrap
- **Backend Development**: Node.js, Python, SQL, .NET
- **Testing & Tools**: Manual Testing, Automation, Git, Postman

### 4. Projects Section
- Showcase các dự án đã làm
- Technology tags
- Live demo và GitHub links

### 5. Experience Section
- Timeline của kinh nghiệm làm việc
- Responsive timeline design
- Chi tiết công việc và thành tựu

### 6. Contact Section
- Contact information
- Contact form với validation
- Social media links

## 🚀 Cách chạy dự án

### Yêu cầu hệ thống
- .NET 8.0 SDK
- Visual Studio 2022 hoặc VS Code
- Git

### Các bước thực hiện

1. **Clone repository**
   ```bash
   git clone <repository-url>
   cd PORTFOLIO
   ```

2. **Restore dependencies**
   ```bash
   dotnet restore
   ```

3. **Build project**
   ```bash
   dotnet build
   ```

4. **Run application**
   ```bash
   dotnet run
   ```

5. **Truy cập website**
   - Mở trình duyệt
   - Truy cập: `https://localhost:7001` hoặc `http://localhost:5000`

## 📝 Tùy chỉnh Portfolio

### 1. Thay đổi thông tin cá nhân
- Cập nhật tên trong `Views/Home/Index.cshtml`
- Thay đổi email, phone, location trong contact section
- Cập nhật social media links

### 2. Thêm/Sửa Projects
- Chỉnh sửa project cards trong `Views/Home/Index.cshtml`
- Thêm project images vào `wwwroot/images/`
- Cập nhật technology tags

### 3. Cập nhật Skills
- Thêm/bớt skills trong skills section
- Thay đổi icons từ Font Awesome
- Cập nhật skill categories

### 4. Tùy chỉnh Styling
- Chỉnh sửa colors trong `wwwroot/css/portfolio.css`
- Thay đổi fonts trong CSS
- Cập nhật animations

### 5. Backend Customization
- Thêm database connection trong `HomeController.cs`
- Implement email sending cho contact form
- Thêm authentication nếu cần

## 🎯 Tính năng JavaScript

### Interactive Features
- **Mobile Menu**: Hamburger menu cho mobile
- **Smooth Scrolling**: Navigation links scroll mượt mà
- **Form Validation**: Client-side validation cho contact form
- **Notifications**: Toast notifications cho form submission
- **Animations**: Fade-in animations khi scroll
- **Counter Animation**: Animated counters cho statistics
- **Scroll to Top**: Button scroll to top
- **Active Navigation**: Highlight active section

### Performance Optimizations
- **Lazy Loading**: Images và content
- **Intersection Observer**: Efficient scroll animations
- **Debounced Events**: Optimized scroll handlers
- **Minified Assets**: Production-ready assets

## 📱 Responsive Design

### Breakpoints
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

### Mobile Features
- Touch-friendly navigation
- Optimized touch targets
- Mobile-first approach
- Swipe gestures support

## 🔧 Development

### Code Structure
- **Separation of Concerns**: HTML, CSS, JS tách biệt
- **Modular CSS**: Component-based styling
- **ES6 Modules**: Modern JavaScript patterns
- **MVC Pattern**: Clean backend architecture

### Best Practices
- **Semantic HTML**: Proper HTML structure
- **Accessibility**: ARIA labels và keyboard navigation
- **SEO Friendly**: Meta tags và structured data
- **Performance**: Optimized loading times

## 🚀 Deployment

### Local Development
```bash
dotnet run --environment Development
```

### Production Deployment
```bash
dotnet publish -c Release
```

### Docker Support
```dockerfile
FROM mcr.microsoft.com/dotnet/aspnet:8.0
COPY bin/Release/net8.0/publish/ App/
WORKDIR /App
ENTRYPOINT ["dotnet", "PORTFOLIO.dll"]
```

## 📞 Support

Nếu bạn có câu hỏi hoặc cần hỗ trợ:
- Tạo issue trên GitHub
- Liên hệ qua email: your.email@example.com
- Follow trên social media

## 📄 License

MIT License - Xem file LICENSE để biết thêm chi tiết.

---

**Happy Coding! 🎉** 