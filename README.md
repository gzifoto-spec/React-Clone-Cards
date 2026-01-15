# React Clone Cards  
A tiny React exercise: clone a “card” component and practice passing props.

**What this repo is**
- A teaching demo built by Prof. Ana Aragón ([@anaaragon88](https://github.com/anaaragon88))  
- Starter code is a single `App.jsx` that renders one card; students fork it, add two more cards, push back to GitHub.

<img width="300" alt="localhost page Screenshot" style="float" align="right" src="https://github.com/user-attachments/assets/90df9d59-60a3-47e7-9b2c-602754817322" />

**Quick start**
```bash
git clone https://github.com/YOUR-USERNAME/React-Clone-Cards.git
cd React-Clone-Cards
npm install
npm run dev
      import './App.css';
      import Testimonio from './components/Testimonio.jsx';
      function App() {
        return (
          <div className='App'>
              <h1>Esto es lo que dicen nuestros alumnos sobre freeCodeCamp:</h1>
              <Testimonio 
      					nombre='Emma Bostian'
                pais='Suecia'
                imagen='emma'
                cargo='Ingeniera de Software'
                empresa='Spotify'
                testimonio='Siempre he tenido problemas para aprender JavaScript. He tomado muchos cursos, pero el curso de freeCodeCamp fue el que se quedó. Estudiar JavaScript, así como estructuras de datos y algoritmos en freeCodeCamp me dio las habilidades y la confianza que necesitaba para conseguir el trabajo de mis sueños como ingeniero de software en Spotify.'
              />
          </div>
        )
      }
      
      export default App;
```
**Reference**
Design inspiration: **freeCodeCamp** (https://www.freecodecamp.org/espanol/)
