<section class="homepage" id="home">
  <h1>I</h1>
    <svg height="120px" width="120px" class="heart-svg" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512" xml:space="preserve" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <path d="M474.655,74.503C449.169,45.72,413.943,29.87,375.467,29.87c-30.225,0-58.5,12.299-81.767,35.566 c-15.522,15.523-28.33,35.26-37.699,57.931c-9.371-22.671-22.177-42.407-37.699-57.931c-23.267-23.267-51.542-35.566-81.767-35.566 c-38.477,0-73.702,15.851-99.188,44.634C13.612,101.305,0,137.911,0,174.936c0,44.458,13.452,88.335,39.981,130.418 c21.009,33.324,50.227,65.585,86.845,95.889c62.046,51.348,123.114,78.995,125.683,80.146c2.203,0.988,4.779,0.988,6.981,0 c2.57-1.151,63.637-28.798,125.683-80.146c36.618-30.304,65.836-62.565,86.845-95.889C498.548,263.271,512,219.394,512,174.936 C512,137.911,498.388,101.305,474.655,74.503z"></path> <path d="M160.959,401.243c-36.618-30.304-65.836-62.565-86.845-95.889 c-26.529-42.083-39.981-85.961-39.981-130.418c0-37.025,13.612-73.631,37.345-100.433c21.44-24.213,49.775-39.271,81.138-43.443 c-5.286-0.786-10.653-1.189-16.082-1.189c-38.477,0-73.702,15.851-99.188,44.634C13.612,101.305,0,137.911,0,174.936 c0,44.458,13.452,88.335,39.981,130.418c21.009,33.324,50.227,65.585,86.845,95.889c62.046,51.348,123.114,78.995,125.683,80.146 c2.203,0.988,4.779,0.988,6.981,0c0.689-0.308,5.586-2.524,13.577-6.588C251.254,463.709,206.371,438.825,160.959,401.243z"></path> </g></svg>  
      <h2>Web</h2>
  <div class="homepage-bottom">
      <a href="#learning-journal"><svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 32 32"><path fill="#00f" fill-rule="evenodd" d="m22.535 16.88-5.656 5.66a.962.962 0 0 1-.879.25.962.962 0 0 1-.879-.25l-5.656-5.66a1.006 1.006 0 0 1 0-1.42 1 1 0 0 1 1.414 0L15 19.59V9a1.001 1.001 0 0 1 2 0v10.59l4.121-4.13a1 1 0 0 1 1.414 0c.391.4.391 1.03 0 1.42ZM16 0C7.163 0 0 7.16 0 16s7.163 16 16 16 16-7.16 16-16S24.837 0 16 0Z"/></svg></a>
  </div>
</section>



<section class="learning-journal" id="learning-journal">
  <h2>Learning Journal</h2>

<div class="block-grid">
<section class="sprint-13-block">
  <h3>Sprint 13</h3>
</section>

<section class="sprint-14-block">
  <h3>Sprint 14</h3>
</section>

<section class="sprint-15-block">
  <h3>Sprint 15</h3>
</section>

<section class="sprint-16-block">
  <h3>Sprint 16</h3>
</section>

<section class="sprint-17-block">
  <h3>Sprint 17</h3>
</section>

<section class="sprint-18-block">
  <h3>Sprint 18</h3>
</section>

<section class="sprint-19-block">
  <h3>Sprint 19</h3>
</section>

<section class="sprint-20-block">
  <h3>Sprint 20</h3>
</section>
</div>

</section>

<style>

  .learning-journal{
    height: 100vh;

    & h2{
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 5vh;
    }
  }
  .block-grid{
    display: grid;
    place-items: center;
    grid-template-columns: 1fr 1fr;
    gap: 1em;
    padding: 10px;

    & section{
      height: 175px;
      width: 175px;
      border-radius: 10px;
      transition: 0.2s;

      &:hover{
        transform: scale(1.1);
        cursor: pointer;
      }
    }
  }

.block-grid section:nth-of-type(1){
  background-color: red;
}

.block-grid section:nth-of-type(2){
  background-color: blue;
}

section:nth-of-type(3){
  background-color: green;
}

section:nth-of-type(4){
  background-color: yellow;
}

section:nth-of-type(5){
  background-color: purple;
}

section:nth-of-type(6){
  background-color: orange;
}

section:nth-of-type(7){
  background-color: pink;
}

section:nth-of-type(8){
  background-color: coral;
}


</style>