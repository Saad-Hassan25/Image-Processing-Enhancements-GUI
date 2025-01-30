<h2>Overview</h2>
<p>This project provides a GUI-based implementation of image processing techniques, including:</p>
<ul>
    <li><strong>Enlargement</strong> using custom convolution (Zero-order hold & First-order hold)</li>
    <li><strong>Linear Interpolation</strong> based on user-defined size (K)</li>
</ul>

<h2>Installation</h2>
<pre><code>pip install -r requirements.txt</code></pre>
<p>Alternatively, install the required libraries manually:</p>
<pre><code>pip install numpy opencv-python matplotlib tkinter</code></pre>

<h2>Usage</h2>
<ol>
    <li><strong>Run the Jupyter Notebook:</strong></li>
    <pre><code>jupyter notebook notebook.ipynb</code></pre>
</ol>

<h2>Algorithms Implemented</h2>
<h3>1. Image Enlargement</h3>
<h4>(a) Zero-Order Hold (Nearest Neighbor Interpolation)</h4>
<p>Uses the nearest pixel value when expanding the image. Fast but can cause blocky artifacts.</p>
<h4>(b) First-Order Hold (Bilinear Interpolation)</h4>
<p>Uses weighted average of neighboring pixels. Produces smoother images.</p>

<h3>2. Linear Interpolation</h3>
<p>Takes a scaling factor <strong>K</strong> from the user. Smoothly resizes the image using linear interpolation.</p>


<h2>License</h2>
<p>This project is licensed under the MIT License.</p>


