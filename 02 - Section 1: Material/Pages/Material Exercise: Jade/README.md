# Material Exercise: Jade

<p>&nbsp;</p>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19681/preview?verifier=lz5F77ohiythD0SdC0YKyvICFcqqwcxyxwYaQze1" alt="image.png" width="637" height="305" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19681" data-api-returntype="File"></p>
<p><span style="color: var(--ic-brand-font-color-dark); font-family: inherit; font-size: 1rem;"><img src="https://vertexschool.instructure.com/courses/311/files/19682/preview?verifier=pVTTAVtsiAVnMKKOpSaUKhOUiKuEezd0nAzxLbgU" alt="image.png" width="322" height="300" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19682" data-api-returntype="File"></span></p>
<p><span style="color: var(--ic-brand-font-color-dark); font-family: inherit; font-size: 1rem;"><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19683/preview?verifier=7UwoIItxf7PrQJOX9ZzXaik7nbhgIBpzPEPRKtCN" alt="image.png" width="580" height="303" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19683" data-api-returntype="File"></span></p>
<p>&nbsp;</p>
<p><span style="color: var(--ic-brand-font-color-dark); font-family: inherit; font-size: 1rem;">Creating a Jade like material even ice, you can make some dependencies to make the material rich with control.</span></p>
<ul>
<li>Set the material to be Subsurface under the Shading Model</li>
<li>To texturize the effect, Color can be stacked with LERPs and Multiplies.</li>
<li>The Final texture output can have a Scalar on it to control amount of noise filter to use - plugged into a LERP Alpha *</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19684/preview?verifier=GKsEeIx93SOZHMrAGhyIvY4fr3k0cDpRLXqoayqy" alt="image.png" width="624" height="251" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19684" data-api-returntype="File"><span style="font-size: 14pt;"><strong>Controlling Opacity</strong></span></p>
<ul>
<li>Create Fresnel Index and Control Exponeth</li>
<li>Introduce a LERP and a Scalar to control Subsurface amount (opacity is used for transmission)</li>
<li>Add a Multiply into the LERP B to Multiply the Subsurface amount effect This can be adjusted with a new input but can be used as a generic range control.</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<hr>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19685/preview?verifier=TUf6EyX1XQXPwfjwbmwIZXp1YSlfb2fBTTXiKGTl" alt="image.png" width="616" height="451" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19685" data-api-returntype="File"><strong><span style="font-size: 14pt;">Adding Subsurface control</span></strong></p>
<ul>
<li>Create A Fresnel node - this helps sell the idea<br>of light affecting the surface.</li>
<li>Create A Scalar for the ExponentIn (In this<br>case it controls Edge Subsurface control)</li>
<li>Create a Scalar for Spec Reflect (but in this<br>case it will give the illusion of thickness.)<br>Plug into the BaseReflectFractionIn</li>
<li>Plug into a Multiply with a 3 Constant Vector<br>to control overall color<br><br></li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<hr>
<p><span style="font-size: 14pt;"><strong><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19686/preview?verifier=cMOhqT3pFiP00gOZ0dZbxY5PhnATsbhI4qQwOi3Z" alt="image.png" width="311" height="277" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19686" data-api-returntype="File">Adding Subsurface control</strong></span><br>NOTE: The Fresnel that is found under Vector Ops is a highly customizable version of Fresnel that allows you to affect many different aspects of how the Fresnel is rendered.</p>
<p><img src="https://vertexschool.instructure.com/courses/311/files/19687/preview?verifier=aDLfskCJxTwXJnLTjeabpK1yD62CddA1Qed4r8zV" alt="image.png" width="729" height="250" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19687" data-api-returntype="File"></p>