
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tuyển dụng VTC1</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f6fa;
    color: #333;
}

header {
    background: #003b71;
    color: white;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 30px;
    font-weight: bold;
    color: #ffcc00;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
}

.banner {
    background: linear-gradient(120deg, #003b71, #0879bd);
    color: white;
    text-align: center;
    padding: 90px 20px;
}

.banner h1 {
    font-size: 40px;
    margin-bottom: 20px;
}

.banner p {
    font-size: 18px;
    margin-bottom: 30px;
}

.btn {
    background: #ffcc00;
    color: #003b71;
    padding: 14px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    display: inline-block;
}

.container {
    width: 85%;
    margin: 50px auto;
}

h2 {
    text-align: center;
    color: #003b71;
    margin-bottom: 35px;
}

.jobs {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.job-card {
    background: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 3px 12px rgba(0,0,0,0.08);
}

.job-card h3 {
    color: #0066a6;
    margin-bottom: 15px;
}

.job-card p {
    margin: 10px 0;
    line-height: 1.5;
}

.job-card button {
    background: #0066a6;
    color: white;
    border: none;
    padding: 12px 20px;
    margin-top: 15px;
    cursor: pointer;
    border-radius: 5px;
}

.job-card button:hover {
    background: #003b71;
}

.about {
    background: white;
    padding: 40px;
    border-radius: 10px;
    line-height: 1.8;
}

form {
    background: white;
    padding: 30px;
    max-width: 600px;
    margin: auto;
    border-radius: 10px;
}

input, textarea, select {
    width: 100%;
    padding: 13px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    width: 100%;
    padding: 14px;
    background: #003b71;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

footer {
    background: #003b71;
    color: white;
    text-align: center;
    padding: 25px;
    margin-top: 50px;
}
</style>
</head>

<body>

<header>
    <div class="logo">VTC1</div>
    <nav>
        <a href="#home">Trang chủ</a>
        <a href="#jobs">Vị trí tuyển dụng</a>
        <a href="#about">Giới thiệu</a>
        <a href="#apply">Ứng tuyển</a>
    </nav>
</header>

<section class="banner" id="home">
    <h1>VTC1 - CƠ HỘI NGHỀ NGHIỆP</h1>
    <p>Gia nhập đội ngũ sáng tạo – Đồng hành cùng truyền thông hiện đại</p>
    <a href="#jobs" class="btn">KHÁM PHÁ CƠ HỘI</a>
</section>

<section class="container" id="jobs">
    <h2>CÁC VỊ TRÍ TUYỂN DỤNG</h2>

    <div class="jobs">

        <div class="job-card">
            <h3>Biên tập viên</h3>
            <p><b>Số lượng:</b> 03 người</p>
            <p><b>Yêu cầu:</b> Kỹ năng viết, biên tập nội dung và tư duy thời sự.</p>
            <p><b>Địa điểm:</b> Hà Nội</p>
            <button onclick="applyJob('Biên tập viên')">
                Ứng tuyển ngay
            </button>
        </div>

        <div class="job-card">
            <h3>Phóng viên</h3>
            <p><b>Số lượng:</b> 05 người</p>
            <p><b>Yêu cầu:</b> Năng động, giao tiếp tốt, có khả năng tác nghiệp.</p>
            <p><b>Địa điểm:</b> Hà Nội</p>
            <button onclick="applyJob('Phóng viên')">
                Ứng tuyển ngay
            </button>
        </div>

        <div class="job-card">
            <h3>Kỹ thuật viên truyền hình</h3>
            <p><b>Số lượng:</b> 02 người</p>
            <p><b>Yêu cầu:</b> Có kiến thức về kỹ thuật hình ảnh và âm thanh.</p>
            <p><b>Địa điểm:</b> Hà Nội</p>
            <button onclick="applyJob('Kỹ thuật viên truyền hình')">
                Ứng tuyển ngay
            </button>
        </div>

    </div>
</section>

<section class="container" id="about">
    <h2>VỀ VTC1</h2>
    <div class="about">
        <p>
            VTC1 là kênh truyền hình thuộc hệ thống truyền hình VTC.
            Với môi trường làm việc năng động, sáng tạo và chuyên nghiệp,
            chúng tôi hướng tới việc phát triển đội ngũ nhân sự có năng lực,
            trách nhiệm và đam mê với lĩnh vực truyền thông, truyền hình.
        </p>
        <p>
            Hãy cùng chúng tôi khám phá những cơ hội nghề nghiệp
            và phát triển sự nghiệp trong lĩnh vực truyền thông.
        </p>
    </div>
</section>

<section class="container" id="apply">
    <h2>FORM ĐĂNG KÝ ỨNG TUYỂN</h2>

    <form id="applyForm">
        <input type="text" id="name"
               placeholder="Họ và tên" required>

        <input type="email" id="email"
               placeholder="Email" required>

        <input type="tel" id="phone"
               placeholder="Số điện thoại" required>

        <select id="position" required>
            <option value="">Chọn vị trí ứng tuyển</option>
            <option>Biên tập viên</option>
            <option>Phóng viên</option>
            <option>Kỹ thuật viên truyền hình</option>
        </select>

        <textarea id="message"
                  placeholder="Giới thiệu bản thân..."
                  rows="5"></textarea>

        <button type="submit">GỬI HỒ SƠ ỨNG TUYỂN</button>
    </form>
</section>

<footer>
    <p>© 2026 VTC1 - WEBSITE TUYỂN DỤNG</p>
    <p>Thông tin tuyển dụng minh họa, chưa phải thông báo tuyển dụng chính thức.</p>
</footer>

<script>
function applyJob(job) {
    document.getElementById("position").value = job;
    document.getElementById("apply").scrollIntoView({
        behavior: "smooth"
    });
}

document.getElementById("applyForm").addEventListener(
    "submit", function(event) {
        event.preventDefault();

        const name = document.getElementById("name").value;

        alert("Cảm ơn " + name +
              "! Thông tin đăng ký đã được ghi nhận trên giao diện.");

        this.reset();
    }
);
</script>

</body>
</html>
