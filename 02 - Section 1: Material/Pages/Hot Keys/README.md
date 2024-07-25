# Hot Keys

<p><span style="font-size: 14pt;"><strong>Using hotkeys in the Unreal Material Editor is important for three key reasons:&nbsp;</strong></span></p>
<p style="padding-left: 40px;"><strong>1. Efficiency:</strong> Hotkeys allow for quicker access to commonly used functions and actions, reducing the time spent navigating menus and interfaces. This results in a more streamlined and efficient workflow, enabling artists to create and edit materials faster.<br><strong>2. Focus and Flow: </strong>Hotkeys help maintain the flow of work by minimizing interruptions and distractions. Instead of searching through menus or toolbars, artists can stay focused on their creative process and seamlessly execute commands using hotkeys, maintaining a smooth and uninterrupted workflow.<br><strong>3. Muscle Memory and Familiarity:</strong> By regularly using hotkeys, artists develop muscle memory and become more familiar with the Material Editor's shortcuts and commands. This familiarity improves speed and accuracy in material creation and manipulation, allowing artists to work more intuitively and with greater precision.</p>
<p><span style="font-size: 14pt;"><strong>Write your own custom hotkeys:</strong></span></p>
<p><span style="font-size: 12pt;">To create your own custom hotkeys: </span></p>
<ol style="list-style-type: decimal;">
<li><span style="font-size: 12pt;">Firstly, you need to close your project.</span></li>
<li><span style="font-size: 12pt;">Navigate to your engine folder. i.e. (UE_5.1)</span></li>
<li><span style="font-size: 12pt;">Open the Engine &gt; Config &gt; BaseEditorPerProjectUserSettings&nbsp;</span></li>
<li><span style="font-size: 12pt;">Navigate almost to the bottom, looking for [MaterialEditorSpawnNodes]</span></li>
<li><span style="font-size: 12pt;">Here we can insert code to create new hockeys, Use the code below as a template. Make sure to use the node's name and set the alternative keys to true that you plan to use such as alt, control or shift and save, restart engine.</span></li>
</ol>
<p><span style="font-size: 12pt;"><span>+Node=Class=MaterialExpression<span style="color: #e03e2d;">NodeName</span> Key=<span style="color: #e03e2d;">$</span> Shift=false Ctrl=false Alt=false)</span></span></p>
<p><span style="font-size: 14pt;"><strong>Default Hotkeys:</strong></span></p>
<p><img src="https://vertexschool.instructure.com/courses/311/files/19594/preview?verifier=0W0l0KpRQiKJr922w45kVdhYeRynDpdN2UhX0Ore" alt="Unreal material editor hotkeys cheat Sheet.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/311/files/19594" data-api-returntype="File"></p>