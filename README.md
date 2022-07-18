![cover](./cover.png)  
![Services](./services.png)
# Web Development for 5th Semester Computer, IIST
 👉 Create a Web Design using HTML,CSS, JS &amp; Bootstrap Project-1  
---
### Youtube Link of Web Design  
[Web Design-Project](https://youtu.be/aqvRafv_5nc)  
---
 ### Playlists Link for Web Design & Web Development of me  
1. [Web Design Project-1](https://www.youtube.com/playlist?list=PLxqLmn_MNa-Sl7EtwOFCV4zWEwleEd3mk)  
2. [Web Design Project-2](https://www.youtube.com/playlist?list=PLxqLmn_MNa-Rfie-DoTgRRnUnXxZKGZip)  
3. [Web Development Level-IV Certificate](https://www.youtube.com/playlist?list=PLxqLmn_MNa-Sv8NyBi2i97qDElbCeWcdW)
---

### Useful Resources for Web Design for Free Downloadable Images & Videos : 
1. [Unsplash](https://unsplash.com/)
2. [Pixa Bay](https://pixabay.com/)
3. [Pexels](https://www.pexels.com/)  
4. [Free Images](https://www.freeimages.com/)    

### Useful Resources for Web Design for Free Downloadable Illustrations:   
1. [Undraw](https://undraw.co)
2. [Free Pik](https://www.freepik.com)
3. [Vecteezy](https://www.vecteezy.com/)
4. [Storyset](https://storyset.com/)     

### Usable Gradient Colors Source:  
- [Web Gradients](https://webgradients.com/)  
- [CSS Gradient](https://cssgradient.io/)   

### Useful Resources for Web Design for Free Downloadable for icons  
- [Free Icons](https://freeicons.io/)  
- [Flat Icons](https://www.flaticon.com/)  

### Useful Resources for Web Design for Free Downloadable for background remove from Image
- [Remove BG](https://www.remove.bg/)
- [Adobe BG](https://www.adobe.com/express/feature/image/remove-background)

### Useful Resources for Web Design for Free Downloadable for Photo Editor & Design Maker
- [Pix Lr](https://pixlr.com/e/) 
- [Picture Resize](https://picresize.com/) 
- [Adobe Resize](https://www.adobe.com/express/feature/image/resize) 
- [Biteable](https://biteable.com/tools/image-resizer/) 

---  

 ### HTML Code  
~~~html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Design</title>
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="assets/css/bootstrap.min.css">
</head>
<body>
<!-- header part start -->
<header>
	<div class="container header_cont">
		<div class="row">
			<div class="col-lg-6">
				<p>বাংলাদেশ জাতীয় তথ্য বাতায়ন</p>
			</div>
			<div class="col-lg-6 text-end header_right">
				<p>১৮ পৌষ, ১৪২৮</p>
				<a href="">English</a>
			</div>
		</div>
	</div>
</header>
<!-- header part end -->
<!-- logo part start -->
<section>
	<div class="container logo">
		<div class="row">
			<div class="col-lg-5">
				<a href=""><img src="assets/images/logo/logo_bn.png" alt=""></a>
			</div>
			<div class="col-lg-5">
				<form action="">
					<input type="text" placeholder="খুঁজুন ">
					<button>অনুসন্ধান </button>
				</form>
			</div>
			<div class="col-lg-2 d-flex justify-content-end">
				<div class="logo1">
					<a href=""><img src="assets/images/logo/a2i-logo-footer.png" alt=""></a>
				</div>
				<div class="logo2">
					<p>সাথে থাকুন:</p>
					<a href=""><img src="assets/images/logo/facebook-icon.png" alt=""></a>
					<a href=""><img src="assets/images/logo/facebook-icon.png" alt=""></a>
					<a href=""><img src="assets/images/logo/facebook-icon.png" alt=""></a>
					<a href=""><img src="assets/images/logo/facebook-icon.png" alt=""></a>
				</div>
			</div>
		</div>
	</div>
</section>
<!-- logo part end -->
<!-- menu part start -->
<section>
	<div class="container">
		<div class="row">
			<nav class="navbar navbar-expand-lg bg-light">
				<div class="container-fluid">
				  
				  <div class="collapse navbar-collapse" id="navbarSupportedContent">
					<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					  <li class="nav-item">
						<a class="nav-link active" aria-current="page" href="#">Home</a>
					  </li>
					  <li class="nav-item">
						<a class="nav-link" href="#">Link</a>
					  </li>
					  
					</ul>
				
				  </div>
				</div>
			  </nav>
		</div>
	</div>
</section>
<!-- menu part end -->
<!-- hero part start -->
<section>
	<div class="container">
		<div class="row">
			<div class="col-lg-8">
				<!-- image part start -->
				<div class="main_img">
					<a href=""><img src="assets/images/National-Portal-Card-PM.jpg" class="d-block w-100"alt=""></a>
				</div>
				<!-- marquee part start -->
				<div class="marquee">
					<h4><marquee behavior="" direction="">
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid labore voluptas quod totam ullam incidunt!
					</marquee></h4>
				</div>
				<!-- slider part start -->
				<div class="slider">
					<div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
						<div class="carousel-inner">
						  <div class="carousel-item active">
							<img src="assets/images/slider/Banner-1.jpg" class="d-block w-100" alt="...">
						  </div>
						  <div class="carousel-item">
							<img src="assets/images/slider/Banner-2.jpg" class="d-block w-100" alt="...">
						  </div>
						  <div class="carousel-item">
							<img src="assets/images/slider/our_pride.png" class="d-block w-100" alt="...">
						  </div>
						</div>
						
					  </div>
				</div>
				<!-- tabs part start -->
				<div class="tabs">
					<ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
						<li class="nav-item" role="presentation">
						  <button class="nav-link active" id="pills-home-tab" data-bs-toggle="pill" data-bs-target="#pills-home" type="button" role="tab" aria-controls="pills-home" aria-selected="true">জনপ্রিয় সেবা</button>
						</li>
						<li class="nav-item" role="presentation">
						  <button class="nav-link" id="pills-profile-tab" data-bs-toggle="pill" data-bs-target="#pills-profile" type="button" role="tab" aria-controls="pills-profile" aria-selected="false">নতুন সেবা</button>
						</li>
						<li class="nav-item" role="presentation">
						  <button class="nav-link" id="pills-contact-tab" data-bs-toggle="pill" data-bs-target="#pills-contact" type="button" role="tab" aria-controls="pills-contact" aria-selected="false">মোবাইল সেবা</button>
						</li>
						<li class="nav-item" role="presentation">
						  <button class="nav-link" id="pills-disabled-tab" data-bs-toggle="pill" data-bs-target="#pills-disabled" type="button" role="tab" aria-controls="pills-disabled" aria-selected="false" disabled>Disabled</button>
						</li>
					  </ul>
					  <div class="tab-content" id="pills-tabContent">
						<div class="tab-pane fade show active" id="pills-home" role="tabpanel" aria-labelledby="pills-home-tab" tabindex="0">
							<div class="row">
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/online_application.png" alt="">
									<p>
										অনলাইন আবেদন                                </p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
							</div>
						</div>
						<div class="tab-pane fade" id="pills-profile" role="tabpanel" aria-labelledby="pills-profile-tab" tabindex="0">
							<div class="row">
								<div class="col-lg-2">
									<img src="assets/images/tabs/agriculture.png" alt="">
									<p>
										মৎস্য ও প্রাণী                            </p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/online_application.png" alt="">
									<p>
										অনলাইন আবেদন                                </p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
								<div class="col-lg-2">
									<img src="assets/images/tabs/business.png" alt="">
									<p>অর্থ ও বাণিজ্য</p>
								</div>
							</div>
						</div>
						<div class="tab-pane fade" id="pills-contact" role="tabpanel" aria-labelledby="pills-contact-tab" tabindex="0">..3.</div>
						<div class="tab-pane fade" id="pills-disabled" role="tabpanel" aria-labelledby="pills-disabled-tab" tabindex="0">...</div>
					  </div>
				</div>
				<!-- other part start -->
				<div class="others"></div>
			</div>
			<div class="col-lg-4">
				<!-- sidebar image start -->
				<div class="side_img">
					<a href=""><img src="assets/images/sidebar/bangladesh-portal--batton-bangla.png" class="d-block w-100"alt=""></a>
					<a href=""><img src="assets/images/sidebar/bangladesh-portal--batton-bangla.png" class="d-block w-100"alt=""></a>
					<a href=""><img src="assets/images/sidebar/bangladesh-portal--batton-bangla.png" class="d-block w-100"alt=""></a>
					<a href=""><img src="assets/images/sidebar/bangladesh-portal--batton-bangla.png" class="d-block w-100"alt=""></a>
					<a href=""><img src="assets/images/sidebar/bangladesh-portal--batton-bangla.png" class="d-block w-100"alt=""></a>
					<a href=""><img src="assets/images/sidebar/bangladesh-portal--batton-bangla.png" class="d-block w-100"alt=""></a>
				</div>
				<!-- sidebar video start -->
				<div class="sidebar_video">
					<h4>সকল বাতায়ন</h4>
					<form action="">
						<select>
							<option selected>Open this select menu</option>
							<option value="1">One</option>
							<option value="2">Two</option>
							<option value="3">Three</option>
						  </select>
						  <button>Search</button>
					</form>
					<h5>মুজিব১০০ আ্যাপ</h5>
					<iframe width="362" height="200" src="https://www.youtube.com/embed/4Om3kZJL-qU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
					<h5>মাস্ক পরুন সেবা নিন</h5>
					<img src="assets/images/sidebar/mask-bd-portal (1).jpg" class="d-block w-100" alt="">
					<h4>ডেঙ্গু প্রতিরোধে করণীয়</h4>
					<img src="assets/images/sidebar/dengu.jpg" class="d-block w-100"alt="">
				</div>
			</div>
		</div>
	</div>
</section>
<!-- hero part end -->
<footer>
	<div class="container">
		<div class="row">
			<img src="assets/images/footer/download.png" class="d-block w-100" alt="">
		</div>
		<div class="row">
			<div class="col-lg-8">
				<nav class="navbar navbar-expand-lg bg-light">
					<div class="container-fluid">
					  
					  <div class="collapse navbar-collapse" id="navbarSupportedContent">
						<ul class="navbar-nav me-auto mb-2 mb-lg-0">
						  <li class="nav-item">
							<a class="nav-link active" aria-current="page" href="#">Home</a>
						  </li>
						  <li class="nav-item">
							<a class="nav-link" href="#">Link</a>
						  </li>
						  
						</ul>
					
					  </div>
					</div>
				  </nav>
			</div>
			<div class="col-lg-4 text-end">
				<p>পরিকল্পনা ও বাস্তবায়নে: এটুআই, মন্ত্রিপরিষদ বিভাগ, বিসিসি, বেসিস, ডিওআই</p>
				<img src="assets/images/footer/np-logo-set.png" alt="">
			</div>
		</div>
	</div>
</footer>
	


	<script src="assets/js/bootstrap.bundle.min.js"></script>
</body>
</html>
~~~  

### Style.css code  

~~~css
*{
    margin: 0;
    padding: 0;
}

.header_cont{
    height: 30px; 
    background: #9e5bba;
    color: #fff;
    font-size: 14px;
    padding: 5px;
}
.header_right p{
    display: inline-block;
    border-right: 1px solid #fff;
    padding-right: 5px;
    margin-right: 5px;
}
.header_right a{
    color: #fff;
    text-decoration: none;
}
/* logo part start */
.logo{
height: 110px;
padding: 25px;
}
.logo1{
    border-right: 1px solid #ddd;
    padding-right: 5px;
    margin-right: 5px;
}
/* logo part end */
.sidebar_video h5{
    background: green;
    padding: 5px;
    color: #fff;
}
~~~
