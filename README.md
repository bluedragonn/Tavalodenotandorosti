/* پایه */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  direction: rtl;
  font-family: Tahoma, sans-serif;
}

body {
  background: linear-gradient(to right, #e0f2f1, #f1f8e9);
  color: #333;
  line-height: 1.8;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 2rem;
}

/* هدر */
header {
  background-color: #004d40;
  color: white;
  padding: 1rem 0;
}

header h1 {
  text-align: center;
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  gap: 1.5rem;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  text-decoration: underline;
}

/* بخش قهرمان */
.hero {
  background: url('https://images.unsplash.com/photo-1612832021454-25e5f5c8d722?auto=format&fit=crop&w=1400&q=80') no-repeat center/cover;
  color: white;
  text-align: center;
  padding: 5rem 2rem;
  text-shadow: 1px 1px 5px rgba(0,0,0,0.6);
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

/* بخش‌ها */
.section {
  padding: 3rem 0;
  background: white;
  margin: 1rem 0;
  border-radius: 16px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

.section h2 {
  color: #00695c;
  margin-bottom: 1rem;
  text-align: center;
}

.section p,
.section ul {
  font-size: 1.1rem;
}

/* کارت‌ها */
.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
  margin-top: 2rem;
}

.card {
  background-color: #e0f7fa;
  padding: 1rem;
  border-radius: 12px;
  width: 280px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  text-align: center;
}

.card h3 {
  color: #00796b;
  margin-bottom: 0.5rem;
}

/* لیست عوارض */
.effects ul {
  list-style: disc;
  padding-right: 1.5rem;
}

/* فوتر */
footer {
  background-color: #004d40;
  color: white;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
  font-size: 0.9rem;
}

/* موبایل */
@media (max-width: 768px) {
  .cards {
    flex-direction: column;
    align-items: center;
  }

  .hero h2 {
    font-size: 1.8rem;
  }
}
