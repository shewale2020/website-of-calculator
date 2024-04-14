# website-of-calculator*{
    margin: 0;
    padding: 0;
    font-family: Cambria;
    box-sizing: border-box;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100%;
    margin: 0;
    background-color: rgb(248,239,239);
}
.Calculator{
    background-color: #3a4452;
    padding: 20px;
    border-radius: 10px;
    width: 25%;
}
#display{
    width: 95%;
    height: 100%;
    font-size: 18px;
    margin-bottom: 10px;
    padding: 5px;
}
.buttons{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 10px;
}
button{
    font-size: 16px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    cursor: pointer;
    background-color: #fff;
}
.operator{
    border: 0;
    outline: 0;
    border-radius: 10px;
    box-shadow: -8px -8px 15px rgba(255,255,255, 0.1),5px 5px 15px rgba(0,0,0,0.2);
    background: transparent;
    font-size: 20px;
    color: white;
    cursor: pointer;
    margin: 10px;
}
#calculate{
    background-color: white;
    margin: 10px;
}
#clear{
    background-color: white;
    margin: 10px;
}
