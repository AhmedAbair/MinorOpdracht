<script>
	// Add any necessary JavaScript here
  </script>
  
  <style>
	header {
	  display: flex;
	  justify-content: space-between;
	  align-items: center;
	  padding: 1rem;
	  background-color: #f1f1f1;
	}
  
	.logo {
	  display: flex;
	  align-items: center;
	}
  
	.logo img {
	  height: 40px;
	  margin-right: 1rem;
	}
  
	.nav-links a {
	  margin-left: 1rem;
	  text-decoration: none;
	  color: #333;
	}
  
	main {
	  text-align: center;
	  padding: 2rem;
	  background: linear-gradient(to bottom, #d9edf7, #fff);
	}
  
	.cards {
	  display: flex;
	  justify-content: space-around;
	  margin-top: 2rem;
	}
  
	.card {
	  background-color: #0066cc;
	  border-radius: 8px;
	  color: white;
	  padding: 1rem;
	  width: 200px;
	  text-align: center;
	}
  
	.card img {
	  width: 100%;
	  border-bottom: 2px solid white;
	  margin-bottom: 1rem;
	}
  
	.card .attributes {
	  margin: 1rem 0;
	}
  
	.card .attributes p {
	  margin: 0.5rem 0;
	}
  
	.card .attributes span {
	  display: inline-block;
	  width: 10px;
	  height: 10px;
	  background-color: yellow;
	  margin-right: 2px;
	}
  
	.card button {
	  background-color: yellow;
	  border: none;
	  padding: 0.5rem 1rem;
	  cursor: pointer;
	}
  
	footer {
	  background-color: #005580;
	  color: white;
	  padding: 1rem;
	  text-align: center;
	}
  </style>
  
  <header>
	<div class="logo">
	  <img src="C:\Users\ahmed\OneDrive\Bureaublad\bootShizzle\svelte-app\public\rijkswaterLogo.png">
	  <h1>Rijkswaterstaat experience</h1>
	</div>
	<div class="nav-links">
	  <a href="#">Contact</a>
	  <a href="#">International</a>
	</div>
  </header>
  
  <main>
	<h2>Kies je boot</h2>
	<div class="cards">
	  <div class="card">
		<img src="/assets/boat1.png" alt="Boat 1">
		<div class="attributes">
		  <p>Snelheid</p>
		  <div>
			<span></span><span></span><span></span><span></span><span></span>
		  </div>
		  <p>Diepte</p>
		  <div>
			<span></span><span></span><span></span><span></span>
		  </div>
		</div>
		<button>Volgende</button>
	  </div>
	  <div class="card">
		<img src="/assets/boat2.png" alt="Boat 2">
		<div class="attributes">
		  <p>Snelheid</p>
		  <div>
			<span></span><span></span><span></span><span></span><span></span>
		  </div>
		  <p>Diepte</p>
		  <div>
			<span></span><span></span><span></span><span></span>
		  </div>
		</div>
		<button>Volgende</button>
	  </div>
	  <div class=" card">
		<img src="/assets/boat3.png" alt="Boat 3">
		<div class="attributes">
		  <p>Snelheid</p>
		  <div>
			<span></span><span></span><span></span><span></span><span></span>
		  </div>
		  <p>Diepte</p>
		  <div>
			<span></span><span></span><span></span><span></span>
		  </div>
		</div>
		<button>Volgende</button>
	  </div>
	</div>
  </main>
  
  <footer>
	<p>Footer content here</p>
  </footer>
  