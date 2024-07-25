# What are Material Functions?

<p><span style="font-size: 14pt;"><strong>What are Material Functions?</strong></span></p>
<ul>
<li>Function inputs allow to customize data.</li>
<li>Editing sorting priority allows control on where the new node slot is placed in the Material function in material destination.</li>
</ul>
<p><span style="font-size: 14pt;"><strong>Using Function Inputs<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19603/preview?verifier=tZFdv68d6phovjzvxGamPhTgdQ5RK4cz5p9lZpnD" alt="image.png" width="476" height="278" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19603" data-api-returntype="File"></strong></span></p>
<ul>
<li>Function inputs allow to customize data</li>
<li>Editing sorting priority allows control on where the new node slot is placed in the Material function in material destination.</li>
</ul>
<p><span style="font-size: 14pt;"><strong>Building an Animated Material Function</strong></span></p>
<ul>
<li>Create an <strong>Material Function</strong> Right click on the content browser &gt; materials and textures.</li>
<li>Then open it up and create this system - inclass exercise (not as hard as it seems). Sample<br><strong></strong></li>
<li><strong>Function Inputs </strong>are key each allow for more functionality in this material, allowing for customization.</li>
</ul>
<p><span style="font-size: 14pt;"><strong>Using a Material Function in a Master Material<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19604/preview?verifier=KC49n0g4XAGHPkWjbwo3SBUme6pDb0QHFqK7YyKi" alt="image.png" width="475" height="255" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19604" data-api-returntype="File"></strong></span></p>
<ul>
<li><span style="font-size: 12pt;">Select the main material node and change the Material Domain to Light function and make sure it castsshadows<br></span></li>
<li><span style="font-size: 12pt;">Then call up a material function in the graph You can technically just drag it in.<br></span></li>
<li><span style="font-size: 12pt;">Specify the MF_4Waymotion02 (or whatever you called it)<br></span></li>
<li><span style="font-size: 12pt;">Now connect a TextCoordinate and Scalar param to a multiply then to the MF material function<br></span></li>
<li><span style="font-size: 12pt;">Then connect Caustic Softer Texture to the Texture node then to the emissive.<br></span></li>
<li><span style="font-size: 12pt;">Once done we connect it to our light under the light function</span></li>
</ul>