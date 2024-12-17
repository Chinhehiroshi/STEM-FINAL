
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dự án STEM Maxi Box</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
        font-family: 'Inter', sans-serif;
        background-image: url('https://imgur.com/9ZRsIVy.jpg'); /* Đường dẫn ảnh */
        background-size: cover; /* Ảnh phủ đầy màn hình */
        background-repeat: no-repeat; /* Không lặp ảnh */
        background-attachment: fixed; /* Ảnh cố định khi cuộn */
        background-position: center; /* Căn giữa ảnh */
        color: #343a40;
        }
        header {
            height: 50vh;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
       header h1 {
    font-size: 2.5rem; /* Giảm kích thước tiêu đề */
    font-weight: 700;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}
        }
        header .btn-primary {
            background-color: #4e54c8;
            border: none;
            font-size: 1rem;
            padding: 10px 20px;
            border-radius: 50px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        nav {
            background: #fff;
    height: 120px;
    padding: 60px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        nav .nav-link {
            color: #343a40 !important;
            font-weight: 500;
            margin: 0 10px;
        }
        nav .nav-link:hover {
            color: #007bff !important;
        }
        section {
            padding: 60px 0;
        }
        section h2 {
            font-size: 2rem;
            font-weight: 600;
            margin-bottom: 30px;
            text-align: center;
            color: #007bff;
section {
    padding: 60px 0;
    text-align: left; /* Tùy chỉnh nếu cần */
}
ol li, ul li {
    margin-bottom: 10px;
    line-height: 1.8;
}

        }
        .card {
            border: none;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 15px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s ease-in-out;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card-body {
            padding: 20px;
        }
        .card-body p {
            color: #6c757d;
        }
        footer {
            background: linear-gradient(135deg, #1d2671, #c33764);
            background: #343a40;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
        footer a {
            color: #ffffff;
            text-decoration: none;
            margin: 0 10px;
        }
        footer a:hover {
            color: #ffd700;
            color: #fff;
        }
        .d-grid {
    display: grid;
    gap: 20px; 
    grid-template-columns: repeat(2, 1fr); 
    justify-items: center; 
}
.card {
    width: 100%; 
    max-width: 300px; 
    border: none;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    border-radius: 15px;
    overflow: hidden;
    text-align: center;
    transition: transform 0.3s ease-in-out;
}
.card img {
    width: 100%;
    height: 200px;
    object-fit: cover; 
}
.card:hover {
    transform: translateY(-10px); 
}
/* Giảm kích thước cho tiêu đề Dự án STEM Maxi Box */


/* Khung nổi cho các phần nội dung */
section {
    background-color: white; /* Không có màu nền */
    padding: 30px;
    margin-bottom: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Khung nổi */
}

/* Bỏ khung nổi ở tiêu đề */
h2 {
    padding: 15px;
    background: transparent; /* Không có màu nền */
    color: #007bff; /* Màu chữ */
    font-size: 1.6rem;
    font-weight: 600;
    border-radius: 10px;
    margin-bottom: 20px;
    box-shadow: none; /* Bỏ khung nổi */
}

/* Khung nổi cho các sản phẩm */
.card {
    background-color: transparent;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Khung nổi */
    border: none;
}

/* Khung nổi cho footer */
footer {
            background: linear-gradient(135deg, #1d2671, #c33764);
    background-color: transparent;
    color: #ffffff;
    padding: 30px;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    margin-top: 30px;
}
footer a {
    color: #ffffff;
    text-decoration: none;
    margin: 0 10px;
}
footer a:hover {
            color: #ffd700;
    color: #ffffff; /* Thay đổi màu khi hover */
}



    </style>
</head>
<body>
<header style="background: linear-gradient(135deg, #ff0000, #ff7f00, #0000ff);">
    <h1>Dự án STEM Maxi Box</h1>
    <p>Kết hợp Toán học, Nghệ thuật và AI để tạo ra các giải pháp sáng tạo</p>
    <a href="#about" class="btn btn-primary">Tìm hiểu thêm</a>
</header>

    <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container"><a class="navbar-brand d-flex align-items-center" href="#">
    <img src="https://imgur.com/hO1nRcZ.png" alt="Logo" style="height: 100px; margin-right: 15px;">
    MaxiBox
</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">Giới thiệu</a></li>
                    <li class="nav-item"><a class="nav-link" href="#process">Quy trình</a></li>
                    <li class="nav-item"><a class="nav-link" href="#products">Sản phẩm</a></li>
                    <li class="nav-item"><a class="nav-link" href="#team">Đội ngũ</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Liên hệ</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main>
        <section id="about" class="container">
            <h2>Giới thiệu</h2>
            <p>Dự án Maxi Box là một sáng kiến STEM nhằm tối ưu hóa kích thước hộp để đạt thể tích lớn nhất và chi phí thấp nhất. Học sinh kết hợp kiến thức toán học, mỹ thuật và tin học để tạo ra các thiết kế sáng tạo và hiệu quả.</p>
        </section>
        <section id="process" class="container">
    <h2>Quy trình</h2>
    <ol>
        <li>Xác định vấn đề: Phân tích yêu cầu toán học để tối ưu hóa thể tích.</li>
        <li>Sử dụng công cụ AI như <a href="https://math-gpt.org/">MathGPT</a> và <a href="https://leonardo.ai/>Leonardo.ai</a> để tìm giải pháp.</li>
        <li>Tạo mô hình thử nghiệm bằng các vật liệu bền vững như bìa carton.</li>
        <li>Đánh giá và cải tiến thiết kế dựa trên phản hồi của nhóm và giáo viên.</li>
    </ol>
      
    <div class="text-center mt-4">
        <a href="https://drive.google.com/file/d/11-Zpzo-8UtkEmEPzlblaCzEPFLAoPlZW/view?usp=sharing" 
           class="btn-video" target="_blank">
            <i class="fas fa-play-circle"></i> Xem Video Quy Trình
        </a>
    </div>

    <style>
        .btn-video {
            display: inline-block;
            padding: 10px 25px;
            font-size: 1.2rem;
            font-weight: 600;
            color: #fff; /* Màu chữ trắng */
            text-decoration: none;
            border: none;
            border-radius: 50px; /* Bo tròn */
            background: linear-gradient(135deg, #ff0000, #ff7f00, #0000ff); /* Gradient màu */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2); /* Đổ bóng */
            transition: all 0.3s ease-in-out;
        }

        .btn-video i {
            margin-right: 10px; /* Khoảng cách biểu tượng */
        }

        .btn-video:hover {
            background: linear-gradient(135deg, #e60000, #ff6f00, #0033cc); /* Gradient hover */
            transform: translateY(-5px); /* Hiệu ứng nổi */
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3); /* Đổ bóng lớn hơn */
        }
    </style>

    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    
</section>
        <section id="products" class="container">
    <h2>Sản phẩm của học sinh</h2>
    <div class="d-grid gap-4" style="grid-template-columns: repeat(2, 1fr);">
        <div class="card">
            <img src="https://imgur.com/E3c8h7i.jpg" alt="Sản phẩm 1">
            <div class="card-body">
                <h5>Hộp chủ đề Vũ trụ</h5>
                <p>Nhóm 1</p>
            </div>
        </div>
        <div class="card">
            <img src="https://imgur.com/dz4KDNI.jpg" alt="Sản phẩm 2">
            <div class="card-body">
                <h5>Rương kho báu Đại dương</h5>
                <p>Nhóm 2</p>
            </div>
        </div>
        <div class="card">
            <img src="https://imgur.com/eyJW3uA.jpg" alt="Sản phẩm 3">
            <div class="card-body">
                <h5>Thế giới Ẩm thực</h5>
                <p>Nhóm 3</p>
            </div>
        </div>
        <div class="card">
            <img src="https://imgur.com/cSUMrRs.jpg" alt="Sản phẩm 4">
            <div class="card-body">
                <h5>Hộp Thể thao</h5>
                <p>Nhóm 4</p>
            </div>
        </div>
    </div>
</section>


    <section id="team" class="container">
    <h2>Đội ngũ thực hiện</h2>
    <p><strong>Trường:</strong> THPT Lê Quý Đôn, lớp 12A3</p>
    <p><strong>Học sinh thực hiện:</strong></p>
    <ul>
        <li>Võ Hữu Tài</li>
        <li>Lê Công Bình</li>
        <li>Huỳnh Quang Minh</li>
        <li>Huỳnh Minh Quý</li>
    </ul>
    <p><strong>Giáo viên hướng dẫn:</strong> Huỳnh Nguyễn Diễm Phương</p>
</section>
    <section id="contact" class="container">
    <h2>Liên hệ</h2>
    <p>Để biết thêm thông tin, vui lòng liên hệ với điều phối viên dự án qua email <a href="mailto:stem@school.edu">stem@school.edu</a>.</p>
</section>

 <footer style="background: linear-gradient(135deg, #ff0000, #ff7f00, #0000ff);">
    <p>&copy; 2024 Dự án STEM Maxi Box | <a href="#">Chính sách bảo mật</a> | <a href="#">Điều khoản sử dụng</a></p>
</footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
