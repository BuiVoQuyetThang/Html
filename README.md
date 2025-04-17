# Html
<!DOCTYPE html>  <html lang="vi">  
<head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1" />  
  <title>Thế Giới Thiên Nhiên</title>  
  <style>  
    html {  
      scroll-behavior: smooth;  
    }  body {  
  margin: 0;  
  font-family: 'Arial', sans-serif;  
  background-color: #eafaf1;  
  color: #1e3d2f;  
}  

header {  
  background-color: #c0e8d5;  
  padding: 20px;  
  text-align: center;  
}  

header h1 {  
  margin: 0;  
  color: #2e8b57;  
  font-family: 'Courier New', monospace;  
}  

nav {  
  display: flex;  
  justify-content: center;  
  background-color: #a0d6b4;  
  position: sticky;  
  top: 0;  
  z-index: 999;  
}  

nav a {  
  color: #1e3d2f;  
  padding: 14px 20px;  
  text-decoration: none;  
  display: block;  
}  

nav a:hover {  
  background-color: #7cbf94;  
}  

section, .content {  
  padding: 30px;  
  max-width: 1000px;  
  margin: auto;  
}  

.content {  
  display: grid;  
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));  
  gap: 20px;  
}  

.image-card {  
  background-color: #dff5e3;  
  border: 1px solid #90c89f;  
  border-radius: 10px;  
  overflow: hidden;  
  transition: transform 0.3s;  
}  

.image-card:hover {  
  transform: scale(1.05);  
}  

.image-card img {  
  width: 100%;  
  display: block;  
}  

.image-card a {  
  display: block;  
  padding: 10px;  
  color: #2e8b57;  
  text-align: center;  
  text-decoration: none;  
}  

.image-card a:hover {  
  text-decoration: underline;  
}  

footer {  
  background-color: #c0e8d5;  
  color: #1e3d2f;  
  text-align: center;  
  padding: 20px;  
}  

.extra-image {  
  width: 100%;  
  border-radius: 10px;  
  margin-top: 15px;  
}

  </style>  
</head>  
<body>    <header>  
    <h1>Thế Giới Thiên Nhiên</h1>  
  </header>    <nav>  
    <a href="#home">Trang Chủ</a>  
    <a href="#nature">Cảnh Đẹp</a>  
    <a href="#gallery">Thư Viện Ảnh</a>  
    <a href="#contact">Liên Hệ</a>  
  </nav>    <!-- Trang Chủ -->    <section id="home">  
    <h2 style="color: #2e8b57; text-align: center;">Chào mừng đến với Thế Giới Thiên Nhiên</h2>  
    <p style="font-size: 18px; text-align: center;">  
      Nơi lưu giữ những khoảnh khắc tuyệt đẹp của thiên nhiên – từ rừng xanh, biển cả, núi non đến những cánh đồng ngát hương.    
      <br><br>  
      Hãy cùng chiêm ngưỡng vẻ đẹp nguyên sơ và cảm nhận sự yên bình từ mẹ thiên nhiên.  
    </p>  
  </section>    <!-- Cảnh Đẹp -->    <section id="nature">  
    <h2 style="color: #2e8b57; text-align: center;">Cảnh Đẹp Thiên Nhiên</h2>  
    <p style="font-size: 18px;">  
      <strong>Rừng nguyên sinh</strong>: Với tầng tầng lớp lớp cây cổ thụ, ánh sáng len lỏi qua tán lá tạo nên một khung cảnh huyền ảo.  
    </p>  
    <img class="extra-image" src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1000&q=80" alt="Rừng nguyên sinh" />  <p style="font-size: 18px; margin-top: 20px;">  
  <strong>Thác nước giữa núi rừng</strong>: Dòng nước đổ trắng xóa tạo âm thanh vang vọng đầy sống động giữa thiên nhiên hoang dã.  
</p>  
<img class="extra-image" src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1000&q=80" alt="Thác nước hùng vĩ" />

  </section>    <!-- Thư Viện Ảnh -->    <section id="gallery">  
    <h2 style="color: #2e8b57; text-align: center;">Thư Viện Ảnh</h2>  
    <div class="content">  
      <div class="image-card">  
        <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1000&q=80" alt="Hoàng hôn biển">  
        <a href="#">Hoàng hôn trên biển</a>  
      </div>  
      <div class="image-card">  
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1000&q=80" alt="Rừng rậm">  
        <a href="#">Kỳ quan giữa rừng</a>  
      </div>  
      <div class="image-card">  
        <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1000&q=80" alt="Thác nước thiên nhiên">  
        <a href="#">Âm thanh của thiên nhiên</a>  
      </div>  
    </div>  
  </section>    <!-- Liên Hệ -->    <footer id="contact">  
    <h3>Liên hệ với tác giả</h3>  
    <p>Bùi Võ Quyết Thắng – Lớp 12CSA2</p>  
    <p>Email: nguyenvana@example.com | SĐT: 0123 456 789</p>  
  </footer>  </body>  
</html>
