# API Reference

___
<div id="heading">
    <span id="code-bold">configure_logger()</span><span id="code-italic">(function)</span>
</div>

- **Parameters**

    - **file_name** **|** *string* **|** *Default=None*

    - **directory** **|** *string* **|** *Default=None*
    
    - **log_format** **|** *string* **|** *Default=None*
    
    - **file_mode** **|** *string* **|** *Default=None*
    
    - **level** **|** *string* **|** *Default=None*
___
<div id="heading">
    <span id="code-bold">log()</span><span id="code-italic">(function)</span>
</div>

- **Parameters**

    - **input_level** **|** *int* **|** *Default=0*

    - **log_message** **|** *string* **|** *Default="I'm an empty log message!"*
    
    - **flag** **|** *bool* **|** *Default=True*
___
<div id="heading">
    <span id="code-bold">log_wide()</span><span id="code-italic">(function)</span>
</div>

- **Parameters**

    - **input_level** **|** *int* **|** *Default=0*

    - **log_message** **|** *string* **|** *Default=""*

    - **log_width** **|** *int* **|** *Default=None*
    
    - **log_character** **|** *int* **|** *Default=*"*"
___
<div id="heading">
    <span id="code-bold">delete_old_log_files()</span><span id="code-italic">(function)</span>
</div>

- **Parameters**

    - **keep_amount** **|** *int* **|** *Default=5*
___
<div id="heading">
    <span id="code-bold">Colors</span><span id="code-italic">(class)</span>
</div>

<div id="heading">
    <span id="code-italic">reset</span>
</div>
<div id="heading">
    <span id="code-italic">bold</span>
</div>
<div id="heading">
    <span id="code-italic">disable</span>
</div>
<div id="heading">
    <span id="code-italic">underline</span>
</div>
<div id="heading">
    <span id="code-italic">reverse</span>
</div>
<div id="heading">
    <span id="code-italic">strikethrough</span>
</div>
<div id="heading">
    <span id="code-italic">invisible</span>
</div>
<div id="heading">
    <span id="code-bold">fg</span><span id="code-italic">(class)</span>
</div>
<div id="heading-indent">
    <span id="code-italic">black</span>
</div>
<div id="heading-indent">
    <span id="code-italic">red</span>
</div>
<div id="heading-indent">
    <span id="code-italic">green</span>
</div>
<div id="heading-indent">
    <span id="code-italic">orange</span>
</div>
<div id="heading-indent">
    <span id="code-italic">blue</span>
</div>
<div id="heading-indent">
    <span id="code-italic">purple</span>
</div>
<div id="heading-indent">
    <span id="code-italic">cyan</span>
</div>
<div id="heading-indent">
    <span id="code-italic">lightgrey</span>
</div>
<div id="heading-indent">
    <span id="code-italic">darkgrey</span>
</div>
<div id="heading-indent">
    <span id="code-italic">lightred</span>
</div>
<div id="heading-indent">
    <span id="code-italic">lightgreen</span>
</div>
<div id="heading-indent">
    <span id="code-italic">yellow</span>
</div>
<div id="heading-indent">
    <span id="code-italic">lightblue</span>
</div>
<div id="heading-indent">
    <span id="code-italic">pink</span>
</div>
<div id="heading-indent">
    <span id="code-italic">lightcyan</span>
</div>

<div id="heading">
    <span id="code-bold">bg</span><span id="code-italic">(class)</span>
</div>
<div id="heading-indent">
    <span id="code-italic">black</span>
</div>
<div id="heading-indent">
    <span id="code-italic">red</span>
</div>
<div id="heading-indent">
    <span id="code-italic">green</span>
</div>
<div id="heading-indent">
    <span id="code-italic">orange</span>
</div>
<div id="heading-indent">
    <span id="code-italic">blue</span>
</div>
<div id="heading-indent">
    <span id="code-italic">purple</span>
</div>
<div id="heading-indent">
    <span id="code-italic">cyan</span>
</div>
<div id="heading-indent">
    <span id="code-italic">lightgrey</span>
</div>
___

<style>
    #code-bold{
        border-left-style: solid;
        font-weight: bold;
        border-color: rgb(184, 180, 174);
        background-color: rgb(209, 207, 203);
        color: red;
        padding: 0.5rem;
    }
    #code-italic{
        border-color: rgb(184, 180, 174);
        background-color: rgb(209, 207, 203);
        color: rgb(84, 91, 95);
        padding: 0.5rem;
        font-style: italic;
    }
    #heading{
        margin-bottom: 1rem;
        display: inline-block;
        width: 100%;
    }
    #heading-indent{
        margin-bottom: 1rem;
        margin-left: 2rem;
        display: inline-block;
        width: 100%;
    }
</style>