<link rel="stylesheet" href="style_general.css" />
<link rel="stylesheet" href="style_specific.css" />
<script src="style.js"></script>

<div onload="onLoad()"></div>

![Prototype Toolset](./banner/prototype_toolset-banner.webp)

<button class="tab" onclick="loadModule('1', this)">main</button>
<button class="tab" onclick="loadModule('2', this)">roll</button>
<button class="tab" onclick="loadModule('3', this)">character builder</button>
<button class="tab" onclick="loadModule('4', this)">monster builder</button>

<div id="1" class="tabcontent">
    <div class="container">
        <h2></h2>
    </div>
</div>

<div id="2" class="tabcontent">
    <div class="container">
        <div class="box">
            <h2>skill check</h2>
            <button class="d100" value="1" onclick="skillCheck(this)">1</button>
            <button class="d100" value="2" onclick="skillCheck(this)">2</button>
            <button class="d100" value="3" onclick="skillCheck(this)">3</button>
            <button class="d100" value="4" onclick="skillCheck(this)">4</button>
            <button class="d100" value="5" onclick="skillCheck(this)">5</button>
            <button class="d100" value="6" onclick="skillCheck(this)">6</button>
        </div>
        <div class="box">
            <h2>damage roll</h2>
            <button class="d10" value="1" onclick="damageRoll(this)">1</button>
            <button class="d10" value="2" onclick="damageRoll(this)">2</button>
            <button class="d10" value="3" onclick="damageRoll(this)">3</button>
            <button class="d10" value="4" onclick="damageRoll(this)">4</button>
            <button class="d10" value="5" onclick="damageRoll(this)">5</button>
            <button class="d10" value="6" onclick="damageRoll(this)">6</button>
        </div>
    </div>
</div>

<div id="3" class="tabcontent">
    <div class="container">
        <p>character builder</p>
    </div>
</div>

<div id="4" class="tabcontent">
    <div class="container"></div>
</div>