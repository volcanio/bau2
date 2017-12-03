# bau2
bauevent2


$bau1 = rand(1,12);




      
      
      if($bau1 == 1)
      if(isset($_POST['item_1'])){
      	if($gebruiker['blacksilver'] < 10) $error = '<div class="error">Ops VocÃª nÃ£o tem Black silver Suficiente.</div>';
      	else {
	    mysql_query("UPDATE `gebruikers` SET `blacksilver`=`blacksilver`-'10', `silver`=`silver`+'2500',`Rank2`=`rank2`+'10' WHERE `user_id`='".$_SESSION['id']."'");
      	$error = '<div class="accept">Bau  Aberto  ! vocÃª ganhou <img src="../images/icons/silver.png" style="vertical-align:middle;">2500 silver!</div>';
      		}
		}
     	if($bau1 == 2)
		 if(isset($_POST['item_1'])){
      	if($gebruiker['blacksilver'] < 10) $error = '<div class="error"Ops VocÃª nÃ£o tem Black silver Suficiente.</div>';
      	else {
	    mysql_query("UPDATE `gebruikers` SET `blacksilver`=`blacksilver`-'10', `silver`=`silver`+'1500',`Rank2`=`rank2`+'10' WHERE `user_id`='".$_SESSION['id']."'");
      	$error = '<div class="accept">Bau aberto 1 ! vocÃª ganhou <img src="../images/icons/silver.png" style="vertical-align:middle;">1500 silver !</div>';
      		}
		}
    	if($bau1 == 3)
		 if(isset($_POST['item_1'])){
      	if($gebruiker['blacksilver'] < 10) $error = '<div class="error">Ops VocÃª nÃ£o tem Black silver Suficiente  .</div>';
      	else {
	    mysql_query("UPDATE `gebruikers` SET `blacksilver`=`blacksilver`-'10', `silver`=`silver`+'20000',`Rank2`=`rank2`+'10' WHERE `user_id`='".$_SESSION['id']."'");
      	$error = '<div class="accept">Bau aberto  ! vocÃª ganhou <img src="../images/icons/silver.png" style="vertical-align:middle;">20000 silver !</div>';
      		}
		}
		if($bau1 == 4)
		 if(isset($_POST['item_1'])){
      	if($gebruiker['blacksilver'] < 10) $error = '<div class="error">Ops VocÃª nÃ£o tem Black silver Suficiente  .</div>';
      	else {
	    mysql_query("UPDATE `gebruikers` SET `blacksilver`=`blacksilver`-'10', `blacksilver`=`blacksilver`+'5',`rank2`=`rank2`+'10' WHERE `user_id`='".$_SESSION['id']."'");
      	$error = '<div class="accept">Bau aberto  ! vocÃª ganhou  <img src="images/mercadonegro/blacksilver.png" style="vertical-align:middle;">5 blacksilver!</div>';
      		}
		}
