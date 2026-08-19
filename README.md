<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GameZone - Featured Games & Rewards</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { background-color: #0b0e14; color: #ffffff; line-height: 1.6; }
    
    header { background: #131722; padding: 20px 8%; display: flex; justify-content: space-between; align-items: center; border-bottom: 2px solid #00ff88; }
    .logo { font-size: 24px; font-weight: bold; color: #00ff88; text-transform: uppercase; letter-spacing: 2px; }
    
    .hero { text-align: center; padding: 80px 20px; background: linear-gradient(180deg, #131722 0%, #0b0e14 100%); }
    .hero h1 { font-size: 42px; margin-bottom: 15px; }
    .hero h1 span { color: #00ff88; }
    .hero p { font-size: 18px; color: #a0a5b5; max-width: 600px; margin: 0 auto 30px; }
    
    .container { padding: 40px 8%; }
    .section-title { font-size: 28px; margin-bottom: 30px; border-left: 4px solid #00ff88; padding-left: 12px; }
    
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; }
    .card { background: #161b26; border-radius: 12px; overflow: hidden; border: 1px solid #232a3b; transition: transform 0.3s ease; }
    .card:hover { transform: translateY(-5px); border-color: #00ff88; }
    .card-img { width: 100%; height: 180px; background: #232a3b; display: flex; align-items: center; justify-content: center; color: #6c757d; font-weight: bold; }
    .card-body { padding: 20px; }
    .card-tag { display: inline-block; background: rgba(0, 255, 136, 0.1); color: #00ff88; font-size: 12px; padding: 4px 8px; border-radius: 4px; font-weight: bold; margin-bottom: 10px; }
    .card-title { font-size: 20px; margin-bottom: 10px; }
    .card-desc { font-size: 14px; color: #a0a5b5; margin-bottom: 20px; }
    
    .btn { display: block; width: 100%; padding: 12px; text-align: center; background: #00ff88; color: #0b0e14; text-decoration: none; font-weight: bold; border-radius: 6px; text-transform: uppercase; }
    .btn:hover { background: #00cc6a; }
    
    footer { text-align: center; padding: 30px; background: #131722; color: #6c757d; font-size: 14px; margin-top: 50px; }
  </style>
</head>
<body>

  <header>
    <div class="logo">GameZone</div>
  </header>

  <section class="hero">
    <h1>Play, Earn & <span>Discover</span></h1>
    <p>Explore top trending games, complete daily tasks, and earn real rewards.</p>
  </section>

  <div class="container">
    <h2 class="section-title">Featured Games</h2>
    
    <div class="grid">
      <!-- Game 1 -->
      <div class="card">
        <div class="card-img">Game Banner 1</div>
        <div class="card-body">
          <span class="card-tag">Earn Rewards</span>
          <h3 class="card-title">Fantasy Battle Arena</h3>
          <p class="card-desc">Play action battles and complete daily missions to unlock exclusive rewards.</p>
          <a href="#" class="btn" target="_blank">Play Now</a>
        </div>
      </div>

      <!-- Game 2 -->
      <div class="card">
        <div class="card-img">Game Banner 2</div>
        <div class="card-body">
          <span class="card-tag">High Bonus</span>
          <h3 class="card-title">Speed Racer Pro</h3>
          <p class="card-desc">Top racing game. Sign up through our link to claim a welcome bonus.</p>
          <a href="#" class="btn" target="_blank">Download & Earn</a>
        </div>
      </div>

      <!-- Game 3 -->
      <div class="card">
        <div class="card-img">Game Banner 3</div>
        <div class="card-body">
          <span class="card-tag">Daily Tasks</span>
          <h3 class="card-title">Puzzle Kingdom</h3>
          <p class="card-desc">Solve daily puzzles, share referral codes, and earn gift vouchers.</p>
          <a href="#" class="btn" target="_blank">Start Playing</a>
        </div>
      </div>
    </div>
  </div>

  <footer>
    <p>&copy; 2026 GameZone. All rights reserved.</p>
  </footer>

</body>
</html>
