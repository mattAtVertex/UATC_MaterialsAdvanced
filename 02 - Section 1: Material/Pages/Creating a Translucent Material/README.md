# Creating a Translucent Material

<p><span style="font-size: 14pt;"><strong>Creating a Simple Translucent Material</strong></span><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19656/preview?verifier=o6GAJaTAIBbZ6gruzXgBj3DwETe4wyTln1Knl6dI" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19656" data-api-returntype="File"></p>
<ul>
<li>Create a material and<br>change its Blend Mode to<br>Translucent</li>
<li>Create a Scalar parameters, for the Spec, Rough, and Opacity</li>
<li>Create a 3 Constant Vector to choose your color.</li>
</ul>
<p><img src="https://vertexschool.instructure.com/courses/311/files/19657/preview?verifier=KDUMPl48hMvL58XUkib1ijpkOlOuyYEzHkrCkr8o" alt="image.png" width="343" height="407" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19657" data-api-returntype="File"></p>
<p>&nbsp;</p>
<ul>
<li><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19658/preview?verifier=8BpSDaLVDGjzsQYdXbCmgs3aYvLEmqOcF6FepgcW" alt="image.png" width="414" height="243" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19658" data-api-returntype="File">Create Fresnel Falloff Scalar Parameter and call it Fresnel Falloff and make its default set to 10.</li>
<li>Create a Fresnel Node and plug the Scalar into it</li>
<li>Create 1 Constant and set it to 1</li>
<li>Create another Scalar Parameter Call it Refraction and set its default to 1.4</li>
<li>Plug both the Constant and Scalar Parameter into a LERP and then in the alpha channel</li>
<li>Plug the Fresnel</li>
<li>Plug the final result of the LERP into the refraction</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>