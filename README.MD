To start using Deep Media Analytics and collectin your data follow these steps:

1. Obtain streamKey, accessKey from Deep.BI
2. Download the script: stub.min.js
3. Insert the code within the head section between ```<script>``` tag:

```
<script type="text/javascript">
  //here goes the code from stub.min.js
</script>
```

4. Call DeepTracker function somewhere in HTML head or body section, but after the stub.min.js script code:

```
DeepTracker(streamKey, accessKey)()
```