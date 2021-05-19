<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<meta name="google-site-verification" content="Bwh8jrsclHJbDw-mixKS1kVl54tEx49DDEE4oJ4xBpE" />
<style>

a:link {
  color: Cyan;
  background-color: transparent;
  text-decoration: none;
}
a:visited {
  color: Cyan;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
body{
 background-color:LightGoldenRodYellow;
}
h3{
list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333333;
  display: block;
  color: white;
  text-align:none;
  padding: 16px;
  text-decoration: none;
  font-size:50px;
  font-family:verdana;
 }
h1
{  background-color:MediumTurquoise;
   border: 3px solid OrangeRed;
   padding: 30px;
   font-size:300%;
   font-family:verdana;
   
   
}
p
{
   background-color:SkyBlue;
   boder: 1px solid Tomato;
   padding :10px;
   font-size:100%;
   font-family:verdana;
}


ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 16px;
  text-decoration: none;
  font-size:50px;
}

li a:hover {
  background-color: #111111;
}
.toggle-box {
  display: none;
}

.toggle-box + label {
  cursor: pointer;
  display: block;
  font-weight: bold;
  line-height: 21px;
  margin-bottom: 5px;
}

.toggle-box + label + div {
  display: none;
  margin-bottom: 10px;
}

.toggle-box:checked + label + div {
  display: block;
}

.toggle-box + label:before {
  background-color: #4F5150;
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  color: #FFFFFF;
  content: "+";
  display: block;
  float: left;
  font-weight: bold;
  height: 20px;
  line-height: 20px;
  margin-right: 5px;
  text-align: center;
  width: 20px;
  color:red;
  
}

.toggle-box:checked + label:before {
  content: "\2212";
  background-color:yellow;
 
}
.fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin: 6px 3px;
}

.fa:hover {
    opacity: 0.9;
}

.fa-facebook {
  background: #3B5998;
  color: blue;
}
.fa-google {
  background: #dd4b39;
  color: white;
}

</style>
</head>

<body>
<a href="https://www.haui.edu.vn/vn" target="_blank" >
<img src="data:image/jpeg;base64,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" style="width:1520px;height:400px;" >
</a>
<h1 style="text-align:center;">
<img src="https://media.cdnandroid.com/60/4b/e4/c2/imagen-quao-n-ly-chao-t-lae-a-ng-qlcl-haui-0thumb.jpeg" width="80" height="80" >
<marquee>Information System ( HTTT01 - HaUI)   -------    Web về thông tin của lớp Hệ Thống thông tin 1 </marquee>
</h1>
 
<ul>
 <li><a href="#TLMH">Tài Liệu Môn Học</a></li>
 <li><a href="#TS">Tuyển Sinh Đại Học</a></li>
 <li><a href="#ABM">About me</a></li>

</ul>
 <h2  style="background-color:LightSkyBlue";>
<marquee>đây là page để demo vì mình mới chỉ tâp làm web , chưa có kinh nhiệm :< , mong ae thông cảm , mọi góp ý mình xin nhận  </marquee>
</h2>


<ul id="TLMH"> 
  <li><a href="#Laptrinh">Lập Trình (IT)</a><li>
  <li><a href="#Toan">Môn Toán</a></li>
  <li><a href="#Li">Môn Lí</a></li> 
  <li><a href="#Hoa"> Môn Hóa</a></li>
  <li><a href="#Sinh"> Môn Sinh</a></li>
  <li><a href="#Van"> Môn Văn</a></li>
  <li><a href="#Anh">Môn Anh</a></li>
  <li><a href="#Su">Môn Sử</a></li>
  <li><a href="#Dia"> Môn Địa </a><li>
  <li><a href="#Congdan"> Môn DDCD</a><li>
 
 </ul>
<h2>
</h2>
<h2>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
</h2>
 <h3 id="Toan">
  Môn Toán
 </h3>
<h2  style="background-color:DarkGrey " >
1.Các Chuyên đề Ôn tập Từ đầu (2021)

<a href="https://drive.google.com/drive/folders/10oOY4m_6613Lj8ZEpEXy8FQLnR59mXIY?usp=sharing"  target="_blank"> Click here</a>
<br><br>
2.Ôn tập Góc và Khoảng cách (2021)
<a href="https://drive.google.com/drive/folders/10oOY4m_6613Lj8ZEpEXy8FQLnR59mXIY?usp=sharing" target="_blank">Click here</a>
<br><br>
3.Tài Liệu Ôn Tập (5 - 6 điểm ) (2021)
<a href="https://drive.google.com/drive/folders/1-WwhcJS9pDu2t9kUMAxzOoWzR6HzTRwW?usp=sharing" target="_blank">Click here</a>
<br><br>
4.Tài Liệu Ôn Tập (7-8 điểm ) (2021)
<a href="https://drive.google.com/drive/folders/1uD6BinsJupolO9zh9dW3cDYm0N6UYZc2?usp=sharing" target="_blank">Click here</a>

<br><br>
5.Tài Liệu Ôn Tập (9-10 điểm ) (2021)
<a href="https://drive.google.com/drive/folders/1fAxPIo0zTH0CfV4H_15RWmKOwQrOIJWe?usp=sharing" target="_blank">Click here</a>
<br><br>
6.40 Chuyên đề Ôn tập THPT (2021)
<a href="https://drive.google.com/drive/folders/15YIGujGQK-8Q9epzYA75hW5Z1JGuZsJv?usp=sharing" target="_blank">Click here</a>
<br><br>
7.10 Đề tự đánh Giá năng Lực (2021)
<a href="https://drive.google.com/file/d/1ExgJgM9k6TTO99o8FzpiwodEA1GEu2O9/view?usp=sharing" target="_blank">Click here</a>
<br><br>
8.BỘ 40 đề chính thức - Phát triển đề của Bộ Giáo Dục (2021)
<a href="https://drive.google.com/drive/folders/1QTwmotPGFPtAxiVNM22SDI9bfU_U290G?usp=sharing" target="_blank">Click here</a>
<br><br>
9.Tổng Hợp đề Thi Đại Học Qua các năm (2016 - 2020)
<a href="https://drive.google.com/drive/folders/1TkfE2E3aeMsaPYy0sEaa_vlBgV4cS5tk?usp=sharing" target="_blank">Click here</a>
<br><br>
<input class="toggle-box" id="identifier-1" type="checkbox"  >
<label for="identifier-1" ><a>Click để Xem thêm </a></label>
<div>
10.Tổng Hợp 40 đề ôn Thi THPT Quốc Gia 2021<a href="https://drive.google.com/drive/folders/1LDao58iR4rkAg7qENajbvcTRdBHs0LlV?usp=sharing" target="_blank">Click here</a></div>
    
</h2>
<br><br><br>
<h3 id="Hoa" >
Môn Hóa
</h3>
<br><br><br>
<h3 id="Li">
  Môn Lí
 </h3>	
 <br><br><br>
 <h3 id="Hoa">
  Môn Hóa
 </h3><br><br><br>
 <h3 id="Van">
  Môn Văn
 </h3><br><br><br>
 <h3 id="Anh">
  Môn Anh
 </h3><br><br><br>
 <h3 id="Sinh">
  Môn Sinh
 </h3><br><br><br>
 <h3 id="Su">
  Môn Sử
 </h3><br><br><br>
 <h3 id="Dia">
  Môn Địa
 </h3><br><br><br>
 <h3 id="Congdan">
  Môn DDCD
  </h3><br><br><br>
<h3 id="Laptrinh">
Lập Trình (IT)
</h3>
<h2 style="background-color:DarkGrey";>
1. Tài Liệu Nhập Môn Lập trình c/c++ ( Chuẩn VNU)
<a href="https://drive.google.com/drive/folders/16lViITinALIwQngC2r-IzvYP_vw5l15X?usp=sharing" target="_blank">Click here</a>
<br><br>
2. Tài Liệu Lập Trình Web (Đh Công Nghệ Thông Tin)
<a href="https://drive.google.com/drive/folders/1r00H1NyVfbSrNcmH4hVtRN9fJFq7m6x3?usp=sharing" target="_blank">Click here</a>
<br><br>
3.Tài Liệu Lập trình Java
<a href="https://drive.google.com/file/d/11_Ah0J8T1Ns_Q8JUKlOrSpqgNCaqEEdN/view?usp=sharing" target="_blank">Click here</a>
<br><br>
4.Tài Liệu Lập trình Python
<a href="https://drive.google.com/drive/folders/1nnkniRq3-YJdTGOy0taBNhvSd5bw40hE?usp=sharing" target="_blank">Click here</a>
<br><br>
5.Tài Liệu Lập trình Hướng đối Tượng C++
<a href="https://drive.google.com/drive/folders/1A5rktv5c5whvQHLveD5BDXfXU7arh7d7?usp=sharing" target="_blank">Click here</a>
<br><br>
6.Tài Liệu Lập trình Javascript 
<a href="https://drive.google.com/drive/folders/16gPjuki0oWm1O_54cyIyHSLCSpC5PKWx?usp=sharing" target="_blank">Click here</a>
<br><br>
</h3>
<br><br><br>
<h3 id="ABM">
ABOUT ME 
</h3>
<h2 style="background-color:DarkGrey"; "font-family:verdana";"font-size:20px">
Chào các Bạn , Mình Là 'Nguyễn Trọng Quân' , Coder & Admin của Trang Web này .<br>
Profile:<br>
Name: Quân &emsp; &emsp; &emsp; full Name: Nguyễn Trọng Quân;<br>
Year of Birth: 2002<br>
Sex: Male<br>
School: K15 - Information system - Hanoi University of Industry (haui)<br>
Home town: Ninh Bình City <br>
My FaceBook:<a href="https://www.facebook.com/quan.nguyentrong.35325" target="_blank"  class="fa fa-facebook"></a><br>
Send Mail: <a href="mailto:qquannguyentrong123@gmail.com" target="_blank" class="fa fa-google"></a>
</h2>           


 

</body>
</html>
   
