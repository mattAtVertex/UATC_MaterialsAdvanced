# Creating Masked Materials

<p><span style="font-size: 14pt;"><strong>The Process:<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19598/preview?verifier=vE8MFQzAjXwd8wrSMlB3ALoFFLlIhSGjMFJFvuzx" alt="image.png" width="441" height="251" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19598" data-api-returntype="File"></strong></span></p>
<p><strong>There are two ways this can be achieved</strong></p>
<ul>
<li>With an outside alpha embedded in a texture or stand alone<br>in a texture’s alpha data plugged into Opacity</li>
<li>Or through color channels</li>
</ul>
<p><strong><span style="font-size: 14pt;">Using Minus Nodes and Clamps</span></strong></p>
<ul>
<li>Create or use the Black and white texture given Create a Texture Sample</li>
<li>Create a one minus if you need to flip the masking effect. done here to make gold trim.</li>
<li>Create a Clamp to keep things in range if parameters are introduced for control, and if someone programs into your shader, they will see you have</li>
<li><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19599/preview?verifier=31srSyBCp5Tev6jDIsJvbRKI45MwB3t6lArxDoN9" alt="image.png" width="460" height="239" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19599" data-api-returntype="File">&nbsp;a Clamp to keep things in a certain range.</li>
</ul>
<p><strong><span style="font-size: 14pt;">Using the Lerp Node</span></strong></p>
<ul>
<li>Create a Lerp Node and Run the One Minus into the Alpha input of the Lerp</li>
<li>Duplicate that Process for the Metal Texture</li>
<li></li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>