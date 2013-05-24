<?php
  list($largura, $altura) = getimagesize('./cus_php.jpg'); //pega o tamanho da imagem
	$img = imagecreatefromjpeg('./cus_php.jpg'); //lê a imagem
	
	for($iAlt=0; $iAlt<$altura; ++$iAlt){
		for($iLarg=0; $iLarg<$largura; ++$iLarg){
			$colors = imagecolorsforindex($img, imagecolorat($img, $iLarg, $iAlt));
			echo "<div style='width:1px; height:1px; background: rgba(".$colors['red'].", ".$colors['green'].", ".$colors['blue'].",
			1); float: left'></div>";
		}
		echo "<div style='clear: both'></div>";
	}
?>
