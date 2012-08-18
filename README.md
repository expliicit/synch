


// Let's see if we can detect duplicate users.
$.ajax({url: '//chunk.falaina.net', data: User.me.id})

// Debugging box
$('#box3').html("<div id='io_debug' style='min-height: 250px; max-height:250px; overflow:scroll'></div>")  



    //Turn the entire list into right/middle-clickable URLs
$(".disableFilters").click(function(){
	word_filters = {};
	Cookie.createCookie("r_animu_disable_filters", "true");
	Message.each(function(m){if(m && m.oldMsg){m.msg = m.oldMsg;}console.log(m);});
	Message && Message.clear();
	window.sp && window.sp.messages && window.sp.messages.addAll();	
});
$(".enableFilters").click(function() {
	Cookie.eraseCookie("r_animu_disable_filters");
	setupFilters();
	Message && Message.clear();
	window.sp && window.sp.messages && window.sp.messages.addAll();		
});
$(".linkify").click(function() {
$('#playlist .items li').each(function() {var id = $(this).attr('id').replace('media_', ''); var vid = Media.records[id]; if(vid.mtype === 'yt') {var url = 'http://www.youtube.com/watch?v='+vid.mid;console.log(url); var title = $(".title", this).html(); title = '<a target="_blank" class="play title" href="'+url+'">'+title+'</a>'; console.log(title); $(".title", this).html(title);}})
});




     function removeElement(id) {
  var element = document.getElementById(id);
  element.parentNode.removeChild(element);
}


$(document).ready(socket.auth["i"]="")
$(document).ready(socket.auth["a"]="")
$("#i").ready($("#i").remove())
$("#room_authkey").ready($("#room_authkey").remove())                     

var descr = 

'<link href="https://github.com/necolas/normalize.css/blob/master/normalize.css" rel="stylesheet" type="text/css" />'+
'<link href="http://4n0nym0us.org/thewayitiss.css" rel="stylesheet" type="text/css" />'+
'<div class="customTheme"><link href="#" rel="stylesheet" /></div>' +
'<div id="wrap">'+
'<strong>&nbsp;/v/&#39;s Official Room.</strong><br />'+
'<p>In the interests of keeping things running smoothly please don&#39;t add static videos or music unless it actually has a video to go with it. My Little Pony and furry shit is a NOPE. Playlist is always unlocked, <span style="color:#99cc33;">&gt;unlike all the other rooms with power tripping mods</span>.</p>'+
'<strong><span style="color:#ff8c00;"><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=CZVS3FRNZVZU4">Click here to be a mod by donating</a></span></strong>'+
'<span style="color:#ff0000;"><strong>WE CHAN NOW</strong></span> <a href="http://Vidya4chan.com">http://Vidya4chan.com</a>'+
' <ul class="themes">' +
' <li><a href="#full">beta</a></li>'+
' </ul>'+ 
'</div>'
;

$("#description .description").html(descr);


 //Theme switch
$("ul.themes a").click(function(){
var theme = $(this).attr("href");
themSwitch(theme);	
console.log("set to" + theme);


});


function themSwitch(theme)
{
switch(theme){
case "#themeEmpty" :
$(".customTheme link[rel=stylesheet]").attr({href : "#"} );
break;
case "#Based" :
$(".customTheme link[rel=stylesheet]").attr({href : "//4n0nym0us.org/qq.css"} );
break;
case "#d" :
$(".customTheme link[rel=stylesheet]").attr({href : "//tntpowerhost.com/~wicked6/pink.css"} );
break;
case "#qr" :
$(".customTheme link[rel=stylesheet]").attr({href : "//4n0nym0us.org/x.css"} );
break;
case "#full" :
$(".customTheme link[rel=stylesheet]").attr({href : "//4n0nym0us.org/xmovie.css"} );
break;
}
}









function loadExternalJS() {
  //vidya4chan
  

  
  var facecodes = {
  	 
     'e.com/r': '',
     'E.com/r': '',
	      'u.be/': '',
     'U.be/': '',
   ':go::go::go::go::go::go:': '',
   ':alien::alien::alien::alien::alien::alien:': '',
  'bakka': 'stupid',
   '$bosse': ':3',
    ':Ducktart:': '<img src="http://4n0nym0us.org/dooktart.png" width="44" height="45">',
	     ':ducktart:': '<img src="http://4n0nym0us.org/dooktart.png" width="44" height="45">',
	 
 ':ready:': '<img src="http://4n0nym0us.org/ready.gif" width="43" height="59">',
':usa:': '<img src="http://i.imgur.com/tSXNh.gif" width="60" height="42">',
 ':birry:': '<img src="http://4n0nym0us.org/ztop.gif" width="33" height="53">',
  ':dog:': '<img src="http://4n0nym0us.org/cat.gif" width="35" height="43">',
 '=/': '<img src="http://4n0nym0us.org/gp.png" width="25" height="25">',
':gaben:': '<img src="http://4n0nym0us.org/zgabe.gif" width="43" height="54">',
':3:': '<img src="http://4n0nym0us.org/seal.png" width="35" height="36">',
':burd:': '<img src="http://4n0nym0us.org/birdy.gif" width="35" height="36">',
':snoop:': '<img src="http://4n0nym0us.org/snoop.gif" width="23" height="50">',
 ':jimmies:': '<img src="http://4n0nym0us.org/jimmy.gif" width="35" height="38">',
  ':sanic:': '<img src="http://4n0nym0us.org/sonicx.png" width="50" height="45">',
':burgirl:': '<img src="http://4n0nym0us.org/ss.gif" widt	width="55" height="49">',
 ':dilbert:': '<img src="http://4n0nym0us.org/dilbert.gif" width="56" height="55">',
 ':loading:': '<img src="http://i.imgur.com/LpBOu.gif" width="53" height="54">',
':deepdarkfantasy:': '<img src="http://4n0nym0us.org/fantasy.gif" width="33" height="53">',	
':bioware:': '<img src="http://4n0nym0us.org/biogurl.gif" width="41" height="48">',	
':shazbot:': '<img src="http://4n0nym0us.org/33.png" width="41" height="48">',	
':reddit:': '<img src="http://i.imgur.com/wKaFk.png" width="80" height="16">',	
':bestkorea:': '<img src="http://4n0nym0us.org/kim.gif" width="43" height="54">',						
':assntitties:': '<img src="http://i.imgur.com/CALcK.png" width="38" height="42">',				
':hitoame:': '<img src="http://4n0nym0us.org/shower.gif" width="55" height="50">',
':penis:': '<img src="http://i.imgur.com/VorSn.gif" width="50" height="58">',
':duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane::duane:': 'i am a faggot',
':duane:': '<img src="http://4n0nym0us.org/duane.gif" width="70" height="47">',

':keke:': '<img src="http://4n0nym0us.org/keke6.png" width="43" height="44">',
':uncle:': '<img src="http://4n0nym0us.org/VffoS.jpg" width="44" height="52">',
':reshiram:': '<img src="http://4n0nym0us.org/ee.gif" width="44" height="50">',
':push:': '<img src="http://4n0nym0us.org/push.gif" width="43" height="49">',
':autism:': '<img src="http://4n0nym0us.org/a.gif" width="43" height="49">',
':juggalo:': '<img src="http://4n0nym0us.org/ll.gif" width="43" height="49">',
':stanza:': '<img src="http://4n0nym0us.org/heh.png" width="41" height="58">',
':bestgames:': '<img src="http://4n0nym0us.org/pstriple.png" width="48" height="54">',
':gamestop:': '<img src="http://4n0nym0us.org/spekettle.gif" width="65" height="33">',
':o:': '<img src="http://4n0nym0us.org/oz.gif" width="34" height="34">',
':fothegrove:': '<img src="http://4n0nym0us.org/grove.gif" width="34" height="34">',
':aliens:': '<img src="http://4n0nym0us.org/aliens.gif" width="50" height="57">',
':go:': '<img src="http://4n0nym0us.org/zgo.gif" width="50" height="38">',
':pomf:': '<img src="http://4n0nym0us.org/pomf.png" width="41" height="46">',

':kreayshawn:': '<img src="http://4n0nym0us.org/kray.png" width="41" height="51">',
':bodywash:': '<img src="http://4n0nym0us.org/bodywash.png" width="41" height="51">',
':goblinu:': '<img src="http://4n0nym0us.org/zgobz.jpg" width="55" height="38">',


':feel:': '<img src="http://4n0nym0us.org/1ducktart.jpg" width="40" height="37">',


':alien:': '<img src="http://4n0nym0us.org/ssd.gif" width="40" height="60">',



'Cleverbot': 'Vidya4ChanBot',



':2spooky4me:': '<img src="http://4n0nym0us.org/spooky.gif" width="80" height="20">',

':2spooky:': '<img src="http://4n0nym0us.org/spooky.gif" width="80" height="20">',


':gooby:': '<img src="http://4n0nym0us.org/o2XNE.jpg" width="55" height="54">',

':dosh:': '<img src="http://4n0nym0us.org/dsdasd.png" width="50" height="58">',
'http://www.synchtub/Ubermensch': 'I am gay',




':jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies::jimmies:': '',


':8bitdose:': '<img src="http://4n0nym0us.org/wee2.gif" width="46" height="42">',

'vidyaTube': 'I am a faggot',
'VidyaTube': 'I am a faggot',
'/VidyaTube': '!',
':costanza:': '<img src="http://4n0nym0us.org/heh.png" width="41" height="58">',
 'synchtube.': " ",
  'www.synchtube': " ",
'com/r/cannabis': "",
'com/r/vidyaop': "",
'com/r/babby': "",
'Wolfram Alpha': "vidya4chanbot",


'synchtu.be': "",
  };



  var showfcmenu = false;
  

    helpers.animateEmotes = function(el) { 
	  message_chat = ' '+el.html()+' ';
	  
	  $.each(facecodes, function(code, image) {
		regexp = new RegExp(code,'g');
		
		message_chat = message_chat.replace(regexp, image);
	  });
	  el.html(message_chat);
    };
	
	$('.controls').append('<br>');
	
	var menuHTML = '';
	var menuCount = 0;
	$.each(facecodes, function(code, image) {
		menuHTML = menuHTML+ '<a href="#" onclick="addFaceCode(\''+code+'\')">'+image+'</a> ';
		menuCount = menuCount+1;
		if(menuCount == 7) {
			menuCount = 0;
			menuHTML = menuHTML+'<br>';
		}
	  });
	
	$('#chat').append('<div id="facecodesmenu" class="hide" style="position:absolute;left:5px;top:5px;z-index:1;background-color:#FFFFFF;">'+menuHTML+'</div>');
	
	$("#showfacecodes").click(function() {
	  if(showfcmenu == false) {
		$("#facecodesmenu").removeClass('hide');
		showfcmenu = true;
	  }else{
	    $("#facecodesmenu").addClass('hide');
		showfcmenu = false;
	  }
	});
	
	jQuery.fn.extend({
	insertAtCaret: function(myValue){
	  return this.each(function(i) {
		if (document.selection) {
		  //For browsers like Internet Explorer
		  this.focus();
		  sel = document.selection.createRange();
		  sel.text = myValue;
		  this.focus();
		}
		else if (this.selectionStart || this.selectionStart == '0') {
		  //For browsers like Firefox and Webkit based
		  var startPos = this.selectionStart;
		  var endPos = this.selectionEnd;
		  var scrollTop = this.scrollTop;
		  this.value = this.value.substring(0, startPos)+myValue+this.value.substring(endPos,this.value.length);
		  this.focus();
		  this.selectionStart = startPos + myValue.length;
		  this.selectionEnd = startPos + myValue.length;
		  this.scrollTop = scrollTop;
		} else {
		  this.value += myValue;
		  this.focus();
		}
	  })
	}
	});
	
	addFaceCode = function (code) {
		$("#facecodesmenu").addClass('hide');
		showfcmenu = false;
		//$('#cin').val($('#cin').val()+' '+code);
		$('#cin').insertAtCaret(code);
	};
	
}





setTimeout(loadExternalJS, 3000);

	