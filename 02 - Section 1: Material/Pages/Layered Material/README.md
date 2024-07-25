# Layered Material

<p><strong><span style="font-size: 14pt;">Use</span></strong><br><em>- The layered materials </em>are used in Unreal to combine elements that can be edited. It’s used to keep executions cleaner. (prevents a noodle fest) Can be used to create - EX: snow on rock, moss on wood.</p>
<p><span style="font-size: 14pt;"><strong>Layered Materials<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19668/preview?verifier=R3Sv4D3PxKthK6onhzugjURcF1371FtLhvPcUS6t" alt="image.png" width="531" height="291" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19668" data-api-returntype="File"></strong></span></p>
<ul>
<li>Make a Material Layer</li>
<li>Call it Grunge - or whatever you like. This first one will be a bit of our noise texture.</li>
<li>Once made, in the Material layer Type in Make Material Attributes</li>
<li>Drag an Albedo and Normal and any other texture items needed to make the material visually dynamic</li>
<li>Once you have them connect them into the Input Attributes node</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19669/preview?verifier=SARbUD0dCmxvoeGEDT4HjtZQkI73rHASYHx7TkwT" alt="image.png" width="514" height="232" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19669" data-api-returntype="File"></p>
<ul>
<li>Convert Each texture into a Parameter so you can make an instance of this material layer and swap out textures when desired easily.</li>
<li>Create another Material layer - call it whatever you like based on its purpose as in dirt or grass or grime. It’s up to you.</li>
<li>Repeat the first process -</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19670/preview?verifier=qvItJRTeq9GBRG1Jjl3DZylBv5YnbCEbBvX5LRj6" alt="image.png" width="727" height="249" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19670" data-api-returntype="File"></p>
<ul>
<li>Now create a Master material.</li>
<li>In your master Material right click and type Material Attribute Layers</li>
<li>In the Material properties of the material (you can get there by clicking on the grid once). Go to the settings and Click on the tick box to Use Material Attributes</li>
</ul>
<p>&nbsp;</p>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19672/preview?verifier=xduVlezQVZyn3XMlEeNJdNqP5YTHAzlnKvezmqmo" alt="image.png" width="727" height="435" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19672" data-api-returntype="File"></p>
<ul>
<li>Select the Material Library (Material Attribute Layer Node you made) In the master and load the desired background you want.</li>
<li>From there hit the plus and load the other material made.</li>
<li>Right click in your content browser and Make another Material layer Blend - load in the Blend Asset slot.</li>
<li>Keep the node structure and for this simple one, just add an alpha condition by simply adding a scalar<br>parameter. Right click and Type Scalar Parameter or hit the S hotkey.
<ul>
<li>Can leave the numbers as is.</li>
<li>This is a simple Blend</li>
</ul>
</li>
</ul>
<p>&nbsp;</p>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19673/preview?verifier=vYcjYelA7lEXvzjlkFWYZjJKRR3IMvYReWfbMCqQ" alt="image.png" width="454" height="201" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19673" data-api-returntype="File"><img src="https://vertexschool.instructure.com/courses/311/files/19674/preview?verifier=62LxlTnaC1caLUbGTIapqeuqA7q9wYkJy1vMw5It" alt="image.png" width="572" height="198" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19674" data-api-returntype="File"></p>
<ul>
<li>Now go to the Master Material and Connect the Material Attributes Layer to the Master Material.</li>
<li>Load the simple Material blend that was made in the Master Material</li>
<li>Now Make an instance of the Master Material.</li>
</ul>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19675/preview?verifier=WdJqjQVJobsX5uFf7teFbUsq5DAxs2mlHusAjZyc" alt="image.png" width="426" height="562" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19675" data-api-returntype="File"></p>
<ul>
<li>Now you have an Alpha slot in the instance that you can turn on and manipulate - Layer parameters tab</li>
<li>Now if we needed a more complex blend, we can create another Material Layer Blend with an Alpha in place to get a more realistic effect instead of an overall fade in and out.</li>
<li>You can also create new layers quickly with established layers or ones you have built and swap then out with a plus button at the top speeding the process up once you have ones to choose from.</li>
</ul>
<p>PRO TIP: be careful to not make too many layers as you will cause the materials complexity to grow. Pick and choose the best parts. This system makes things cleaner but not necessarily lighter.</p>
<p><img src="https://vertexschool.instructure.com/courses/311/files/19677/preview?verifier=97GUdUOi3vXFzrg8tNWFba79GRUYNQkcg3qQqABh" alt="image.png" width="613" height="202" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19677" data-api-returntype="File"></p>