# React Clone Cards  
A tiny React exercise: clone a “card” component and practice passing props.

**What this repo is**
- A teaching demo built by Prof. Ana Aragón ([@anaaragon88](https://github.com/anaaragon88))  
- Starter code is a single `App.jsx` that renders one card; students fork it, add two more cards, push back to GitHub.

<img width="250" alt="localhost page Screenshot" style="float" align="right" src="https://github.com/user-attachments/assets/90df9d59-60a3-47e7-9b2c-602754817322" />

**Reference**
Design inspiration: **freeCodeCamp** (https://www.freecodecamp.org/espanol/)

**Starting point App.jsx code:**
```bash
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

**Quick start**
```bash
git clone https://github.com/YOUR-USERNAME/React-Clone-Cards.git
cd React-Clone-Cards
npm install
npm run dev
```
**Completed App.jsx code**  
*(also in repository files)*
```bash
import './App.css';
import Testimonio from './components/Testimonio.jsx';
function App() {
  return (
    <div className='App'>
        <h1>Esto es lo que dicen nuestros alumnos sobre freeCodeCamp:</h1>
        <Testimonio 
					nombre='Shawn Wang'
          pais='Singapur'
          imagen='shawn'
          cargo='Ingeniero de Software'
          empresa='Amazon'
          testimonio='Da miedo cambiar de carrera. Solo gané la confianza de que podía programar trabajando a través de los cientos de horas de lecciones gratuitas en freeCodeCamp. Dentro de un año tuve un trabajo de seis cifras como ingeniero de software. freeCodeCamp cambió mi vida.'
        />
        <Testimonio 
					nombre='Sarah Chima'
          pais='Nigeria'
          imagen='sarah'
          cargo='Ingeniera de Software'
          empresa='ChatDesk'
          testimonio='freeCodeCamp fue la puerta de entrada a mi carrera como desarrollador de software. El plan de estudios bien estructurado llevó mis conocimientos de programación de un nivel de principiante total a un nivel muy seguro. Era todo lo que necesitaba para conseguir mi primer trabajo de desarrollador en una empresa increíble.'
        />
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
