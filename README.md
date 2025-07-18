# 📱 Huddle Landing Page - Minha Jornada de Desenvolvimento
<img width="1889" height="934" alt="image" src="https://github.com/user-attachments/assets/e7980a45-8511-4c44-ac93-413eef77a087" />
<img width="396" height="862" alt="image" src="https://github.com/user-attachments/assets/04d544b8-c4bc-41b1-b788-052753949ca7" />


## 📌 Visão Geral
Landing page responsiva para a Huddle, desenvolvida como desafio do Frontend Mentor e Quest (HTML + CSS) do curso DEV QUEST. Superei vários desafios técnicos para criar esta página que demonstra minhas habilidades em front-end.

## 🛠 Tecnologias
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## 🎯 Desafios & Soluções

### 1. 🔄 Layout Responsivo
**Problema:**  
A página quebrava em telas menores

**Solução:**  
```css
@media (max-width: 768px) {
  .main-container {
    flex-direction: column;
    padding: 2rem;
  }
}
```
### 2. Posicionamento de Imagens
Problema:
A ilustração não alinhava com o texto

Solução:
Ajustei as propriedades Flexbox e adicionei:

```css
.imagem-container {
  margin-right: auto;
  max-width: 50%;
}
```


### 3. 🔑 Autenticação no GitHubProblema:
Erros 403 ao fazer push

Solução:
Gerei token de acesso com permissão repo
Configurei o remote

