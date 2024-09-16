# Calculator-1
body {
    margin: 0;
    padding: 0;
    line-height: 0.5;
    background: linear-gradient(to left, #92c40a, #92c40a); 
    font-family: sans-serif;
}

.calci {
    width: 500px;
    padding-top: 100px;
    padding-bottom: 100;
    position: absolute;
    top: 50%;
    left: 70%;
    transition: 0.25px;
    transform: translate(-50%, -50%);
    text-align: center;
}

#zero {
    height: 55;
    width: 116;
    font-size: 20;
    font-family: sans-serif;
    font-weight: 300;
}

#display {
    border: none;
    background: black;
    border-radius: 30px;
    width: 245;
    font-size: 20;
    font-family: sans-serif;
    font-weight: 300;
    height: 60;
    margin: auto;
    border: 2px solid white(5, 218, 255, 0.726);
    color: whitesmoke;
}

.button {
    width: 55;
    height: 55;
    padding-top: -1;
    font-size: 20;
    border: none;
    background: black;
    font-family: sans-serif;
    font-weight: 300;
    border: 0;
    border-radius: 30px;
    margin: 1.5;
    transition: 0.25px;
    color: whitesmoke
}

h1 {
    margin-top: 300px;
    margin-left: 100px;
    font-family: sans-serif;
    font-size: 50;
    text-decoration: underline;
    color: blueviolet;
    text-transform: uppercase;
    font-weight: 700;
}

.operator {
    width: 55;
    height: 55;
    padding-top: -1;
    font-size: 20;
    text-align: center;
    color: whitesmoke;
    border: none;
    background: black;
    font-family: sans-serif;
    font-weight: 500;
    border: 0;
    border-radius: 30px;
    margin: 1.5;
    transition: 0.25px;
    cursor: pointer;
}

.operator:hover {
    background: hsl(245, 31%, 30%);
}
