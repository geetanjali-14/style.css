# style.css
body{
    color: black;
    background-color:coral ;
    text-align: center;
    /* background-size: 100px 100px, cover,cover; */
    background-position: top left,center center,bottom center; */
    background-repeat: repeat,no-repeat,no-repeat;
     background-attachment: fixed,fixed,fixed;
}

#section{

    margin-left: 10%;
}

.css-button {
    border: 5px solid #dc333300;
    height: 51px;
    width: 218px;
    position: absolute;
    left: 44%;
    margin: auto;
    overflow: hidden;
    cursor: pointer;
    color: white;

}

h1{
    font-weight: 600;
    line-height: 1.5;
    margin: 0 0 1rem 0;
    text-transform: uppercase;
    letter-spacing: 0.1rem;
    font-family: sans-serif;
}

p.css-button-text {
    width: 100%;
    position: absolute;
  }

  .css-button-inner {
    height: 51px;
    width: 265px;
    position: relative;
    left: -4px;
    top: -1px;
    border: 2px solid #dcb124;
    background-color: #2ad3c2;
    text-align: center;
    -webkit-transform: skew(-42deg) translate(300px,0);
    -moz-transform: skew(-42deg) translate(300px,0);
    -o-transform: skew(-42deg) translate(300px,0);
    transform: skew(-42deg) translate(300px,0);
    -webkit-animation-name: buttonx-out;
    -webkit-animation-duration: .7s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
    -moz-animation-name: buttonx-out;
    -moz-animation-duration: .7s;
    -moz-animation-iteration-count: 1;
    -moz-animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
    animation-name: buttonx-out;
    animation-duration: .7s;
    animation-iteration-count: 1;
    animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
  }

  
  .css-button:hover > .css-button-inner {
    -webkit-animation-name: buttonx-in;
    -webkit-animation-duration: .6s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
    -moz-animation-name: buttonx-in;
    -moz-animation-duration: .6s;
    -moz-animation-iteration-count: 1;
    -moz-animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
    animation-name: buttonx-in;
    animation-duration: .6s;
    animation-iteration-count: 1;
    animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
    -moz-transform: skew(-42deg) translate(-20px, -0px);
    -o-transform: skew(-42deg) translate(-20px, -0px);
    transform: skew(-42deg) translate(-20px, -0px);
  }

  @keyframes buttonx-in {
    from {transform:skew(-42deg) translate(-300px, 0);}
    to {transform:skew(-42deg) translate(-20px, -0px);}
}

@keyframes buttonx-out {
    from {transform: skew(-42deg) translate(0, 0);}
    to {transform: skew(-42deg) translate(300px, -0px);}
}

@-webkit-keyframes buttonx-in {
    from {transform:skew(-42deg) translate(-300px, 0);}
    to {transform:skew(-42deg) translate(-20px, -0px);}
}

@-webkit-keyframes buttonx-out {
    from {transform: skew(-42deg) translate(0, 0);}
    to {transform: skew(-42deg) translate(300px, -0px);}
}

.reset-skew {
    -moz-transform: skew(40deg);
    -o-transform: skew(40deg);
    transform: skew(40deg);
  }

  .flat-table {
    margin-bottom: 20px;
    border-collapse:collapse;
    font-family: Arial, Helvetica, sans-serif;
    border: none;
            border-radius: 5px;
           -webkit-border-radius: 3px;
           -moz-border-radius: 3px;
           position: relative;
           left: 30%;
}
.flat-table th, .flat-table td {
    box-shadow: inset 0 -1px rgba(0,0,0,0.25),
        inset 0 1px rgba(0,0,0,0.25);
}
.flat-table th {
    font-weight: normal;
    -webkit-font-smoothing: antialiased;
    padding: 1em;
    color: rgb(0, 0, 0);
    text-shadow: 0 0 1px rgba(191, 4, 4, 0.1);
    font-size: 1.5em;
}
.flat-table td {
    color: white;
    padding: 0.7em 1em 0.7em 1.15em;
    text-shadow: 0 0 1px rgba(255,255,255,0.1);
    font-size: 1.4em;
}
.flat-table tr {
    -webkit-transition: background 0.3s, box-shadow 0.3s;
    -moz-transition: background 0.3s, box-shadow 0.3s;
    transition: background 0.3s, box-shadow 0.3s;
}
.flat-table-1 {
    background: goldenrod;
}
.flat-table-1 tr:hover {
    background: rgba(0,0,0,0.19);
}

