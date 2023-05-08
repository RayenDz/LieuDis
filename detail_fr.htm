<html>
<head>
<title>JavaScript CRUD</title>
<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/icons.css">
<style rel="stylesheet">
body {margin: 0;padding: 0;font-family: 'Poppins', sans-serif;display: block;}
body: before {content: '';position: fixed;width: 100vw;height: 100vh;background-image: #253614;background-position: center center;background-repeat: no-repeat;background-attachment: fixed;-webkit-background-size: cover;background-size: cover;-webkit-filter: blur(10px);-moz-filter: blur(10px);filter: blur(10px);}
.tableList-table {border: 0.5px solid blue; padding: 5px;margin: auto;width: 90%;}
body > table{width: 80%;}
.table{border-collapse: collapse;border: solid 1px #DDD;border-collapse: collapse;padding: 2px 3px;text-align: center;}
.table.list{width:100%;}
.table td, th {border: 1px solid #dddddd;text-align: left;padding: 8px;}
.table tr:nth-child(even),table.list thead>tr {background-color: #dddddd;}
a{cursor: pointer;text-decoration: underline;color: #0000ee;margin-right: 4px;}
.hide{display:none;}
input[type='button'] {cursor: pointer;border: none;color: #FFF;}
#Db {position:fixed;top:0;left:0;width:100%;height:100%;background-color:rgba(0,0,0,.5);z-index:99999;text-align:center;}
#DB #ModalBt {text-align: center; border-radius:10px; padding: 10px; border: solid 1px #0000F0; position:relative; margin:200px auto; width:400px; display:inline-block; background: rgba(0,0,0,.5); box-shadow: 0 0 5px rgba(159,159,159,0.6); color: #ffffff;}
#Db #ModalBt .close {position:absolute;top:15px;right:15px;font-size: 15px;}
#Db #ModalBt .title {font-size: 20px;margin-top: 10px;color:#fff;}
#Db #ModalBt .text {clear:both;font-size: 14px;margin-bottom: 10px;color:#fff;}
.red {color: #F06F97;}
.green {color: #3ACB1C;}
.bleu {color: #3872DC;}
.yellow {color: #ECF610;}
.w80s {width:80px;   font-size: 16px; background: #276495; color: #fff; height: 24px; padding: 0px; border: 1px solid #4E6189;}
</style>
<script type="text/javascript" src="cruds.php"></script>
<script type="text/javascript">
var codeUnite, codeCamion, codeCamions, codeProduit, codeProduittxt, codeCharg, codeChargtxt,codeOperation;
var val = 0;
const today = new Date();
let day, month, year;
day = today.getDate();
month = today.getMonth() + 1;
year = today.getFullYear();
if (day < 10){day = '0' + day;}
if (month < 10) {month = '0' + month;}

function createInstance(){
	var Http = null;
	if (window.XMLHttpRequest){
		Http = new XMLHttpRequest();
		if (Http.overrideMimeType){
			Http.overrideMimeType('text/html');
		}
	} else if (window.ActiveXObject){
		try {
			Http = new ActiveXObject("Msxml2.XMLHTTP");
		} catch (e) {
			try {
				Http = new ActiveXObject("Microsoft.XMLHTTP");
			} catch (e) {}
		}
	}
	if (!Http) {
		alert('Impossible de créer une instance XMLHTTP');
		return false;
	}
	return Http;
}

function codeUnitef(e){
	for (f=0; f<unite.length; f+=1){
		if(unite[f][0]==e) {
			ShowAlert("Alert Changement d'Unité", "Unité de " + unite[f][1]);
		}
	}
}

function onCamion(){
	codeCamion = window.listm.value;
	for (s=0; s<camion.length; s+=1){
		if(codeCamion == camion[s][0]){
			window.tva.value = camion[s][1];
			window.prive.value = camion[s][2];
			window.Codch.value = camion[s][3];
			window.code.value = camion[s][4];
			if(window.prive.value==0){
				window.code.style.visibility = "visible";
				window.Gtbl0.style.display = "block";
				window.Gtbl1.style.display = "none";
			} else {
				window.code.style.visibility = "hidden";
				window.Gtbl0.style.display = "none";
				window.Gtbl1.style.display = "block";
			}
		}
	}
	if(window.prive.value == 1) {
		texte = "Feuille de Route privé";
		TbModal(1);
	} else texte = "Feuille de Route URCA.CENTRE";
	window.title.innerHTML = texte.toUpperCase();
}

function chekedpes(){
	if(window.pes.checked == true) Ppes = 1; else Ppes = 0;
	return Ppes;
}

function chekedforce(){
	if(window.force.checked == true) {
		window.sforceT.style.display = "none";
		window.force.style.display = "none";
		Pforce = 1;
	} else {
		window.sforceT.style.display = "block";
		window.force.style.display = "block";
		Pforce = 0;
	}
	return Pforce;
}

function chekedretard(){
	if(window.retard.checked == true) Pretard = 1; else Pretard = 0;
	return Pretard;
}

unite = unite.sort();
for (f=0; f<unite.length; f+=1){
	codeUnite += "<option value='"+unite[f][0]+"'>"+unite[f][1]+"</option>";
}

camion = camion.sort();
setTimeout(function(){
	for (s=0; s<camion.length; s+=1){
		if(window.uniteId.value == camion[s][5]){
			codeCamions += "<option value='" + camion[s][0] + "'>" + camion[s][0]+"</option>";
		}
	}
}, 200);

for (ST1=0; ST1<produit.length; ST1+=1){
	codeProduittxt += "<option value='" + produit[ST1][0] + "'>" + produit[ST1][1] + "</option>";
}

produit.sort(sortFunction);
for (ST1=0; ST1<produit.length; ST1+=1){
	codeProduit += "<option value='" + produit[ST1][0] + "'>" + produit[ST1][0] + "</option>";
}

for (ST1=0; ST1<lieu.length; ST1+=1){
	codeChargtxt += "<option value='" + lieu[ST1][0] + "'>" + lieu[ST1][1] + "</option>";
}

lieu.sort(sortFunction);
for (ST1=0; ST1<lieu.length; ST1+=1){
	codeCharg += "<option value='" + lieu[ST1][0] + "'>" + lieu[ST1][0] + "</option>";
}

for (ST1=0; ST1<operation.length; ST1+=1){
	codeOperation += "<option value='" + operation[ST1][0] + "'>" + operation[ST1][1] + "</option>";
}

setTimeout(function(){
	window.Datfr.value = year + "-" + month + "-" + day;
	window.Codunit.innerHTML = codeUnite;
	window.camions.innerHTML = codeCamions;
	window.Codpr.innerHTML = codeProduit;
	window.Codprtxt.innerHTML = codeProduittxt;
	window.charg.innerHTML = codeCharg;
	window.chargtxt.innerHTML = codeChargtxt;
	window.decharg.innerHTML = codeCharg;
	window.dechargtxt.innerHTML = codeChargtxt;
	window.operationtxt.innerHTML = codeOperation;
	window.Codunit.value = window.uniteId.value;
}, 200);

function Reset(){
	window.tva.value = 0;
	window.prive.value = 0;
	window.table.innerHTML = "";
	ResetDfr();
}

function ResetDfr(){
	window.lpn.value = "";
	window.listm.value= "";
	window.Codch.value= "";
	window.code.value= "";
	window.Codpr.value = produit[0][0];
	window.retard.checked  = false;
	window.qte.value = 0;
	window.qte_dech.value = 0;
	window.charg.value  = lieu[0][0];
	window.decharg.value = lieu[0][0];
	window.date_d.value = "";
	window.operationtxt.value = 1;
	window.pes.checked  = false;
	window.force.checked  = false;
	window.distancev.innerHTML = 0;
	window.Codprtxt.value = window.Codpr.value;
	window.chargtxt.value = window.charg.value;
	window.dechargtxt.value = window.decharg.value;
}

function Reparer(){
	ShowAlert('Status', 'Réparation réussie... !');
}

function Modal(options) {
    try {
        document.body.classList.remove("Calce");
        document.getElementById("Db").remove();
    } catch (e) { }

    var closeModal = function() {
        document.body.classList.remove("Calce");
        document.getElementById("Db").remove();
    };
    if(!document.getElementById("Db")) {
        var _background = document.createElement("div"); _background.id = "Db";
        var _dialog = document.createElement("div"); _dialog.id = "ModalBt";
        var _title = document.createElement("div"); _title.classList.add("title");
        var _text = document.createElement("div"); _text.classList.add("text");
        var _btns = document.createElement("div"); _btns.classList.add("btns");

        document.body.classList.add("Calce");
        document.body.appendChild(_background);
        _background.appendChild(_dialog);

        if(options.title !== undefined){
            _title.textContent = options.title;
            _dialog.appendChild(_title);
        }
        if(options.message !== undefined){
            _text.textContent = options.message;
            _dialog.appendChild(_text);
        }
        if(options.buttons === undefined){
            options.buttons = [{label:"OK", handler:function() {} }];
        }

        if(options.buttons) {
            _dialog.appendChild(_btns);
            options.buttons.forEach(function (btn) {
                var _btn = document.createElement("input");
                _btn.setAttribute("type", "button");
                _btn.id = "btn" + btn.label;
                _btn.value = btn.label;
                _btn.classList.add("tbutton", "bout11");
                _btns.appendChild(_btn);
                _btn.addEventListener("click", function() {
                    closeModal();
                    btn.handler();
                });
            });
        }
    }
}

function ShowAlert(title, message){
    Modal({
        title: title,
		message: message,
		buttons:[{label:" Oui ",handler:function(){}}]
    });
}

function ShowConfirm(title, message){
    Modal({
        title: title,
        message: message,
        buttons:[
            {label:" Oui ", handler:function(){}},
            {label:" Non ", handler:function(){ShowAlert("Alert", "Suppression Annuler");}}
        ]
    });
}

function dechargd(e){
	for (ST3=0; ST3<distance.length; ST3+=1){
		if(distance[ST3][0] == window.charg.value && distance[ST3][1] == window.decharg.value){
			val = 1;
			window.distancev.innerHTML = distance[ST3][2];
			tlieu();
		}
	}
	if(val==0){
		ShowAlert("Attestation", "Distance Introuvable ..!");
		window.decharg.focus = true;
		chekedforce();
	}
}

var selectedRow = null
function onFormSubmit(){
	if (validate()){
		var formData = readFormData();
		if (selectedRow == null)
			insertNewRecord(formData);
		//resetForm();
	} else {
		ShowAlert("Attestation", "Matricule Introuvable ?");
		window.listm.focus();
	}
}

function htmlToMysql(){
	var Http = createInstance();
	var table = document.getElementById("BodyTable");
	var html = "";
	for(i=0; i<table.rows.length; i++){
		html += ":" + window.prive.value;
		html += "|" + window.user.value;
		html += "|" + window.tva.value;
		html += "|" + window.Codunit.value;
		html += "|" + table.rows[i].cells[0].innerHTML;
		html += "|" + window.listm.value;
		html += "|" + window.code.value;
		html += "|" + table.rows[i].cells[1].innerHTML;
		html += "|" + table.rows[i].cells[2].innerHTML;
		html += "|" + table.rows[i].cells[3].innerHTML;
		html += "|" + table.rows[i].cells[4].innerHTML;
		html += "|" + table.rows[i].cells[5].innerHTML;
		html += "|" + table.rows[i].cells[6].innerHTML;
		html += "|" + table.rows[i].cells[7].innerHTML;
		html += "|" + table.rows[i].cells[8].innerHTML;
		html += "|" + table.rows[i].cells[9].innerHTML;
		html += "|" + table.rows[i].cells[10].innerHTML;
		html += "|" + table.rows[i].cells[11].innerHTML;
		html += "|" + table.rows[i].cells[12].innerHTML;
	}
	var pmeters = "action=add&data=" + html;

	Http.open('post',"add1f.php",true);
	Http.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
	Http.send(pmeters);

	Http.onreadystatechange = function() {
		if (Http.readyState == 3) {
			window.myFormAlert.innerHTML = "Chargement en cours ...";
		}
		if (Http.readyState == 4) {
			ShowAlert("Attestation", "Feuille de route N° :" + Http.responseText);
			PrintFR(Http.responseText);
			Reset();
		}
	}
}

function PrintFR(data){
	window.open("print.php?ft=" + data);
}

function readFormData(){
	var formData = {};
	formData["Datfr"] = window.Datfr.value,
	formData["lpn"] = window.lpn.value,
	formData["Codpr"] = window.Codpr.value,
	formData["qte"] = window.qte.value,
	formData["qte_dech"] = window.qte_dech.value,
	formData["charg"] = window.charg.value,
	formData["decharg"] = window.decharg.value,
	formData["date_d"] = window.date_d.value,
	formData["operation"] = window.operationtxt.value,
	formData["retard"] = chekedretard(),
	formData["pes"] = chekedpes(),
	formData["force"] = chekedforce(),
	formData["distancev"] = window.distancev.innerHTML;
	return formData;
}

function insertNewRecord(data) {
	var table = window.tableList.getElementsByTagName('tbody')[0];
	var newRow = table.insertRow(table.length);
	cell1 = newRow.insertCell(0);
	cell1.innerHTML = data.Datfr;
	cell2 = newRow.insertCell(1);
	cell2.innerHTML = data.lpn;
	cell3 = newRow.insertCell(2);
	cell3.innerHTML = data.Codpr;
	cell4 = newRow.insertCell(3);
	cell4.innerHTML = data.qte;
	cell5 = newRow.insertCell(4);
	cell5.innerHTML = data.qte_dech;
	cell6 = newRow.insertCell(5);
	cell6.innerHTML = data.charg;
	cell7 = newRow.insertCell(6);
	cell7.innerHTML = data.decharg;
	cell8 = newRow.insertCell(7);
	cell8.innerHTML = data.date_d;
	cell9 = newRow.insertCell(8);
	cell9.innerHTML = data.operation;
	cell10 = newRow.insertCell(9);
	cell10.innerHTML = data.retard;
	cell13 = newRow.insertCell(10);
	cell13.innerHTML = data.distancev;
	cell11 = newRow.insertCell(11);
	cell11.innerHTML = data.pes;
	cell12 = newRow.insertCell(12);
	cell12.innerHTML = data.force;
	cell14 = newRow.insertCell(13);
	cell14.innerHTML = "<span class='tbutton' onClick='onDelete(this)'><i class='fas fa-trash'></i></span>";
}

function resetForm(){
	window.lpn.value = "";
	window.camions.value = "";
	window.Codpr.value = produit[0][0];
	window.retard.checked  = false;
	window.qte.value = 0;
	window.qte_dech.value = 0;
	window.charg.value  = lieu[0][0];
	window.decharg.value = lieu[0][0];
	window.date_d.value = "";
	window.operationtxt.value = 1;
	window.pes.checked  = false;
	window.force.checked  = false;
	selectedRow = null;
}
/*
function onEdit(td) {
	selectedRow = td.parentElement.parentElement;
	window.fullName.value = selectedRow.cells[0].innerHTML;
	window.email.value = selectedRow.cells[1].innerHTML;
	window.salary.value = selectedRow.cells[2].innerHTML;
	window.city.value = selectedRow.cells[3].innerHTML;
}

function updateRecord(formData) {
	selectedRow.cells[0].innerHTML = formData.fullName;
	selectedRow.cells[1].innerHTML = formData.email;
	selectedRow.cells[2].innerHTML = formData.salary;
	selectedRow.cells[3].innerHTML = formData.city;
}
*/
function onDelete(td) {
	ShowConfirm("Atention","Êtes-vous sûr de vouloir supprimer cet enregistrement ?");
	row = td.parentElement.parentElement;
	window.tableList.deleteRow(row.rowIndex);
	resetForm();
}

function Reset(){
	window.BodyTable.innerHTML = "";
	window.Gtbl0.style.display = "none";
	window.Gtbl1.style.display = "none";
	ResetDfr();
}

function TbModal(prive){
	var Http = createInstance();
	var StrTache = "<div class='myPop-title'>";
	StrTache += "<span id='titlem' class='myPop-title-value'></span>";
	StrTache += "</div>";
	StrTache += "<div class='forms' style='padding: 5px; width:97%; height:300px;'>";
	StrTache += "   <input type='text' id='myInput' onkeyup='findTable();' placeholder='Recherche de noms..' title='Tapez un nom' style='width: 95%;'>";
	StrTache += "   <div style='height: 236px; width: 95%; overflow: auto'>";
	StrTache += "       <table id='tablech' class='tablErp' style='position:absolute; width: 100%;'></table>";
	StrTache += "   </div>";
	StrTache += "   <p style='position:absolute; margin: auto; width: 100%; text-align: center;'><button class='button' OnClick='closem();'> Fermer </button><p>";
	StrTache += "</div>";
    var div = document.createElement('div');
    div.id = 'modal';
    div.className = 'myPop';
    document.body.appendChild(div);
    window.modal.innerHTML = StrTache;
    window.titlem.innerHTML = "List Chauffeur Privé";
	var pmeters = "action=chauffeur_table&prive=" + prive + "&matcode=" + window.listm.value + "&unite=" + window.uniteId.value;

	Http.open('POST', "add.php", true);
	Http.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
	Http.send(pmeters);
	
	Http.onreadystatechange = function(){
		if(Http.readyState == 4){
			window.tablech.innerHTML = Http.responseText;
		}
	}
	window.bt1.style = "background: red; text-decoration: none; pointer-events: none;";
	window.bt2.style = "background: red; text-decoration: none; pointer-events: none;";
	window.bt3.style = "background: red; text-decoration: none; pointer-events: none;";
	window.bt4.style = "background: red; text-decoration: none; pointer-events: none;";
	window.bt5.style = "background: red; text-decoration: none; pointer-events: none;";
}

function findTable() {
    var input, filter, table, tr, td, i, txtValue;
    input = document.getElementById("myInput");
    filter = input.value.toUpperCase();
    table = document.getElementById("tablech");
    tr = table.getElementsByTagName("tr");
    for (i = 0; i < tr.length; i++) {
        td = tr[i].getElementsByTagName("td")[0];
        if (td) {
            txtValue = td.textContent || td.innerText;
            if (txtValue.toUpperCase().indexOf(filter) > -1) {
                tr[i].style.display = "";
            } else {
                tr[i].style.display = "none";
            }
        }       
    }
}

function Reporter(data1,data2){
	window.code.value = data1;
	window.Codch.value = data2;
	closem();
}

function DoModal(){
	var Http = createInstance();
	var StrTache = "<div class='myPop-title'>";
	StrTache += "<span id='titlem' class='myPop-title-value'></span>";
	StrTache += "</div>";
	StrTache += "<div class='forms' style='padding: 10px; width:95%; height:313px;'>";
	StrTache += "<label class='LbT'>Sous Tritance: </label><br><select id='st' class='style8 dw80'></select>\n";
	StrTache += "<label class='LbT'>Nom chauffeur: </label><br><input type='text' id='nom' class='style8 dw80' autocomplete='off'>\n";
	StrTache += "<label class='LbT'>Mobil 1: </label><br><input type='text' id='mobil1' class='style8 dw80' autocomplete='off'>\n";
	StrTache += "<label class='LbT'>Mobil 2: </label><br><input type='text' id='mobil2' class='style8 dw80' autocomplete='off'>\n";
	StrTache += "<label class='LbT'>N°Permis Conduire: </label><br><input type='text' id='n_permis_conduire' class='style8 dw80' autocomplete='off'>\n";
	StrTache += "<p style='text-align:center'><button class='button' style='width: 30%' OnClick='BMedesin();'> Enregistrer </button> <button class='button' style='width: 30%' OnClick='closem();'> Fermer </button><p>";
	StrTache += "</div>";
    var div = document.createElement('div');
    div.id = 'modal';
    div.className = 'myPop';
    document.body.appendChild(div);
    window.modal.innerHTML = StrTache;
    window.titlem.innerHTML = "Ajouter un Chauffeur Privé";
	combost();
}

function BMedesin(){
	var Http = createInstance();	
	var st = window.st.value;
	var nom = window.nom.value;
	var mobil1 = window.mobil1.value;
	var mobil2 = window.mobil2.value;
	var npc = window.n_permis_conduire.value;
	var pmeters = "action=chauffeur_add&st="+st+"&nom="+nom+"&mobil1="+mobil1+"&mobil2="+mobil2+"&npc="+npc;
	
	Http.open('POST', "add.php", true);

	Http.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
	Http.send(pmeters);

	Http.onreadystatechange = function(){
		if(Http.readyState == 4){
			//window.doctor.innerHTML = Http.responseText;
		}
	}
	setTimeout("TbModal()", 1000);
	closem();
}

function combost(){
	var Http = createInstance();	
	var pmeters = "action=chauffeur_list&Codunit=" + window.Codunit.value;
	Http.open('POST', "add.php", true);
	Http.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
	Http.send(pmeters);
	
	Http.onreadystatechange = function(){
		if(Http.readyState == 4){
			window.st.innerHTML = Http.responseText;
		}
	}
}

function closem(){
	document.body.classList.remove("myPop");
    window.modal.remove();
	window.bt1.style = "background: rgba(0,0,0,0); text-decoration: none; pointer-events: block;";
	window.bt2.style = "background: rgba(0,0,0,0); text-decoration: none; pointer-events: block;";
	window.bt3.style = "background: rgba(0,0,0,0); text-decoration: none; pointer-events: block;";
	window.bt4.style = "background: rgba(0,0,0,0); text-decoration: none; pointer-events: block;";
	window.bt5.style = "background: rgba(0,0,0,0); text-decoration: none; pointer-events: block;";
}

function Reparer(){
	ShowAlert('Status', 'Réparation réussie... !');
}

function validate(){
	isValid = true;
	if (window.listm.value == "") {
		isValid = false;
	} else {
		isValid = true;
	}
	return isValid;
}
function sortFunction(a, b) {if (a[0] === b[0]) {return 0;} else {return (a[0] < b[0]) ? -1 : 1;}}

setTimeout(function(){
	window.Codprtxt.value = window.Codpr.value;
	window.chargtxt.value = window.charg.value;
	window.dechargtxt.value = window.decharg.value;
},200);
/*
window.title.innerHTML = texte.toUpperCase();
if(window.prive.value == 1) texte = "privé"; else texte = "URCA.CENTRE";
*/

function tlieu(){
	var Operation = 0;
	var type = 0;
	var lieu1 = window.charg.value;
	var lieu2 = window.decharg.value;
	for (f=0; f<lieu.length; f+=1){
		if(lieu1==lieu[f][0]){
			type = lieu[f][2];
		}
	}
	var organisme = lieu2.substr(0,3);
	var lieua = lieu2.substr(-3);
	var livrer =  lieu1.substr(0,3);
	var lieub =  lieu1.substr(-3);

	if(livrer != organisme){
		if(type == 6) { //Producteur
			Operation = 4;
		} else {
			Operation = 1;
		}
		if(type == 11) Operation = 3;
	} else {
		if(lieua!=lieub){
			if(type == 11) Operation = 3; else Operation = 2;
			if(type == 8) Operation = 6;
		} else {
			if(type == 6) Operation = 4;
			if(type == 8) Operation = 6;
			if(type == 7) Operation = 10;
			if(type == 1 || type == 2 || type == 3 || type == 4 || type == 5) Operation = 9;
			if(type == 11) Operation = 3;
		}
	}
	window.operationtxt.value = Operation;
}
</script>
</head>
<body>
<input type="hidden" id="prive">
<input type="hidden" id="user" value="1">
<input type="hidden" id="tva">
<input type="hidden" id="uniteId" value="103">
<h1 id="title" style="color: #fff;">Feuille de Route</h1>
<fieldset>
	<legend>Feuille de Route</legend>
	<table width="90%" class="forms" align="center" style="color: #ccc;">
		<tbody>
			<tr><td align="right" width="16%">Unité :<td style="width: 34%;">
				<select id="Codunit" OnChange="codeUnitef(this.value);" style="width:250px;"></select>
				<td align="right" width="16%">Journée du : <td style="width: 34%;"><input type="date" id="Datfr" value="" style="width:120px;">
		</tr>
		<tr><td align="right" width="16%">Camion : <td style="width: 34%;"><input onChange="onCamion()" list="camions" id="listm" placeholder="Choisissez un camion matricul" style='width:250px;' class="w80s">
			<datalist id="camions"></datalist>
		<td align="right" width="16%">Chauffeur :<td style="width: 34%;">
			<table cellspacing="1" cellpadding="1"><tbody><tr><td><input type="text" id="Codch" value="" style="width:250px;">
			<input type="hidden" id="code" value="" style="visibility: visible;">
			<td>
			<a href="javascrpit:" id="Gtbl0" onclick="TbModal(0)" class="tbutton" style="display: none;"><i class="fas fa-city"></i></a>
			<a href="javascrpit:" id="Gtbl1" onclick="TbModal(1)" class="tbutton" style="display: none;"><i class="fas fa-truck-loading"></i></a>
			</tr></tbody></table>
		</tr><tr>
		<td style="width: 16%;"><td><input type="checkbox" id="retard" value="1"><label for="retard">Retard (hors période)</label>
		</tr><tr>
			<td align="right" width="16%">L.P N° : <td width="34%"><input type="text" id="lpn" style="width:100px;" autocomplete="off">
			<td align="right" width="16%">Produit  : <td width="34%"><select id="Codpr" style="width:80px;" class="w80s" onchange="window.Codprtxt.value = this.value"></select>
			<select id="Codprtxt" placeholder="Choisissez un Produit" style="width:170px;" class="w80s" onchange="window.Codpr.value = this.value"></select>
			<tr><td align="right" width="16%">Quantité : <td width="34%"><input type="text" id="qte" value="0" style="width: 50px;">
			<td align="right" width="16%">Quantité Déchargée : <td width="34%"><input type="text" id="qte_dech" value="0" style="width: 50px;">
		</tr><tr>
			<td align="right" width="16%">Chargement : <td width="34%"><select id="charg" style="width:80px;" class="w80s" onchange="window.chargtxt.value = this.value"></select>
			<select id="chargtxt" style="width:250px;" class="w80s" onchange="window.charg.value = this.value"></select>
			<td align="right" width="16%">Déchargement : <td width="34%"><select id="decharg" style="width:80px;" class="w80s" onchange="dechargd(this.value); window.dechargtxt.value = this.value;"></select>
			<select id="dechargtxt" style="width:250px;" class="w80s" onchange="dechargd(this.value); window.decharg.value = this.value;"></select>
			<span id="distancev">0</span> Km
		</tr><tr>
			<td align="right" width="16%">Date Déchargée : <td width="34%"><input type="date" id="date_d" style="width:120px;">
			<td align="right" width="16%">Opération : <td width="34%"><select id="operationtxt" style="width:200px;"></select>
		</tr><tr>
			<td align="right" width="16%"><label for="pes">Pesée : </label><td width="34%"><input type="checkbox" id="pes" value="1">
			<td align="right"><label id="sforceT" for="force" style="display: none;">Rotation forcée : </label><td><input type="checkbox" id="force" value="1" style="display: none;">
		</tr><tr><td colspan="4" align="center">
			<a href="javascript:" id="bt1" class="button" style="text-decoration: none;" onclick="onFormSubmit();"><i class="fa fa-plus-circle green"></i> Enregitrer </a> 
			<a href="javascript:" id="bt2" class="button" style="text-decoration: none;" onclick="htmlToMysql();"><i class="fa fa-print bleu"></i> Imprimer </a>
			<!--<a href="javascript:" id="bt3" class='button' style="text-decoration: none;" OnCLick="NewFR();"><i class="fa fa-plus-circle red"></i> Nouveau FR</a>-->
			<a href="javascript:" id="bt4" class="button" style="text-decoration: none;" onclick="Reset();"><i class="fa fa-retweet yellow"></i> Reset </a>
			<a href="javascript:" id="bt5" class="button" style="text-decoration: none;" onclick="DoModal();" alt="Ajouter un Chauffeur green" title="Ajouter un Chauffeur"><i class="fas fa-plus green"></i> Ajouter un Chauffeur </a>
	</tr></tbody></table>
</fieldset>
<br/>
<div class="tableList-table">
	<table class="tablErp" width="95%" align="center" id="tableList">
		<thead>
			<tr><th>Date F.R<th>N° L.P<th>Produit<th>Qte<th>Qte déch<th>Charg<th>Décharg<th>Date décharg<th>Opération<th>Pes<th>Km<th><th><th></tr>
		</thead>
		<tbody id="BodyTable"></tbody>
	</table>
</div>
<span id="demo"></span>
</body>
</html>
