---
keywords: fastai
title: Note Template
comments: true
nb_path: _notebooks/2022-12-01-notetemplate.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-12-01-notetemplate.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Take some additional notes that you would like here for 3.12 and 3.13. We will be looking for additional notes from the presentation.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The Notes:</p>
<p>Procedures can be called methods or functions.
procedure call interupts statments to run procedure
before you write:</p>
<ul>
<li>know what arguments you need</li>
<li>be ble to call the procedure
to call a procedure write the name of the procedure followed by parenthesis containing the paramaters</li>
</ul>
<ol>
<li>name procedure</li>
<li>what apramater are needed</li>
<li>what data is needed to acomplish my goal</li>
<li>do I want numerical value or complete an action
## What are procedures?</li>
</ol>
<p><strong>Fill in the blanks please:</strong></p>
<p>Procedure: a named group of instructions that have paramaters and return values</p>
<p>Parameters: input values of a procedure</p>
<p>Arguments: specify values of the paramaters when the procedure is called</p>
<p>Modularity: An splitting large procedures into smaller ones with more uses</p>
<p>Procedural Abstraction: name for a process that allow a procedure to be used by only knowing what it does</p>
<p>Return: sends the output of the procedure to where it was called</p>
<p>What are some other names for procedures?: functions and actions (<em>maybe</em>)</p>
<p>Why are procedures effective?: procedures make code more eficcient by making it so you dont have to write the same code every time.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><mark>Challenge 1</mark> below: Add the command that will <strong>call</strong> the procedure.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">decimal</span> <span class="o">=</span> <span class="mi">35775</span>
<span class="k">def</span> <span class="nf">convertToBinary</span><span class="p">(</span><span class="n">n</span><span class="p">):</span>
    <span class="n">thelist</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="k">while</span> <span class="n">n</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">:</span>
        <span class="k">if</span> <span class="n">n</span> <span class="o">%</span> <span class="mi">2</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
            <span class="n">thelist</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
            <span class="n">n</span> <span class="o">=</span> <span class="n">n</span> <span class="o">/</span> <span class="mi">2</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="n">thelist</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
            <span class="n">n</span> <span class="o">=</span> <span class="n">n</span> <span class="o">/</span> <span class="mi">2</span>
            <span class="n">n</span> <span class="o">=</span> <span class="n">n</span> <span class="o">-</span> <span class="mf">0.5</span>
    <span class="n">x</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">thelist</span><span class="p">)</span> <span class="o">-</span> <span class="mi">1</span>
    <span class="n">final</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="n">thelist</span><span class="p">[</span><span class="n">x</span><span class="p">])</span>
    <span class="n">x</span> <span class="o">=</span> <span class="n">x</span> <span class="o">-</span> <span class="mi">1</span>
    <span class="k">while</span> <span class="n">x</span> <span class="o">&gt;=</span> <span class="mi">0</span><span class="p">:</span>
        <span class="n">final</span> <span class="o">=</span> <span class="n">final</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">thelist</span><span class="p">[</span><span class="n">x</span><span class="p">])</span>
        <span class="n">x</span> <span class="o">=</span> <span class="n">x</span> <span class="o">-</span> <span class="mi">1</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">final</span><span class="p">)</span>

<span class="n">convertToBinary</span><span class="p">(</span><span class="n">decimal</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>1000101110111111
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><mark>Challenge 2</mark> below: Complete the Min and Max procedure in either JavaScript and Python using the instructions from the JavaScript page. (JavaScript will get you a extra 0.1)</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">values</span> <span class="o">=</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">6</span><span class="p">,</span><span class="mi">86</span><span class="p">,</span><span class="mi">253</span><span class="p">,</span><span class="mi">4325</span><span class="p">,</span><span class="mi">78</span><span class="p">,</span><span class="mi">53</span><span class="p">,</span><span class="mi">69</span><span class="p">,</span><span class="mi">23</span><span class="p">,</span><span class="mi">4142</span><span class="p">,</span><span class="mi">56373</span><span class="p">,</span><span class="mi">420</span><span class="p">]</span>
<span class="k">def</span> <span class="nf">findextrema</span><span class="p">(</span><span class="nb">set</span><span class="p">):</span>
    <span class="nb">min</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="nb">max</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">if</span> <span class="nb">set</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span> <span class="o">&gt;</span> <span class="nb">set</span><span class="p">[</span><span class="mi">1</span><span class="p">]:</span>
        <span class="nb">max</span> <span class="o">=</span> <span class="nb">set</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">min</span> <span class="o">=</span> <span class="nb">set</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="nb">set</span><span class="p">)):</span>
        <span class="k">if</span> <span class="nb">set</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">&gt;</span> <span class="nb">max</span><span class="p">:</span>
            <span class="nb">max</span> <span class="o">=</span> <span class="nb">set</span><span class="p">[</span><span class="n">i</span><span class="p">]</span>
        <span class="k">elif</span> <span class="nb">set</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">&lt;</span> <span class="nb">min</span><span class="p">:</span>
            <span class="nb">max</span> <span class="o">=</span> <span class="nb">set</span><span class="p">[</span><span class="n">i</span><span class="p">]</span>
    <span class="k">return</span><span class="p">[</span><span class="nb">min</span><span class="p">,</span><span class="nb">max</span><span class="p">]</span>

<span class="n">stuff</span> <span class="o">=</span> <span class="n">findextrema</span><span class="p">(</span><span class="n">values</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;min is&#39;</span><span class="p">,</span><span class="n">stuff</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span><span class="s1">&#39;- max is&#39;</span><span class="p">,</span><span class="n">stuff</span><span class="p">[</span><span class="mi">1</span><span class="p">])</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>min is 2 - max is 56373
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><mark>Homework/Hacks</mark>: For the hw, you have two options, easy or hard. The easy hack is for a 2.7 + extra work for the full 3. The easy hack is simply creating your own procedure with your own creativity. Since there is a lot of leeway for this one, you must do additional work to get a 3. For the hard hack, below is the start to a character to binary convertor. This is just a template, but the goal is to translate "APCSP" into binary. You can delete the existing code if you want. The only contraint is that you must use a procedure. Doing this will get you a 3.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">BinaryS2L</span><span class="p">(</span><span class="n">binary</span><span class="p">):</span>
    <span class="k">if</span> <span class="nb">type</span><span class="p">(</span><span class="n">binary</span><span class="p">)</span> <span class="o">==</span> <span class="nb">str</span><span class="p">:</span>
        <span class="n">out</span> <span class="o">=</span> <span class="p">[]</span>
        <span class="n">i</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">binary</span><span class="p">)</span> <span class="o">-</span> <span class="mi">1</span>
        <span class="k">while</span> <span class="n">i</span> <span class="o">&gt;=</span> <span class="mi">0</span><span class="p">:</span>
            <span class="n">out</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="nb">int</span><span class="p">(</span><span class="n">binary</span><span class="p">[</span><span class="n">i</span><span class="p">]))</span>
            <span class="n">i</span> <span class="o">=</span> <span class="n">i</span> <span class="o">-</span> <span class="mi">1</span>
        <span class="n">out</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
        <span class="k">return</span><span class="p">(</span><span class="n">out</span><span class="p">)</span>
    <span class="k">elif</span> <span class="nb">type</span><span class="p">(</span><span class="n">binary</span><span class="p">)</span> <span class="o">==</span> <span class="nb">list</span><span class="p">:</span>
        <span class="n">out</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span>
        <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">binary</span><span class="p">)):</span>
            <span class="n">out</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="n">binary</span><span class="p">[</span><span class="n">i</span><span class="p">])</span> <span class="o">+</span> <span class="n">out</span>
        <span class="k">return</span><span class="p">(</span><span class="n">out</span><span class="p">)</span>

<span class="k">def</span> <span class="nf">BinaryAdder</span><span class="p">(</span><span class="n">x</span><span class="p">,</span><span class="n">y</span><span class="p">):</span>
    <span class="n">one</span> <span class="o">=</span> <span class="n">BinaryS2L</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">one</span><span class="p">)</span>
    <span class="n">two</span> <span class="o">=</span> <span class="n">BinaryS2L</span><span class="p">(</span><span class="n">y</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">two</span><span class="p">)</span>
    <span class="n">temp</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">end</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="n">rng</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">x</span><span class="p">)</span> <span class="o">+</span> <span class="mi">1</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="n">rng</span><span class="p">):</span>
        <span class="k">if</span> <span class="n">one</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">two</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">temp</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
            <span class="n">temp</span> <span class="o">=</span> <span class="mi">0</span>
            <span class="n">end</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
        <span class="k">elif</span> <span class="n">one</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">two</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">temp</span> <span class="o">==</span> <span class="mi">1</span><span class="p">:</span>
            <span class="n">temp</span> <span class="o">=</span> <span class="mi">0</span>
            <span class="n">end</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
        <span class="k">elif</span> <span class="n">one</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">two</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">temp</span> <span class="o">==</span> <span class="mi">2</span><span class="p">:</span>
            <span class="n">temp</span> <span class="o">=</span> <span class="mi">1</span>
            <span class="n">end</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
        <span class="k">elif</span> <span class="n">one</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">two</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">+</span> <span class="n">temp</span> <span class="o">==</span> <span class="mi">3</span><span class="p">:</span>
            <span class="n">temp</span> <span class="o">=</span> <span class="mi">1</span>
            <span class="n">end</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>      
    <span class="k">return</span><span class="p">(</span><span class="n">BinaryS2L</span><span class="p">(</span><span class="n">end</span><span class="p">))</span>
            

<span class="n">a</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="nb">input</span><span class="p">(</span><span class="s1">&#39;What is the first of the two numbers would you like to add? Please be sure that both values are the same binary length.&#39;</span><span class="p">))</span>
<span class="n">b</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="nb">input</span><span class="p">(</span><span class="s1">&#39;What is the second of the two numbers would you like to add? Please be sure that both values are the same binary length.&#39;</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="n">BinaryAdder</span><span class="p">(</span><span class="n">a</span><span class="p">,</span><span class="n">b</span><span class="p">))</span>

<span class="c1"># The output shown below is the output you are supposed to get</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[0, 1, 0, 0]
[1, 0, 1, 0]
0111
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

