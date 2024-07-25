# How Foilage Shaders Work and Shader Model Properties

<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19665/preview?verifier=ih4mj4cE91ycFYZ0YD3zFnXD4Dj2EHoZyYQlAq0N" alt="image.png" width="463" height="694" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19665" data-api-returntype="File"></p>
<p><strong><span style="font-size: 14pt;">How Foilage Shaders Work and Shader Model Properties: </span></strong><span style="font-size: 14pt;"><strong>Shading Models: Two Sided Foliage</strong></span></p>
<p>
</p><ul>
<li>Helps give foliage a more natural and uniform look when being lit</li>
<li>Uses a variation of the Subsurface scattering lighting model<br>
<ul>
<li>Simulates light transmission</li>
</ul>
</li>
</ul>
<p></p>
<p><span style="color: #e03e2d;">NOTE: If using Lumen Super Temporal Resolution will blur out the WPO effect. To remedy this got to the Project Settings &gt; Velocity Pass &gt; and switch to Write During Base Pass</span></p>
<ul>
<li>Create a new Material.</li>
<li>Set the Blend Mode to Masked.</li>
<li>Set the Shading Model to Two-Sided Foliage. This adds some Opacity options and Subsurface together.</li>
<li>Drag in the texture details desired.</li>
</ul>