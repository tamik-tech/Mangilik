/* Стили для страницы */
body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background: linear-gradient(135deg, #002147, #0a1e38);
  color: white;
  text-align: center;
}

.hero {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

header h1 {
  font-size: 3rem;
  margin: 0;
  color: #f7c04a;
}

header p {
  font-size: 1.2rem;
  color: #d1d1d1;
  margin-top: 10px;
}

.highlight {
  color: #f7c04a;
}

.cta-button {
  background: #f7c04a;
  color: #002147;
  border: none;
  padding: 15px 30px;
  font-size: 1.2rem;
  font-weight: bold;
  margin-top: 20px;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s ease;
}

.cta-button:hover {
  background: #e0a839;
}

footer {
  position: absolute;
  bottom: 10px;
  width: 100%;
  font-size: 0.9rem;
  color: #b3b3b3;
}