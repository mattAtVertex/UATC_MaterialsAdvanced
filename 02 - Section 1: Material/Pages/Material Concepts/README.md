# Material Concepts

<p title="Click to listen" data-speechify-highlight="true" data-speechify-no-background="true">In PBR, materials are typically defined using a set of texture maps. These maps include the albedo or base color map, which represents the surface color of the material, the roughness map, which controls the level of surface roughness or smoothness, the metalness or reflectivity map, which determines if the material is metallic or dielectric, and other maps like the normal map and ambient occlusion map, which add additional surface details and shading information.</p>
<p><strong><span style="font-size: 14pt;">Base Color (A</span></strong><strong><span style="font-size: 14pt;">lbedo)<img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19593/preview?verifier=OHbGCaTBATeX230fnBCitGej6OtqDtb11BwGacow" alt="image.png" width="197" height="411" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19593" data-api-returntype="File"><img style="float: right;" src="https://vertexschool.instructure.com/courses/311/files/19592/preview?verifier=LVfySKrwtPSfpzx63YqRQXKlE6VUDeGUTafRjxGk" alt="image.png" width="172" height="231" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19592" data-api-returntype="File"></span></strong></p>
<p>&nbsp;</p>
<ul>
<li><span style="font-size: 12pt;">Color info always has a range. There are no pure whites or blacks in nature.<br></span></li>
<li><span style="font-size: 12pt;">Keep in mind Roughness is key in defining the look of the material as in selling its real world<br>equivalent.<br></span></li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 14pt;">Metallic</span></strong></p>
<p><img src="https://vertexschool.instructure.com/courses/311/files/19588/preview?verifier=vWWDLOQX7tUcWdODGlQITI7UIjZCVn6fWARrix9I" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19588" data-api-returntype="File"></p>
<ul>
<li><span style="font-size: 14pt;">Grayscale value, ranging between 0 to 1</span></li>
<li><span style="font-size: 14pt;">Most common usage is either on (1) or off (0)<br></span></li>
<li><span style="font-size: 14pt;">When on, results as a 100% specular reflection</span></li>
</ul>
<p><strong><span style="font-size: 14pt;">Roughness</span></strong></p>
<p><strong><span style="font-size: 14pt;"><img src="https://vertexschool.instructure.com/courses/311/files/19590/preview?verifier=WQng0muaeMFpRkwuW1cnBydAsZCJGNeoE35Sf54l" alt="image.png" width="1049" height="118" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19590" data-api-returntype="File"></span></strong></p>
<ul>
<li><span style="font-size: 12pt;">Grayscale value, ranging between 0 to 1<br></span></li>
<li><span style="font-size: 12pt;">Rough materials scatter reflected light in more directions than smooth materials<br></span></li>
<li><span style="font-size: 12pt;">Ranges from smooth, mirror like surface (0) to rough matte surface (1)</span></li>
</ul>