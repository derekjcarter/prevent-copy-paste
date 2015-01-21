# prevent-copy-paste
Javascript library to prevent copy and paste.  This registers the "onpaste" property on inputs and textareas for browsers that do not natively support it.

### Usage

    <!-- Include library -->
    <script src="prevent-copy-paste-min.js"></script>
    
    <!-- Input with onpaste property -->
    <input type="text" onpaste="return false;" />
    
