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
    <li><strong>Run the GUI Script:</strong></li>
    <pre><code>python gui_code.py</code></pre>
</ol>

<h2>GUI Preview</h2>
<img src="assets/gui_screenshot.png" alt="GUI Preview">

<h2>Algorithms Implemented</h2>
<h3>1. Image Enlargement</h3>
<h4>(a) Zero-Order Hold (Nearest Neighbor Interpolation)</h4>
<p>Uses the nearest pixel value when expanding the image. Fast but can cause blocky artifacts.</p>
<h4>(b) First-Order Hold (Bilinear Interpolation)</h4>
<p>Uses weighted average of neighboring pixels. Produces smoother images.</p>

<h3>2. Linear Interpolation</h3>
<p>Takes a scaling factor <strong>K</strong> from the user. Smoothly resizes the image using linear interpolation.</p>

<h2>Example Results</h2>
<table>
    <tr>
        <th>Original Image</th>
        <th>Zero-Order Hold</th>
        <th>First-Order Hold</th>
        <th>Linear Interpolation</th>
    </tr>
    <tr>
        <td><img src="images/original.jpg" alt="Original" width="150"></td>
        <td><img src="images/zero_order.jpg" alt="Zero Order" width="150"></td>
        <td><img src="images/first_order.jpg" alt="First Order" width="150"></td>
        <td><img src="images/linear.jpg" alt="Linear" width="150"></td>
    </tr>
</table>

<h2>Contributing</h2>
<ol>
    <li>Fork the repository</li>
    <li>Create a feature branch (<code>feature-branch-name</code>)</li>
    <li>Commit your changes</li>
    <li>Submit a Pull Request</li>
</ol>

<h2>License</h2>
<p>This project is licensed under the MIT License.</p>

<h2>Contact</h2>
<p>For any queries or collaborations, reach out via email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
