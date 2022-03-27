# portfolio

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Amanda/Robert's Portfolio</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- linking css file -->
  <link rel="stylesheet" href="style.css">
  <!-- bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <!-- font awesome -->
  <script src="https://kit.fontawesome.com/31149d48b0.js" crossorigin="anonymous"></script>
</head>

<body>
	<nav class="navbar navbar-expand-lg fixed-top navbarScroll">
        <div class="container">
            <a class="navbar-brand" href="#">Amanda/Robert</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#services">Resume</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
                
            </div>
        </div>
    </nav>
	
	<!-- main banner -->
    <section class="bgimage" id="home">
        <div class="container-fluid">
            <div class="row">
				<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12 hero-text">
					<h2 class="hero_title">Insert big text, name maybe?</h2>
					<p class="hero_desc">Insert smaller text, tagline for who I am?</p>
				</div>
            </div>
        </div>
    </section>
	
	<!-- about section-->
    <section id="about">
        <div class="container mt-4 pt-4">
            <h1 class="text-center">About Me</h1>
            <h2 class="text-left">Mission Statement</h2>
            <div class="row mt-4">
                <div class="col-lg-8">
                    <p> My goal in game design is to spread enjoyment and fun, to help people unwind and relax, and maybe forget the negative things in their lives for a little while. I want to make people smile and have a good time.</p>
                </div>
            </div>
            <h2 class="text-left">Summary</h2>
            <div class="row mt-4">
                <div class="col-lg-4">
                    <p> I’ve spent my entire life as a game designer and the greater part of my life as a programmer. I’ve spent so long with both in my life, in fact, that I’ve been calling myself a game designer since long before I realized I’m trans and genderfluid. Now, I’m as much a part of the LGBTQIA+ community as I am a game designer and D&D dungeon master. I also make and sell handmade resin dice, and I moderate and develop for the web browser game <a href="https://mafia.gg/">Mafia.gg</a></p>
                </div>
            </div>
            <h2 class="text-center">More (unfinished)</h2>
            <div class="row mt-4">
                <div class="col-lg-8">
                    <p> More paragraphs about me go here. figure out how to add images if I go if I want them
                        
                    </p>
                </div>
            </div>
		</div>
    </section>


    <!-- load javascript after loading all html content -->
    <script src="script/script.js"></script>
</body>
</html>