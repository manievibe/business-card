the flex box is only concerned with putting the direct child elements in columns

<div class="card">
            <img src="https://media1.popsugar-assets.com/files/thumbor/_NO6aujD-Z5XLuuDS4atzPK97xs/fit-in/2048xorig/filters:format_auto-!!-:strip_icc-!!-/2018/07/19/057/n/44285655/9614c7dbf6e8f91a_GettyImages-533152576/i/Sexy-Drake-Pictures.jpg" class="imgclass" alt="a photo of drake">
            <div>    
                <h3>Emmanuel Onwuka</h3>
                <p>Frontend developer</p>
                <h4> Ago, okota, lagos</h4>
            </div>
        </div>

In the above example, the above class=card contains a display=flex property and the direct children
of the class <div class='card'> are the img tag and the direct <div> element below. These are 
what will be put into columns.