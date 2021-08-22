<h1 align='center'>Example organization <b>CSS</b> propertys</h1>

```CSS
.app {
    /* positioning */
    position: absolute;
    top: 0;
    left: 0;
    z-index: 10;

    /* display stuff */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

    /* box-model */
    width: 100%;
    min-height: 100vh;
    padding: 2rem 3rem;
    margin: 0 auto;

    /* typography */
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 3rem;
    text-align: center;
    line-height: 2;
    letter-spacing: .25px;

    /* formalization */
    transform: rotate(45deg);
    filter: blur(1px);
    opacity: 0.5;
    background: #999;
    border: 2px dashed #333;

    /* animation */
    transition: all 0.5s ease;

    /* mics */
    cursor: pointer;
    will-change: auto;
}
```