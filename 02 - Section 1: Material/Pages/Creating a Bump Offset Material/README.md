# Creating a Bump Offset Material

<p><span style="font-size: 14pt;"><strong>Creating a Bump Offset Material<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19659/preview?verifier=2y5YsehU2hCLleRWhpDdIOTgyXxkx2L8zptVtuol" alt="image.png" width="378" height="286" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19659" data-api-returntype="File"></strong></span><br>To get your material to have a bit more depth you can add a Bump Offset Node. This will give the appearance of air bubbles trapped in a precious stone or ice.</p>
<p>&nbsp;</p>
<ul>
<li>Create a new Material</li>
<li>Add any texture from Mega Scans in the file given (or really any you prefer - doesn’t matter)</li>
<li>Add a 3 Constant Vector - Change its color to what you want.</li>
<li>Add a Multiply node</li>
<li>Create another Multiply node and add the previous to it to the A channel.</li>
<li></li>
</ul>
<hr>
<ul>
<li>Create 2 Noise nodes.<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19660/preview?verifier=SnIKfHakHzD0DXFA2tK8NiG3r6cAey4Hzdvhc9rM" alt="image.png" width="378" height="270" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19660" data-api-returntype="File"></li>
<li>First one:<br>
<ul>
<li>Set the First Scale to 0.01</li>
<li>Levels to 5 on the first one to 5</li>
<li>Output min to 0</li>
<li>Output Max to 0.25</li>
<li>Level Scale to 2</li>
</ul>
</li>
<li>Second One:<br>
<ul>
<li>Scale to 0.1</li>
<li>Levels to 6</li>
<li>Output min to 0</li>
<li>Output Max to 0.25</li>
<li>Level Scale to 2</li>
</ul>
</li>
<li>Create a LERP and plug them into the A and B Slots</li>
</ul>
<hr>
<ul>
<li>Create a TextureCoordinate node for UV options (Hotkey U)<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19661/preview?verifier=JJK8cD6DJ9rRsojZ4OnmEutXv2A7OTuUebfI6RS5" alt="image.png" width="602" height="359" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19661" data-api-returntype="File"></li>
<li>Create a Scalar Parameter node keeping it at 1 by default</li>
<li>Create Multiply Node and plug both into it</li>
<li>Now create a BumpOffset node and connect the Multiply into that in the Coordinates</li>
<li>Create a Constant and set it to 0.7 Plug it into the Height</li>
<li>Create a Scalar Parameter and call it InteriorOffset setting the default to 1 and plug into the Height Ratio input of the BO.</li>
<li>Plug the Bump Offset to the UVs of the desired texture.</li>
</ul>
<p>&nbsp;</p>
<ul>
<li>Connect the desired color channel into the Alpha of the LERP</li>
<li>Grab another channel desired and plug into a Multiply B channel.</li>
<li>With the top Multiply final output connect it into the emissive and refraction</li>
</ul>
<p><span style="color: #e03e2d;">NOTE: The BumpOffset gives the material a 3d parallax shif</span><span style="color: #e03e2d;">t effect making it look like there is depth when there is not.</span></p>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19662/preview?verifier=XTH8pZKoHO9qQAUodVy9jh1ww8zawUvcalbWBytE" alt="image.png" width="406" height="381" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19662" data-api-returntype="File"></p>
<p><img src="https://vertexschool.instructure.com/courses/311/files/19663/preview?verifier=LHZQRB9dIDaXdTqZzEn2fYr1XWnsMYOW9bzL0aG7" alt="image.png" width="456" height="257" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19663" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>&nbsp;</p>