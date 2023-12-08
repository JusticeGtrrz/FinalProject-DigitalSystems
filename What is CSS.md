
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
<details>
    <summary>Grid</summary>
    A CSS grid allows for developers to define a column and row layout for their web designs.
</details>
<details>
    <summary>Opacity</summary>
    Opacity is a property that defines what degree of transparency an element will have.
</details>
<details>
    <summary>Viewport</summary>
    The viewport refers to the total visual area of a webpage that is available to the user.
</details>
<details>
    <summary>Flex</summary>
    The flex property of an element defines how the element will grow or shrink in order to fit the available display.
</details>
<details>
    <summary>Box-Sizing</summary>
    Box-sizing refers to the overall size of the element as it comes to its width and height.
</details>
<details>
    <summary>Rem</summary>
    Rem is a unit of sizing that stands for the root em and will define aspects of the element that will be inherited from the root element.
</details>
<details>
    <summary>vh/vw</summary>
    Vh is an abbriviation for viewport height, while vw stands for viewport width both of these are used to define a percent of the total viewport that should be taken by an element.
</details>
<details>
    <summary>fr</summary>
    Fr stands for Fractional unit and it is a unit of length with-in a defined grid.
</details>
<details>
    <summary>Hexadecimal Color</summary>
    Hexadecimal Color refers a 6-symbol code that represents the value of Red, Green, and Blue that make up a color from 0 to 255.
</details>

### Examples of CSS Code with HTML.
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
    <img src=Pictures-Used-What-Is/Font-for-MD-Page.png>
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
    <img src=Pictures-Used-What-Is/Buttons-for-MD-Page.png>
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
    <img src=Pictures-Used-What-Is/Div-Image-for-MD.png>
</details>
<p align = "center"><a href='https://github.com/JusticeGtrrz/FinalProject-DigitalSystems/blob/main/README.md'>Back to README</a></p>

