
# What is CSS
[CSS](https://en.wikipedia.org/wiki/CSS) is a language that allows for maniputlation of style, color and design of documents that utilize markup languages such as HTML and XML. CSS was first released in 1996 and was written by HÃ¥kon (Haw-kon) Wium Lie 

### Terms Used in Tutorial
<details>
    <summary>Property</summary>
    A property is an aspect of an element that can be set using CSS to change the design of an HTML element. IE: Color, Background Color, Font Size, etc.
</details>
<details>
    <summary>Padding</summary>
    Padding refers to the space that surrounds an elements content within said element.
</details>
<details>
    <summary>Margin</summary>
    Margin refers to the space around an element's border.
</details>
<details>
    <summary>Border</summary>
    The border of an element is the line that surrounds the elements, however while the border isn't always displayed it acts as a framing device for the element.
</details>
<details>
    <summary>Positioning</summary>
    Positioning refers to the location that a element will be displayed on a screen, as well as whether the element will be able to move on the screen.
</details>

### Code Examples
<details>
    <summary>Changing the Font Size and Family</summary>
    <pre><code>&lt;style&gt;
    p{
			text-align: center;
			font-family: alexei;
			}
	&lt;/style&gt;
    &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec imperdiet nunc, eu dignissim ipsum. Curabitur varius nisl eu arcu pellentesque, sit amet venenatis est mattis. &lt;/p&gt;</code></pre>
    <!--<style>
    #p1{
			text-align: center;
			font-family: alexei;
			}
    </style>
    <p id = 'p1'>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec imperdiet nunc, eu dignissim ipsum. Curabitur varius nisl eu arcu pellentesque, sit amet venenatis est mattis.</p>-->
    <img src=Font-for-MD-Page.png>
</details>
<details>
    <summary>Changing the background and borders of an element</summary>
    <pre><code>&lt;style&gt;
    button{
			background-color: Orange;
			border-width: thick;
			}
	&lt;/style&gt;&lt;button type="button" onclick="alert('Hello world!')"&gt;Click Me!&lt;/button&gt;</code></pre>
    <!--<style>
         #button1{
			background-color: Orange;
			border-width: thick;
			}
    </style>
    <button type="button" onclick="alert('Hello world!')">Click Me!</button>
    <button id = 'button1'type="button" onclick="alert('Hello world!')">Click Me!</button>-->
    <img src=Buttons-for-MD-Page.png>
</details>
<details>
    <summary>Customized Content containers.</summary>
    <pre><code>
    &lt;style&gt;
    #div1{
		background-color: white;
        color: black;
        border-radius: 15px;
        text-align: center;
        font-family: alexei;text-align: center;
		font-family: alexei;
	}
    #div2{
        border-color: orange;
        border-radius: 12px;
        color: brown;
        width: 25%;
        text-align: right;
        font-family: fantasy;
    }
    &lt;/style&gt;
    &lt;div Id = 'div1'&gt;&lt;p&gt;Informaiton seperated by a divider.&lt;/p&gt;&lt;/div&gt;&lt;div id='div2'&gt;&lt;p&gt; information seperated from the other using a divider.&lt;/p&gt; &lt;/div&gt;</code></pre>
    <!--<style>
    #div1{
    background-color: white;
    color: black;
    border-radius: 15px;
    text-align: center;
    font-family: alexei;
    }
    #div2{
    background-color: orange;
    border-radius: 12px;
    color: brown;
    width: 25%;
    text-align: right;
    font-family: fantasy;
    }</style>
    <div id='div1'><p>Information seperated by a divider.</p></div><div  id=div2><p>Information seperated form the other using a divider.</p></div>-->
    <img src=Div-Image-for-MD.png>
</details>
<p align = "center"><a href='https://github.com/JusticeGtrrz/FinalProject-DigitalSystems/blob/main/README.md'>Back to README</a></p>

