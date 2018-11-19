# Gmail Basic HTML Dracula
As stated, this is hacky. I don't expect or really want anybody to use or rely on this. I will not be maintaining this on a regular basis.

I will, however, post some proper CSS files once its done. 

```
/*

Make sure you set HTML View as your default! 

*/
* {
    background-color: #282a36;
    color: #f8f8f8;
}

body,
td {
    font-size: 15px;
}



/* Gmail Logo*/
body > table:nth-child(15) > tbody > tr:nth-child(1) > td:nth-child(1) > h1 > a > img {
    filter: invert(100%);
    background-color: #d7d5c9;
}


/* Compose Button */
body > table:nth-child(16) > tbody > tr > td:nth-child(1) > table.m > tbody > tr:nth-child(1) > td > b a {
    background-color: #FF5555;
    padding: 7px 10px 5px 10px;
    position: relative;
    top: 0px;
    font-size: 0.8em;
    line-height: 2em;
    font-weight: 400;
}


/* Header Search */
#sbq {
    border: 1px solid #44475a!important;
    margin: 0 10 0 5;
}



/* Top Border */
.gbh,
.gbd {
    border-top: 1px solid #44475a;
    font-size: 1px;
}



/* Top Buttons */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table:nth-child(1) > tbody > tr > td:nth-child(2) > form > table:nth-child(4) > tbody > tr > td {
    padding: 0px 0px 15px 0px;
    background-color: #282a36;
}




/* Inbox */
body > table:nth-child(16) > tbody > tr > td:nth-child(1) > table.m > tbody > tr:nth-child(3) > td,
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table:nth-child(1) > tbody > tr > td {
    background-color: #282a36;
}


/* Unread Senders Colored */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table > tbody > tr > td:nth-child(2) > form > table.th > tbody > tr > td:nth-child(2) > b {
    color: #FF5555;
}


/* Bottom Buttons */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table:nth-child(1) > tbody > tr > td:nth-child(2) > form > table:nth-child(6) > tbody > tr > td {
    background-color: #282a36;
    padding: 14px 0 0 0;
}



/* Bottom Buttons */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table:nth-child(1) > tbody > tr > td:nth-child(2) > form > table.th > tbody > tr {
    background-color: #f5f5f5;
}


/* Table Border */
.th td,
.th th {
    border-bottom: 0.5px solid #44475a
}



/* Top Links and Label Links */
a:link,
a:active,
a:visited,
a.gb1.cleaned,
a.cleaned {
    color: #f8f8f8!important;
    text-decoration: none!important;
}
a.gb1.cleaned:hover,
a.cleaned:hover {
    color: #ffb86c;
    text-decoration: none!important;
}


/* Footer Span */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table.ft > tbody > tr:nth-child(2) > td > span {
    color: #f8f8f2!important
}

.bn td {
    border: 1px solid #44475a
}

#gbar,
#guser {
    font-size: 80%;
    padding-right: 0px;
    padding: 6px 2px 0 2!important;
}




/* Preview Date */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table:nth-child(1) > tbody > tr > td:nth-child(2) > form > table.th > tbody > tr > td:nth-child(4) {
    font-size: 55%;
    text-transform: uppercase;
    padding: 0 10 0 20;
    font-weight: 700
}



/* Preview Body */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table:nth-child(1) > tbody > tr > td:nth-child(2) > form > table.th > tbody > tr > td:nth-child(3) > a > span > font {
    color: #6272a4;
}



/* Labels Header */
.lb h2 {
    font-weight: bold;
    font-size: 85%;
    text-decoration: underline;
    padding: 0 0 20px 0;
}



/* Labels */
body > table:nth-child(16) > tbody > tr > td:nth-child(1) > table.l > tbody > tr > td > a {
    padding: 0 0 0 5;
    line-height: 1.4em
}

.ml {
    margin-left: 0;
}

body > table:nth-child(16) > tbody > tr > td:nth-child(1) > table.l > tbody > tr > td > a.ml.cleaned {
    line-height: 40px;
    padding: 5px 10px;
    border: 1px solid #44475a;
    background-color: #44475a;
    color: #e5e5e5!important;
    font-size: 0.8em
}



/* Buttons */
select,
input[type="submit"] {
    border-color: #44475a;
    background-color: #44475a;
    color: #f8f8f8;
    font-size: 0.8em;
    padding: 5px 10px;
}
select {
    border: 4px solid #44475a;
}



/* Hide the Star IMG and Replace it */
body > table:nth-child(16) > tbody > tr > td:nth-child(1) > table.m > tbody > tr:nth-child(4) > td > a > img {
    display: none;
}

body > table:nth-child(16) > tbody > tr > td:nth-child(1) > table.m > tbody > tr:nth-child(4) > td > a:after {
    content: "⭑";
    color: #f1fa8c;
    position: relative;
    top: -1px
}

body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table.ft > tbody > tr:nth-child(2) > td {
    font-size: 0.8em;
    line-height: 2em;
}


/* Hide Mobile Ad */
body > table:nth-child(16) > tbody > tr > td:nth-child(2) > table.ft > tbody > tr:nth-child(1) > td {
    display: none;
}


/* Preferences */

/* Borders */
.prf td {
    border-color: #e5e5e5;
    border-width: 0.5px
}


/* Tabs */
.nav ul li.on {
    background-color: #e5e5e5
}
.nav ul li {
    padding: 4 10px 4 8px;
}


/* Messages */
.r {
    padding: 20px 0 20 0;
}

.r a {
    padding: 5px 10px!important;
    background: #44475a;
    color: #f8f8f8;
    font-size: 1.2em;
}

.msg {
    padding: 20px 0 20px 0;
    border-top: 1px solid #44475a;
    border-bottom: 1px solid #44475a
}

.qr {
    padding: 20px 0 0 0;
}
textarea,
input {
    border: 1px solid #44475a;
}

```
