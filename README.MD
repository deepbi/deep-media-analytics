# Deep Media Analytics (DMA)
Follow these steps to start using DMA for collecting your data:

* Obtain streamKey, accessKey from Deep.BI
* Download the script: stub.min.js
* Insert the code within the ```<head>``` section between ```<script>``` tag:

```
<head>
  <!-- your head code here -->
  <script type="text/javascript">
    // here goes the code from stub.min.js
  </script>
</head>

```

* Call DeepTracker function abywhere in HTML head or body section, but after the stub.min.js script code:

```
<body>
  DeepTracker(streamKey, accessKey)();
  
  <!-- your body code here -->

</body>
```