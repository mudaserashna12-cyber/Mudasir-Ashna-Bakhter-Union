<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qara-Zaghan Gold Mine | Mudasir Ashna & Bakhtar Union</title>
    <style>
        *{margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Arial, sans-serif;}
        :root{--primary:#0F4C75; --dark:#1B262C; --gold:#D4AF37; --light:#F8F9FA; --success:#2C5F2D;}
        body{background: var(--light); color: #333; line-height: 1.7;}

        /* Top Bar */
        .top-bar{background: var(--dark); color: white; text-align: center; padding: 0.5rem; font-size: 0.9rem;}

        /* Header & Logos */
        header{background: white; padding: 1.5rem; box-shadow: 0 2px 6px rgba(0,0,0,0.1);}
        .logo-wrapper{max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; gap: 1rem; flex-wrap: wrap;}
        .logo-block{flex: 1; min-width: 260px; text-align: center;}
        .logo-block img{max-width: 180px; height: auto; margin-bottom: 0.6rem;}
        .logo-block h3{color: var(--primary); font-size: 1.1rem; margin-bottom: 0.3rem;}
        .divider{font-size: 2rem; font-weight: bold; color: var(--gold); padding: 0 0.5rem;}

        /* Project Title */
        .project-header{background: var(--primary); color: white; text-align: center; padding: 1.3rem; margin-top: 1rem;}
        .project-header h1{font-size: 1.6rem; margin-bottom: 0.3rem;}
        .project-header p{opacity: 0.9; font-size: 1rem;}

        /* Main Content */
        main{max-width: 1200px; margin: 2rem auto; padding: 0 1rem;}
        .card{background: white; border-radius: 8px; box-shadow: 0 3px 10px rgba(0,0,0,0.08); padding: 1.6rem; margin-bottom: 1.6rem;}
        .card h2{color: var(--primary); border-bottom: 2px solid var(--gold); padding-bottom: 0.5rem; margin-bottom: 1.2rem; font-size: 1.3rem;}
        .detail-row{display: flex; justify-content: space-between; padding: 0.5rem 0; border-bottom: 1px solid #eee; flex-wrap: wrap; gap: 0.4rem;}
        .detail-row strong{color: var(--dark);}

        /* Sample Section */
        .sample-top{display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 0.8rem; margin-bottom: 1rem;}
        .sample-id{color: var(--gold); font-weight: bold; font-size: 1.1rem;}
        .photo-area{border: 2px dashed #BBB; border-radius: 8px; padding: 1.5rem; text-align: center; margin-top: 1rem; background: #FAFAFA;}
        .photo-area p{color: #666; margin-bottom: 0.5rem;}

        /* Buttons & Form */
        .btn{background: var(--primary); color: white; border: none; padding: 0.75rem 1.6rem; border-radius: 5px; font-size: 1rem; cursor: pointer; margin-top: 1rem; transition: background 0.2s;}
        .btn:hover{background: #0A3D62;}
        .add-form{display: none; background: #F0F8FF; padding: 1.5rem; border-radius: 8px; margin-top: 1.2rem;}
        .add-form input, .add-form textarea{width: 100%; padding: 0.7rem; margin: 0.5rem 0; border: 1px solid #DDD; border-radius: 4px; font-size: 0.95rem;}
        .btn-save{background: var(--success);}
        .btn-save:hover{background: #214F22;}

        /* Footer */
        footer{background: var(--dark); color: white; text-align: center; padding: 1.8rem; margin-top: 2.5rem;}
        footer p{margin-bottom: 0.3rem; opacity: 0.9;}
    </style>
</head>
<body>

<div class="top-bar">Joint Mining & Processing Project | Mudasir Ashna × Bakhtar Union</div>

<header>
    <div class="logo-wrapper">
        <div class="logo-block">
            <!-- Mudasir Ashna Logo -->
            <img src="logo-bakhter.png" alt="Mudasir Ashna Mining & Processing Company">
            <h3>Mudasir Ashna Mining & Processing Company</h3>
        </div>
        <div class="divider">✦</div>
        <div class="logo-block">
            <!-- Bakhtar Union Logo -->
            <img src="logo-mudasir.png" alt="Bakhtar Union Mining & Processing Company">
            <h3>Bakhtar Union Mining & Processing Company</h3>
        </div>
    </div>
</header>

<div class="project-header">
    <h1>Qara-Zaghan Gold Mine Project</h1>
    <p>Joint Exploration & Sampling Records</p>
</div>

<main>
    <div class="card">
        <h2>Project Overview</h2>
        <div class="detail-row"><strong>Location:</strong> <span>Doshi District, Baghlan Province, Afghanistan</span></div>
        <div class="detail-row"><strong>Operators:</strong> <span>Mudasir Ashna Mining & Processing Company & Bakhtar Union Mining & Processing Company</span></div>
        <div class="detail-row"><strong>Activity:</strong> <span>Gold Exploration, Mining & Mineral Processing</span></div>
    </div>

    <div class="card">
        <div class="sample-top">
            <h2>Collected Sample Details</h2>
            <span class="sample-id">Sample ID: ABQ-01</span>
        </div>
        <div class="detail-row"><strong>Collection Date:</strong> <span>17 July 2026</span></div>
        <div class="detail-row"><strong>Sample Type:</strong> <span>Quartzite with Gold Mineralization</span></div>
        <div class="detail-row"><strong>Coordinates:</strong> <span>35°33′43.77″ N 68°22′05.42″ E</span></div>
        <div class="detail-row"><strong>Collected By:</strong> <span>Mudasir Ashna & Bakhtar Union Field Team</span></div>

        <!-- Photo Upload Area -->
        <div class="photo-area">
            <p>📷 Sample Photo Placeholder</p>
            <p>Upload or paste your sample image here</p>
            <!-- Uncomment and replace the link below to display your image:
            <img src="your-sample-image.jpg" alt="Sample ABQ-01" style="max-width:100%; border-radius:5px; margin-top:0.5rem;">
            -->
        </div>
    </div>

    <button class="btn" onclick="toggleForm()">➕ Add New Sample Record</button>
    <div class="add-form" id="newSampleForm">
        <h3>Register New Sample</h3>
        <input type="text" placeholder="Sample ID (e.g. ABQ-02)" required>
        <input type="date" required>
        <input type="text" placeholder="Sample Type & Mineral Content" required>
        <input type="text" placeholder="GPS Coordinates" required>
        <input type="text" placeholder="Location / Zone" required>
        <textarea placeholder="Remarks, Lab Results or Additional Notes" rows="3"></textarea>
        <input type="file" accept="image/*">
        <button class="btn btn-save">Save Sample Record</button>
    </div>
</main>

<footer>
    <p>&copy; 2026 Qara-Zaghan Gold Mine Project. All Rights Reserved.</p>
    <p>Mudasir Ashna Mining & Processing Company | Bakhtar Union Mining & Processing Company</p>
</footer>

<script>
function toggleForm(){
    const form = document.getElementById('newSampleForm');
    form.style.display = form.style.display === 'block' ? 'none' : 'block';
}
</script>

</body>
</html>
