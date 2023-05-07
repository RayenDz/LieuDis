# LieuDis
<!-- saved from url=(0065)http://105.96.0.195:2023/Gdistance.php?user=1&prs=3&find=&id=4492 -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<link rel="stylesheet" href="./Gdistance_files/style.css">
<link rel="stylesheet" href="./Gdistance_files/icons.css">
<style>
body {background: transparent; font-family: "lucida grande", tahoma, verdana, arial, sans-serif; font-size: 14px;}
</style>
<script>
    function bba(data){
        window.location = "?action=sherch&lieuA=" + data + "&user=" + window.user.value + "&prs=" + window.prs.value;
    }
    
    function datkm(data){
        window.distance.innerHTML = data.value;
        window.iddata.innerHTML = data.options[data.selectedIndex].getAttribute('data');
    }
    
    function urls(obj){
        var lieuB = window.iddata.innerHTML;
        var lieuA = window.lieuA.value;
        var distance = window.distance.innerHTML;
        window.location="?action=edit&user=" + window.user.value + "&prs=" + window.prs.value + "&d=" + distance + "&a=" + lieuA + "&b=" + lieuB;
    }
</script>
</head>
<body>
	<script>
	//parent.window.frames['body1'].txtdashbord.innerHTML = "<il><li></li></ul>";
	parent.window.frames['body1'].txtdashbord.innerHTML = "++++";
	</script>
	<table width="95%" align="center"><tbody><tr><td><input type="text" id="textSearch" name="find" value="" autocomplete="off" style="border: 2px solid #aaa;border-radius: 4px;margin: 2px 0;outline: none;padding: 3px;box-sizing: border-box;transition: 0.3s;font-size: 16px; background: #276495; color: #fff; width: 50%; height: 24px;">
<i class="fas fa-search tbutton" style="cursor: pointer; color: #fff;" onclick="javascript: window.location=&#39;?find=&#39; + window.textSearch.value + &#39;&amp;user=1&amp;prs=3&#39;" alt="Trouve" title="Trouve"></i>
</td><td align="right"><button class="button" onclick="javascript: window.location=&#39;?action=add&amp;user=1&amp;prs=3&#39;"> <i class="fas fa-plus"></i> Ajouter </button></td></tr></tbody></table><script>
	var input = document.getElementById('textSearch');
	input.addEventListener('keyup', function(event){
		event.preventDefault();
		if (event.keyCode === 13){
			window.location='?find=' + window.textSearch.value + '&user=1&prs=3';
		}
	});
	</script><table class="tablErp" id="tableERP" align="center">
<caption class="bk-co">List distance</caption>
<thead><tr align="center"><th>Lieu A</th><th>Lieu B</th><th>Distance Klm</th><th></th><th></th></tr></thead>
<tbody class="tbody">

<tr><td>
</td><td>DOCK ROUIBA
</td><td>275
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9921" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>
</td><td>DOCK METAL SIDI HADJRAS
</td><td>70
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=6571" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>
</td><td>COMPLEXE M'SILA
</td><td>15
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=7054" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>
</td><td>DSP  BEJAIA
</td><td>214
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9363" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>
</td><td>DOCK BETON LAGHOUAT
</td><td>470
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=4492" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>
</td><td>MAGASIN 2 LAGHOUAT
</td><td>470
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=2045" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>
</td><td>285
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9907" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK DAR EL BEIDA
</td><td>1
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=8462" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>PORT D'ALGER
</td><td>18
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=2079" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DECHARGE OUED-SMAR
</td><td>14
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=4277" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DECHARGE PUBLIC KOLEA
</td><td>58
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9410" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>AIN BENIAN
</td><td>25
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=6562" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DECHARGE PUBLIC BLIDA
</td><td>56
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=3097" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DECHARGE MAKTAA KHEIRA(KOLEA)
</td><td>60
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=6188" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>SARL MAGECO ROUIBA
</td><td>10
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9707" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK3 BLIDA
</td><td>60
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=4278" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK EL AFFROUN
</td><td>79
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=3513" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>AMRANI L'ARBRAA
</td><td>60
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=5585" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>SIM AIN ROMANA
</td><td>65
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9286" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>SOSEMIE BLIDA
</td><td>50
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=8955" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DECHARGE PUB. CHIFFA
</td><td>62
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=4366" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>SOPI
</td><td>50
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=8958" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK 04 EL AFFROUN
</td><td>79
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=2376" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK 01 BLIDA
</td><td>60
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=5552" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>ERIAD BLIDA(MOLITEL)
</td><td>60
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=2346" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DECHARGE SIDI-RACHED
</td><td>58
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=6189" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>SOPI RAHMANIA
</td><td>35
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9614" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK AHMER EL AIN
</td><td>74
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=8817" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>CCLS MEB BLIDA
</td><td>50
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=9549" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">

</spam></td></tr><tr><td>DOCK DAR EL BEIDA
</td><td>DOCK BENI SLIMANE
</td><td>132
</td><td align="center" width="10"><a href="http://105.96.0.195:2023/Gdistance.php?action=edit&amp;user=1&amp;prs=3&amp;find=&amp;id=2862" style="background: #2baf6d; text-decoration: none; color: #fff;" class="tbutton"><i class="fas fa-edit"></i></a>
</td><td align="center" width="10"><spam class="tbutton fas fa-trash" style="background: #af2b37; color: gray;">
</spam></td></tr></tbody>
</table>
<table style="width:99%; background: #097A89; color: #fff;" align="center"><tbody><tr><td style="text-align: left; width: 50%;"><span style="color: #AFC9C4;">Afficher la page 1 � 345 de 10334 entr�es</span></td><td style="text-align: right;"><span class="tbutton" style="color:#fff; text-decoration: none;"> 1 </span><a href="http://105.96.0.195:2023/Gdistance.php?strPage=2&amp;user=1&amp;prs=3&amp;find=" class="tbutton" style="color: #fff; text-decoration: none;"> 2 </a><a href="http://105.96.0.195:2023/Gdistance.php?strPage=3&amp;user=1&amp;prs=3&amp;find=" class="tbutton" style="color: #fff; text-decoration: none;"> 3 </a><a href="http://105.96.0.195:2023/Gdistance.php?strPage=4&amp;user=1&amp;prs=3&amp;find=" class="tbutton" style="color: #fff; text-decoration: none;"> 4 </a><span'><a href="http://105.96.0.195:2023/Gdistance.php?strPage=2&amp;user=1&amp;prs=3&amp;find=" class="tbutton" style="color: #fff; text-decoration: none;">&gt;&gt;</a></span'></td></tr></tbody></table>
</body></html>
