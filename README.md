<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <title>Family Steak</title>
</head>

<body>

    <!-- Header -->
    <header>
        <div class="logo">
            <i class="fas fa-utensils"></i> Family Steak
        </div>
        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#inter">Inter</a>
            <a href="#indrapura">Family Steak</a>
            <a href="#menu">Menu</a>
            <a href="#komentar">Komentar</a>
            <a href="#orderan">Orderan</a>
            <a href="#minuman">Minuman</a>
        </nav>
        <div class="icons">
            <i id="search-icon" class="fas fa-search"></i>
            <i id="menu-bars" class="fas fa-bars"></i>
        </div>
    </header>

    <!-- Search Form -->
    <div id="search-form">
        <input type="search" id="search-box" placeholder="Search...">
        <label id="close" class="fas fa-times"></label>
    </div>

    <!-- Section: Home -->
    <section id="home">
        <div class="home-slider swiper-container">
            <div class="swiper-wrapper">
                <div class="slide swiper-slide">
                    <div class="content">
                        <span>Recomended Order</span>
                        <h3>Steak</h3>
                        <p></p>
                        <button class="btn">Pesan Sekarang</button>
                    </div>
                    <div class="image">
                        <img src="steak1.jpeg" alt="">
                    </div>
                </div>
            </div>
            <div class="swiper-pagination"></div>
        </div>
    </section>

    <!-- Section: Menu -->
    <section id="menu" class="dishes">
        <h2 class="heading">Menu</h2>
        <div class="box-container">
            <div class="box">
                <h3>Sate Madura</h3>
                <div class="image">
                    <img src="sate.jpg" alt="">
                </div>
                <div class="content">
                    <span>Rp15.000</span>
                    <p></p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <i class="fas fa-heart"></i>
                </div>
            </div>
            <div class="box">
                <h3>Bakso</h3>
                <div class="image">
                    <img src="baso.jpg" alt="">
                </div>
                <div class="content">
                    <span>Rp10.000</span>
                    <p></p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <i class="fas fa-heart"></i>
                </div>
            </div>
            <div class="box">
                <h3>Ayam Penyet</h3>
                <div class="image">
                    <img src="ayam.jpg" alt="">
                </div>
                <div class="content">
                    <span>Rp15.000</span>
                    <p></p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <i class="fas fa-heart"></i>
                    </div>
                </div>
                <div class="box">
                    <h3>Ayam Utuh</h3>
                    <div class="image">
                        <img src="ayam1.jpg" alt="">
                    </div>
                    <div class="content">
                        <span>Rp15.000</span>
                        <p></p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <i class="fas fa-heart"></i>
                    </div>
                </div>
            </div>
        </section>
    
        <!-- Mulai Inter -->
        <section class="dishes" id="dishes">
            <h3 class="sub-heading">Menu Best Seller</h3>
            <!-- Tambahkan konten best seller di sini -->
        </section>
    
        <!-- Section: About -->
        <section id="about" class="about">
            <div class="row">
                <div class="image">
                    <img src="https://via.placeholder.com/400" alt="About Image">
                </div>
                <div class="content">
                    <h3>About Us</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent euismod velit at dui.</p>
                    <div class="icons-container">
                        <div class="icons">
                            <i class="fas fa-phone"></i>
                            <span>Contact</span>
                        </div>
                        <div class="icons">
                            <i class="fas fa-location-arrow"></i>
                            <span>Location</span>
                        </div>
                        <div class="icons">
                            <i class="fas fa-clock"></i>
                            <span>Hours</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    
        <!-- Footer -->
        <footer class="footer">
            <div class="box-container">
                <div class="box">
                    <h3>Contact</h3>
                    <a href="#">Email</a>
                    <a href="#">Phone</a>
                    <a href="#">Location</a>
                </div>
                <div class="box">
                    <h3>Quick Links</h3>
                    <a href="#">Home</a>
                    <a href="#">Menu</a>
                    <a href="#">About</a>
                    <a href="#">Contact</a>
                </div>
            </div>
            <div class="akhir">
                <p>&copy; 2025 All Rights Reserved. Designed by You.</p>
            </div>
        </footer>
        <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
    <script src="script.js"></script>
    
        <!-- Script -->
        <script>
            let menu = document.querySelector('#menu-bars');
            let navbar = document.querySelector('.navbar');
    
            menu.onclick = () => {
                menu.classList.toggle('fa-times');
                navbar.classList.toggle('active');
            }
    
            let section = document.querySelectorAll('section');
            let navLinks = document.querySelectorAll('header .navbar a');
    
            window.onscroll = () => {
                menu.classList.remove('fa-times');
                navbar.classList.remove('active');
    
                section.forEach(sec => {
                    let top = window.scrollY;
                    let height = sec.offsetHeight;
                    let offset = sec.offsetTop - 150;
                    let id = sec.getAttribute('id');
    
                    if (top >= offset && top < offset + height) {
                        navLinks.forEach(links => {
                            links.classList.remove('active');
                            document.querySelector('header .navbar a[href*=' + id + ']').classList.add('active');
                        });
                    }
                });
            }
    
            document.querySelector('#search-icon').onclick = () => {
                document.querySelector('#search-form').classList.toggle('active');
            }
    
            document.querySelector('#close').onclick = () => {
                document.querySelector('#search-form').classList.remove('active');
            }
    
            var swiper = new Swiper(".home-slider", {
                spaceBetween: 30,
                centeredSlides: true,
                autoplay: {
                    delay: 7500,
                    disableOnInteraction: false,
                },
                pagination: {
                    el: ".swiper-pagination",
                    clickable: true,
                },
                loop: true,
            });
    
            var swiper = new Swiper(".review-slider", {
                spaceBetween: 20,
                centeredSlides: true,
                autoplay: {
                    delay: 7500,
                    disableOnInteraction: false,
                },
                loop: true,
                breakpoints: {
                    0: {
                        slidesPerView: 1,
                    },
                    640: {
                    slidesPerView: 2,
                },
                768: {
                    slidesPerView: 2,
                },
                1024: {
                    slidesPerView: 3,
                },
            },
        });
    </script>
</body>

</html>
