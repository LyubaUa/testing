# -html,
body {
    margin: 0;
    padding: 0;
}

body {
    width: 550px;
    height: 300px;
    font-size: 12px;
    font-family: Tahoma, Arial, sans-serif;
}

.profile {
    padding: 5px 10px;
}

.profile img {
    display: block;
    padding: 10px;
    border: 2px solid #34495e;
    border-radius: 8px;
}

.profile .photo {
    float: left;
    width: 152px;
}

.profile .info {
    float: left;
    width: 368px;
    margin-left: 10px;
}

.info h2, h2#info-title {
    margin: 0 !important;
    padding: 10px !important;
    font-weight: normal;
    font-size: 12px;
    color: #ffffff;
    background: #34495e;
    border-radius: 4px;
}

.profile .info div.fact {
    padding: 10px;
    background: white;
}

.profile .info div.fact:nth-child(odd) {
    background: #ecf0f1;
}

.profile .info .fact::after {
    content: "";
    display: table;
    clear: both;
}

.fact div.title {
    float: left;
    width: 120px;
    text-align: right;
    color: #7f8c8d;
}

.fact div.value {
    margin-left: 140px;
    color: #34495e;
}



.profile .info .albums {
    margin-top: 5px;
}

 
#miska, .albums img{
    float: left;
    margin-right: 5px;
}

.albums img:last-child {
    margin-right: 0;
}


.profile .photo .button {
    display: block;
    height: 30px;
    margin: 5px 0;
    line-height: 30px;
    text-align: center;
    color: #ffffff;
    border-radius: 4px;
}

.button.stroke {
    background: #3498db;
}

.button.feed {
    background: #2ecc71;
}

.button.startle {
    background: #e74c3c;
}
