# cs551-computer-graphics---homework-assignment-3---raytracing-solved
**TO GET THIS SOLUTION VISIT:** [CS551 Computer Graphics – Homework Assignment 3 – Raytracing Solved](https://www.ankitcodinghub.com/product/cs551-computer-graphics-homework-assignment-3-raytracing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97301&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS551 Computer Graphics - Homework Assignment 3 - Raytracing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<h2 dir="auto"><a id="user-content-overview" class="anchor" href="https://github.com/yig/graphics101-raytracing#overview" aria-hidden="true"></a>Overview:</h2>
<p dir="auto">In this assignment, you will be implementing a ray tracer which supports Phong lighting, shadows, reflections, and optionally refractions. You will be able to create stunning artwork like this:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-raytracing/blob/master/docs/spheres_cylinder.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-raytracing/raw/master/docs/spheres_cylinder.png?w=980&amp;ssl=1" alt="solid color spheres and a cylinder" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">The assignment is broken down into parts: (1) computing accurate normals for ray/shape intersections, (2) computing direct illumination (a local Phong lighting model with ambient, diffuse, and specular lighting), (3) computing global illumination effects (shadows, reflections, and, optionally, refractions).

<h2 dir="auto"><a id="user-content-goals" class="anchor" href="https://github.com/yig/graphics101-raytracing#goals" aria-hidden="true"></a>Goals:</h2>
<ul dir="auto">
<li>
<p dir="auto">Understand how to calculate virtual illumination for a 3D scene.

</li>
<li>
<p dir="auto">Gain experience deriving and implementing mathematical expressions for geometric calculations.

</li>
<li>
<p dir="auto">Become more familiar with a 3D math library (identical to one available when programming for a GPU).

</li>
<li>
<p dir="auto">Become more comfortable with C++.

</li>
</ul>
<h2 dir="auto"><a id="user-content-background" class="anchor" href="https://github.com/yig/graphics101-raytracing#background" aria-hidden="true"></a>Background:</h2>
<ul dir="auto">
<li>Book (FoCG,4e): Chapter 10&nbsp;<em>Surface Shading</em>&nbsp;and, for the bonus, Chapter 13.1&nbsp;<em>Transparency and Refraction</em>, and Chapter 11&nbsp;<em>Texture Mapping</em>.</li>
<li>Video: “Lecture 5: Illumination”, “Quadratic light attenuation with distance”, “Lambert’s Cosine Law on a Flat Earth”, “Assignment 3: Raytracing”, and “Lecture 6: Parameterization”.</li>
</ul>
<p dir="auto">(FoCG,4e is&nbsp;<em>Fundamentals of Computer Graphics (4th edition)</em>&nbsp;by Steve Marschner and Peter Shirley.)

<p dir="auto">If you love this topic and want to go&nbsp;<em>beyond</em>, here are some free, online resources:

<ul dir="auto">
<li>The&nbsp;<em>Physically Based Rendering</em>&nbsp;book:&nbsp;<a href="https://www.pbrt.org/" rel="nofollow">https://www.pbrt.org/</a>. It won an Academy Award!</li>
<li>The&nbsp;<em>Ray Tracing in One Weekend</em>&nbsp;series:&nbsp;<a href="https://raytracing.github.io/" rel="nofollow">https://raytracing.github.io/</a>.</li>
<li><em>smallpt: Global Illumination in 99 lines of C++</em>:&nbsp;<a href="https://www.kevinbeason.com/smallpt/" rel="nofollow">https://www.kevinbeason.com/smallpt/</a>&nbsp;There is a presentation on the site explaining it line by line.</li>
</ul>
<h2 dir="auto"><a id="user-content-getting-started--handing-in" class="anchor" href="https://github.com/yig/graphics101-raytracing#getting-started--handing-in" aria-hidden="true"></a>Getting Started &amp; Handing In:</h2>
<ul dir="auto">
<li>
<p dir="auto">This project builds off of your&nbsp;<a href="https://github.com/yig/graphics101-raycasting">raycasting</a>&nbsp;homework. There is no new code to download. You will augment your existing codebase to generate&nbsp;<em>raytraced</em>&nbsp;output for the&nbsp;<code>.json</code>&nbsp;scenes.

</li>
<li>
<p dir="auto">You will be fleshing out&nbsp;<code>Scene::rayColor()</code>&nbsp;to implement a Phong lighting model with shadows, reflections, and (optionally) refractions. You will also revisit&nbsp;<code>Shape::rayIntersect()</code>&nbsp;to fill out&nbsp;<code>Intersection.position</code>&nbsp;and&nbsp;<code>.normal</code>&nbsp;if you did not already do so (and, for bonus,&nbsp;<code>Intersection.texCoord</code>).

</li>
<li>
<p dir="auto">Add your code to&nbsp;<code>scene.cpp</code>&nbsp;and&nbsp;<code>shape.cpp</code>.

</li>
<li>
<p dir="auto">Build and run and test that it is working correctly.

</li>
<li>
<p dir="auto">Check your work with the&nbsp;<a href="https://github.com/yig/graphics101-raytracing-autograder">autograder</a>.

</li>
<li>
<p dir="auto">Copy the latest autograder output (<code>.html</code>&nbsp;file and associated directory) into a new&nbsp;<code>output/</code>&nbsp;subdirectory.

</li>
<li>
<p dir="auto">Create a&nbsp;<code>.json</code>&nbsp;scene yourself. It can be the one you made for your raycaster with updated materials or an entirely new scene. Copy it and a&nbsp;<code>.png</code>&nbsp;rendering of it into the&nbsp;<code>output/</code>&nbsp;subdirectory as well.

</li>
<li>
<p dir="auto">You are encouraged to share blooper images you create while implementing the assignment on Piazza.

</li>
<li>
<p dir="auto">Create a file named&nbsp;<code>Notes.txt</code>&nbsp;in the folder. Describe any known issues or extra features. Name people in the class who deserve a star for helping you (not by giving your their code!).

</li>
<li>
<p dir="auto">When done, run the the&nbsp;<code>cpack</code>&nbsp;command from inside your build directory to generate an appropriate zip file of your&nbsp;<code>raycasting</code>&nbsp;project (that is now actually a raytracer). The zip file it creates,&nbsp;<code>raycasting.zip</code>, will include the&nbsp;<code>output</code>&nbsp;subdirectory and your&nbsp;<code>Notes.txt</code>&nbsp;file. It will ignore unneeded large and numerous directories (e.g.&nbsp;<code>build</code>). Upload your&nbsp;<code>raycasting.zip</code>&nbsp;before the deadline.

</li>
<li>
<p dir="auto">The framework and glm vector math library still provide all the support code that you need.

</li>
<li>
<p dir="auto"><strong>THIS IS AN INDIVIDUAL, NOT A GROUP ASSIGNMENT. That means all code written for this assignment should be original! Although you are permitted to consult with each other while working on this assignment, code that is substantially the same will be considered cheating.</strong>

</li>
</ul>
<h2 dir="auto"><a id="user-content-rubric" class="anchor" href="https://github.com/yig/graphics101-raytracing#rubric" aria-hidden="true"></a>Rubric</h2>
<ul dir="auto">
<li>
<p dir="auto"><strong>(25 points)</strong>&nbsp;The&nbsp;<code>Shape</code>&nbsp;subclasses’&nbsp;<code>rayIntersect()</code>&nbsp;methods should fill out the&nbsp;<code>Intersection.position</code>&nbsp;and&nbsp;<code>.normal</code>&nbsp;fields. Both of these should be in world-space. The position in world-space is easy to compute, since it is the world-space ray’s position + t * direction. The world-space normal can be computed as the inverse transpose of the shape’s transformation matrix * the object-space normal. The object-space normal can be computed as the gradient (vector of partial derivatives with respect to&nbsp;<em>x,y,z</em>) of the implicit function for the part of the shape intersected.&nbsp;<strong>Note:</strong>&nbsp;By convention, normals should point away from the shape (towards its exterior, not its interior). For example, the normal on the bottom face of the cylinder (the&nbsp;<em>z</em>=0 plane) should be &lt;0,0,-1&gt;, not &lt;0,0,1&gt;. Because an implicit function&nbsp;<em>F</em>(<em>x</em>,<em>y</em>,<em>z</em>) defines the shape as anywhere&nbsp;<em>F</em>(<em>x</em>,<em>y</em>,<em>z</em>) = 0, both&nbsp;<em>F</em>&nbsp;and –<em>F</em>&nbsp;define the same shape. Their gradients point in the opposite direction. The implicit functions given below—they are the same as in Homework 2 – Raycasting—are defined properly so that their gradients points towards the exterior.

<ul dir="auto">
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Sphere (centered at the origin with radius 1):

<ul dir="auto">
<li>F(x,y,z) = x² + y² + z² – 1</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Plane (the&nbsp;<em>xy</em>&nbsp;plane, also known as the&nbsp;<em>z</em>&nbsp;= 0 plane)

<ul dir="auto">
<li>F(x,y,z) = z</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Cylinder (bottom at the origin, top at (0,0,1), radius 1) with a top and bottom cap (circles with radius 1 at z=0 and z=1). You handle this as a collection of three shapes with conditions:

<ul dir="auto">
<li>if 0 &lt; z &lt; 1: F(x,y,z) = x² + y² – 1</li>
<li>if x² + y² &lt; 1: F(x,y,z) = -z</li>
<li>if x² + y² &lt; 1: F(x,y,z) = z-1</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Cone (bottom at the origin, top at (0,0,1), radius 1 at the bottom, radius 0 at the top, with a bottom cap). You handle this as a collection of two shapes with conditions:

<ul dir="auto">
<li>if 0 &lt; z ≤ 1: F(x,y,z) = x² + y² – (1 – z)²</li>
<li>if x² + y² &lt; 1: F(x,y,z) = -z</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Cube (centered at the origin, with vertices ( ±1, ±1, ±1)). Think of it as six planes:

<ul dir="auto">
<li>if -1 ≤ y,z ≤ 1: F(x,y,z) = x-1</li>
<li>if -1 ≤ y,z ≤ 1: F(x,y,z) = -(x+1)</li>
<li>if -1 ≤ x,z ≤ 1: F(x,y,z) = y-1</li>
<li>if -1 ≤ x,z ≤ 1: F(x,y,z) = -(y+1)</li>
<li>if -1 ≤ x,y ≤ 1: F(x,y,z) = z-1</li>
<li>if -1 ≤ x,y ≤ 1: F(x,y,z) = -(z+1)</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(bonus 5 points)</strong>&nbsp;Mesh (arbitrary triangle meshes)

<ul dir="auto">
<li>The normal should be perpendicular to whichever triangle is intersected. By convention, the vertices of a triangle are given in counter-clockwise order when viewed from the exterior of the triangle along the normal. The normal can be obtained via the cross product.</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(75 points)</strong>&nbsp;Illumination. This code goes into&nbsp;<code>Scene::rayColor()</code>&nbsp;and replaces the stub that you wrote that simply returns&nbsp;<code>Intersection.diffuse_color</code>. The expression we will be using for the color at a point on a surface is:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-raytracing/blob/master/docs/illumination.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-raytracing/raw/master/docs/illumination.png?w=980&amp;ssl=1" alt="K_R I_R + K_T I_T + \sum_L \big( K_A I_{AL} + \big[ K_D I_L ( N \cdot L ) + K_S I_L ( V \cdot R )^n  \big] S_L \big)" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">In this expression,&nbsp;<em>K<sub>A</sub></em>,&nbsp;<em>K<sub>D</sub></em>,&nbsp;<em>K<sub>S</sub></em>,&nbsp;<em>n</em>,&nbsp;<em>K<sub>R</sub></em>, and&nbsp;<em>K<sub>T</sub></em>&nbsp;refer to&nbsp;<code>Material.color_ambient</code>,&nbsp;<code>.color_diffuse</code>,&nbsp;<code>.color_specular</code>,&nbsp;<code>.shininess</code>,&nbsp;<code>.color_reflect</code>, and&nbsp;<code>.color_refract</code>. The summation is over all the&nbsp;<code>Light</code>&nbsp;structures in the&nbsp;<code>Scene</code>;&nbsp;<em>I<sub>AL</sub></em>&nbsp;and&nbsp;<em>I<sub>L</sub></em>&nbsp;refer to&nbsp;<code>Light.color_ambient</code>&nbsp;and&nbsp;<code>.color</code>. You can multiply colors stored as&nbsp;<code>vec3</code>‘s, and it will do the right thing (multiply each channel or wavelength of light). The other terms will be defined below.

<ul dir="auto">
<li>
<p dir="auto">For direct illumination, you will implement a local Phong lighting model with ambient, diffuse, and specular terms.

<ul dir="auto">
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;Ambient lighting:&nbsp;<em>K<sub>A</sub>&nbsp;I<sub>AL</sub></em>

</li>
<li>
<p dir="auto"><strong>(15 point)</strong>&nbsp;Diffuse lighting:&nbsp;<em>K<sub>D</sub>&nbsp;I<sub>L</sub>&nbsp;( N · L )</em>.&nbsp;<em>N</em>&nbsp;is the (normalized) surface normal vector and&nbsp;<em>L</em>&nbsp;is the (normalized) vector from the surface position to the light’s position. Note that if this dot product is negative, then the light is behind the surface and you should not add diffuse&nbsp;<strong>or</strong>&nbsp;specular lighting.

</li>
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Specular lighting: K<sub>S</sub>&nbsp;I<sub>L</sub>&nbsp;( V · R )<sup>n</sup>.&nbsp;<em>V</em>&nbsp;is the (normalized) vector from the surface position to the “eye” position. (Because you are writing a recursive ray tracer, the “eye” in this formula should be the position of the ray parameter passed to&nbsp;<code>rayColor()</code>.)&nbsp;<em>R</em>&nbsp;is the (normalized) direction from the light position to the surface position, reflected across the surface normal. The formula for reflecting a vector across another vector is given below under&nbsp;<strong>Implementation Details</strong>. Note that if the dot product is negative, then the light is reflected away from the viewer and you should not add any specular lighting. (You can use max( 0,&nbsp;<em>V · R</em>&nbsp;) instead of an if statement if you desire.) Also note that if the dot product used for diffuse lighting is zero (the light is behind the surface), then you also should not add specular lighting.

</li>
</ul>
</li>
<li>
<p dir="auto">For indirect or global illumination, you will add shadows, reflections, and (optionally) refractions.

<ul dir="auto">
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Shadows. Is there an object between the surface position and the light? If so, set&nbsp;<em>S<sub>L</sub></em>&nbsp;to 0. Otherwise, set&nbsp;<em>S<sub>L</sub></em>&nbsp;to 1. You can check this easily by calling&nbsp;<code>closestIntersection()</code>&nbsp;with a ray from the surface position in the direction from the surface position towards the light position. Check if there is an intersection closer than the light itself. Note that if the ray originates from the surface position exactly, your&nbsp;<code>closestIntersection()</code>&nbsp;method may find that the closest intersection is still the surface position (t=0). To avoid this problem, offset the ray’s position by epsilon (a tiny number) along the ray’s direction.

</li>
<li>
<p dir="auto"><strong>(20 points)</strong>&nbsp;Reflections. If&nbsp;<code>Material.reflective</code>&nbsp;is true, then reflect the vector from the “eye” to the surface position across the surface normal and call&nbsp;<code>rayColor()</code>&nbsp;recursively to find the color of light&nbsp;<em>I<sub>R</sub></em>&nbsp;seen by that ray. (Because you are writing a recursive ray tracer, the “eye” in this formula should be the position of the ray parameter to&nbsp;<code>rayColor()</code>.) The formula to reflect one vector across another is below under&nbsp;<strong>Implementation Details</strong>. Just like with shadow rays, you will want to offset the reflected ray’s position along its direction to avoid self-intersection. To keep light from reflecting forever, only do this if&nbsp;<code>max_recursion &gt; 0</code>&nbsp;and pass&nbsp;<code>max_recursion-1</code>&nbsp;to&nbsp;<code>rayColor()</code>.

</li>
<li>
<p dir="auto"><strong>(bonus 5 points)</strong>&nbsp;Refraction. If&nbsp;<code>Material.refractive</code>&nbsp;is true, then the object is translucent. Refract the vector from the eye to the surface position into the surface according to the index of refraction and call&nbsp;<code>rayColor()</code>&nbsp;recursively to find the color of light&nbsp;<em>I<sub>T</sub></em>&nbsp;seen by that ray. (The formula for the refracted direction can be found in the book.) To keep light from bouncing forever, only do this if&nbsp;<code>max_recursion &gt; 0</code>&nbsp;and pass&nbsp;<code>max_recursion-1</code>&nbsp;to&nbsp;<code>rayColor()</code>. To get this right, you will have to adjust your code elsewhere. You will intersect with the inside of shapes. To detect this, check if the normal faces towards or away from the ray. You will want to use a normal that faces the ray direction when calculating lighting effects other than refraction. The ratio of the index of refraction of air to the&nbsp;<code>Material</code>&nbsp;is inverted when leaving versus entering a surface. Translucent objects should cast less of a shadow. If the shadow ray hits a refractive object, use the object’s refractive color instead of a 0 or 1 for&nbsp;<em>S<sub>L</sub></em>.

</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(bonus 20 points)</strong>&nbsp;Texture mapping. To do this you do two things. In&nbsp;<code>Shape::rayIntersect()</code>, fill out&nbsp;<code>Intersection.texCoord</code>&nbsp;with explicit 2D coordinates (numbers between 0 and 1) that parameterize the shape. In&nbsp;<code>Scene::rayColor()</code>, if&nbsp;<code>material.use_diffuse_texture</code>&nbsp;is true, get the texture from&nbsp;<code>Scene::textures[material.diffuse_texture]</code>, use&nbsp;<code>Intersection.texCoord</code>&nbsp;to look up the color at that texture coordinate in the image, and then multiply this color with&nbsp;<code>material.diffuse_color</code>&nbsp;to use as the diffuse color&nbsp;<em>K<sub>D</sub></em>. If there is interest in this, I can provide additional guidance. You will need to create a scene that uses textures (sets&nbsp;<code>material.use_diffuse_texture</code>&nbsp;to true and&nbsp;<code>material.diffuse_texture</code>&nbsp;to e.g.&nbsp;<code>bricks</code>, and adds a&nbsp;<code>textures</code>&nbsp;property to the JSON scene, e.g.&nbsp;<code>textures = { 'bricks': 'path/to/bricks.png' }</code>).

<ul dir="auto">
<li>
<p dir="auto">Cylinder and cone: The end cap texture coordinates should map the object-space xy-plane unit square [-1,1] to the texture coordinates’ [0,1] square.

</li>
<li>
<p dir="auto">Plane: The plane should map the object-space xy-plane unit square [-1,1] to the texture coordinates’ [0,1] square. The texture coordinates elsewhere should repeat modulo.

</li>
<li>
<p dir="auto">Cube: Each face should map to the texture coordinates’ [0,1] square. The orientation does not matter.

</li>
</ul>
</li>
</ul>
<h2 dir="auto"><a id="user-content-the-code" class="anchor" href="https://github.com/yig/graphics101-raytracing#the-code" aria-hidden="true"></a>The Code</h2>
<ul dir="auto">
<li>
<p dir="auto">The code for the raytracer is the same as the code for the raycaster. All of your changes will be to&nbsp;<code>Shape::rayIntersect()</code>&nbsp;(to fill out&nbsp;<code>Intersection.position</code>&nbsp;and&nbsp;<code>.normal</code>) and to&nbsp;<code>Scene::rayColor()</code>.

</li>
<li>
<p dir="auto">The one exception is&nbsp;<code>Scene::render()</code>, where you should initially call&nbsp;<code>rayColor()</code>&nbsp;with a&nbsp;<code>max_recursion</code>&nbsp;of whatever your code can handle. A value of 3 is sufficient. Also note that the resulting&nbsp;<code>rayColor()</code>&nbsp;may be very bright, with a value outside [0,1]. To clamp it to the valid range, you can use the function&nbsp;<code>glm::clamp( color, 0.0, 1.0 )</code>.

</li>
<li>
<p dir="auto">To iterate over the lights in&nbsp;<code>Scene::rayColor()</code>, you can use:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  for( const Light&amp; l : lights ) { ... }
</code></pre>
</div>
</li>
</ul>
<h2 dir="auto"><a id="user-content-implementation-details" class="anchor" href="https://github.com/yig/graphics101-raytracing#implementation-details" aria-hidden="true"></a>Implementation Details</h2>
<p dir="auto">To reflect a (not necessarily normalized) vector&nbsp;<strong>v</strong>&nbsp;across a normalized vector&nbsp;<strong>n</strong>, the formula for the reflected vector&nbsp;<strong>r</strong>&nbsp;is&nbsp;<strong>r = v – 2(v·n)n</strong>.

<p dir="auto"><a href="https://github.com/yig/graphics101-raytracing/blob/master/docs/reflection.svg" target="_blank" rel="noopener noreferrer"><img decoding="async" data-src="https://github.com/yig/graphics101-raytracing/raw/master/docs/reflection.svg" alt="Illustration of a vector v reflected across a vector n" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<h2 dir="auto"><a id="user-content-glm-and-cc-standard-library-functions-you-need-for-this-assignment" class="anchor" href="https://github.com/yig/graphics101-raytracing#glm-and-cc-standard-library-functions-you-need-for-this-assignment" aria-hidden="true"></a>glm and C/C++ standard library functions you need for this assignment</h2>
<p dir="auto"><strong>glm.</strong>&nbsp;Please consult the Raycasting handout for the basics of&nbsp;<strong>glm</strong>. The code particular to raytracing will make use of&nbsp;<code>transpose(m)</code>&nbsp;and perhaps&nbsp;<code>clamp(v, minVal, maxVal)</code>&nbsp;and&nbsp;<code>reflect(v,n)</code>.

<p dir="auto"><strong>std::max(a,b)</strong>. This is part of C++’s&nbsp;<code>&lt;algorithm&gt;</code>. Note that&nbsp;<code>std::max()</code>&nbsp;requires both parameters to have the exact same type. If not, you will get a very long compiler error since they are generic functions written using C++ templates. You can also use&nbsp;<code>glm::max(a,b)</code>.
