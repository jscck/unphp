# unphp
php decode tool, hex to string etc.


## **Demo** ##

[https://jscck.github.io/unphp/](https://jscck.github.io/unphp/)


This tool use to decode php code, writed by javascript. make more fast than <a href="http://www.unphp.net/" target="_blank">UnPHP - The Online PHP Decoder</a>, just use local explain.


**Decode:**

	<?php 
	${"\x47\x4c\x4f\x42\x41L\x53"}["o\x75\x68\x6dz\x79l\x78\x66\x62\x6ai"]="fi\x6ct\x65r\x45\x6cem\x65\x6e\x74";
	${"GL\x4f\x42\x41L\x53"}["\x62\x61\x71f\x69\x6de\x6c\x77\x6fw"]="\x73t\x61r\x74\x50i\x6edex";
	...
	?>

**Output:**

    <?php 
	${"GLOBALS"}["ouhmzylxfbji"]="filterElement";
	${"GLOBALS"}["baqfimelwow"]="startPindex";
	...
	?>		



Only for study and research.

---
MIT license
