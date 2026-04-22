<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Polai Academy | Smart Learning Portal</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #2c3e50;
            --accent: #e67e22;
            --success: #27ae60;
            --danger: #e74c3c;
            --light: #f8f9fa;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body { background-color: var(--light); color: #333; line-height: 1.6; }

        /* Navigation */
        nav {
            background: var(--primary);
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .logo { color: white; font-size: 1.5rem; font-weight: bold; }
        .logo span { color: var(--accent); }
        .nav-links a { color: white; text-decoration: none; margin-left: 20px; font-weight: 500; transition: 0.3s; }
        .nav-links a:hover { color: var(--accent); }

        /* Hero Section */
        .hero {
            height: 70vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1513258496099-48168024aec0?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 0 20px;
        }
        .hero h1 { font-size: 3rem; margin-bottom: 15px; }
        .hero p { font-size: 1.2rem; max-width: 700px; margin-bottom: 25px; }
        .btn-main { background: var(--accent); color: white; padding: 15px 35px; border-radius: 50px; text-decoration: none; font-weight: bold; transition: 0.3s; }
        .btn-main:hover { transform: scale(1.05); background: #d35400; }

        /* Mock Test Highlight Section */
        .test-info { padding: 80px 10%; background: white; text-align: center; }
        .test-info h2 { font-size: 2.5rem; color: var(--primary); margin-bottom: 40px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; }
        .card { padding: 30px; border-radius: 15px; background: var(--light); transition: 0.3s; border: 1px solid #eee; }
        .card:hover { transform: translateY(-10px); box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
        .card i { font-size: 2.5rem; color: var(--accent); margin-bottom: 15px; }

        /* Features Section */
        .features { padding: 60px 10%; background: #f1f2f6; display: flex; flex-wrap: wrap; justify-content: center; gap: 40px; }
        .feat-item { flex: 1; min-width: 300px; background: white; padding: 30px; border-radius: 15px; }

        /* Footer */
        footer { background: #1a1a1a; color: white; padding: 50px 10% 20px; text-align: center; }
        .social-link { color: #ff0000; font-size: 2rem; text-decoration: none; display: inline-block; margin-top: 15px; }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            .nav-links { display: none; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Polai<span> Academy</span></div>
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#test">Mock Test</a>
            <a href="#features">Lessons</a>
            <a href="https://youtube.com/@polaiacademy" target="_blank">YouTube</a>
        </div>
    </nav>

    <section class="hero">
        <h1>Prepare for Success with Polai Academy</h1>
        <p>Expert Guidance for Class 1-10, SSC, Railway, OSSC & OSSSC Exams. Bilingual Lessons in English, Odia & Hindi.</p>
        <a href="#test" class="btn-main">Launch Mock Test</a>
    </section>

    <section class="test-info" id="test">
        <h2>Smart Mock Test Pattern</h2>
        <div class="grid">
            <div class="card">
                <i class="fas fa-tasks"></i>
                <h3>13 Questions</h3>
                <p>Curated MCQs based on latest exam patterns [cite: 1414-1785].</p>
            </div>
            <div class="card">
                <i class="fas fa-clock"></i>
                <h3>25 Minutes</h3>
                <p>Strict time limit for real exam experience.</p>
            </div>
            <div class="card">
                <i class="fas fa-plus-circle" style="color: var(--success);"></i>
                <h3>+2 Marks</h3>
                <p>Rewarding every correct answer.</p>
            </div>
            <div class="card">
                <i class="fas fa-minus-circle" style="color: var(--danger);"></i>
                <h3>-1 Mark</h3>
                <p>Negative marking for wrong attempts.</p>
            </div>
        </div>
        <div style="margin-top: 50px;">
            <p style="background: #fff3e0; padding: 15px; border-radius: 10px; display: inline-block; color: #e67e22; font-weight: bold;">
                <i class="fas fa-info-circle"></i> Live Attendance Palette & Result Dashboard Included!
            </p>
        </div>
    </section>

    <section class="features" id="features">
        <div class="feat-item">
            <h3>English Grammar</h3>
            <p>Master Nouns, Pronouns, and more with our basic-to-advanced level notes [cite: 1-1413].</p>
        </div>
        <div class="feat-item">
            <h3>Attractive Visuals</h3>
            <p>We use cartoon avatars and high-quality graphics to make learning engaging.</p>
        </div>
    </section>

    <footer>
        <h2>Join Polai Academy Community</h2>
        <p>Subscribe to our channel for daily updates and smart preparation tips.</p>
        <a href="https://youtube.com/@polaiacademy?si=gUwt0zAa-S8ccqhK" target="_blank" class="social-link">
            <i class="fab fa-youtube"></i> Subscribe Now
        </a>
        <p style="margin-top: 30px; font-size: 0.8rem; color: #666;">&copy; 2026 Polai Academy. Best of Luck!</p>
    </footer>

</body>
</html>
