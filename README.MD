To start using Deep Media Analytics and collectin your data follow these steps:

1. Obtain streamKey, accessKey from Deep.BI
2. Download the script: stub.min.js
3. Insert the code within the ```<head>``` section between ```<script>``` tag:

```
<head>
  <!-- your head code here -->
  <script type="text/javascript">
    // here goes the code from stub.min.js
  </script>
</head>

```

4. Call DeepTracker function abywhere in HTML head or body section, but after the stub.min.js script code:

```
<body>
  DeepTracker(streamKey, accessKey)();
  
  <!-- your body code here -->

</body>
```