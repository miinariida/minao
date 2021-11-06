<?php 

ob_start();
$API_KEY = '2010668295:AAHOAxU2PpN4SG5kE8b3sD0zCGNPCxWjz58'; #توكنك
define('API_KEY',$API_KEY);
echo file_get_contents("https://api.telegram.org/bot" . API_KEY . "/setwebhook?url=" . $_SERVER['SERVER_NAME'] . "" . $_SERVER['SCRIPT_NAME']);
function bot($method,$datas=[]){
$hhzZz = http_build_query($datas);
$url = "https://api.telegram.org/bot".API_KEY."/".$method."?$hhzZz";
$vhhhhh = file_get_contents($url);
 return json_decode($vhhhhh);
}
$update = json_decode(file_get_contents('php://input'));
$message = $update->message;
$chat_id = $message->chat->id;
$text = $message->text;
$admin = 1337821105; # ايديك
$chat_id2 = $update->callback_query->message->chat->id;
$message_id2 = $update->callback_query->message->message_id;
$data = $update->callback_query->data;
$name = $message->from->first_name;
$user = $message->from->username;
$from_id = $message->from->id;
$tws = file_get_contents("tw.txt");
$message = $update->message;
$chat_id = $message->chat->id;
$text = $message->text;
$chat_id2 = $update->callback_query->message->chat->id;
$message = $update->message;
$chat_id = $message->chat->id;
$message_id2 = $update->callback_query->message->message_id;
$data = $update->callback_query->data;
$from_id = $message->from->id;
$fromid= $update->callback_query->from->id;
$data_name = $update->callback_query->from->first_name;
$datatag_name = "[$data_name](tg://user?id=$fromid";
$name = $update->message->from->first_name;
$from_id = $message->from->id;
$u = explode("\n",file_get_contents("memb.txt"));
$c = count($u)-1;
$modxe = file_get_contents("usr.txt");
$username = $update->message->from->username;
$reply = $message->reply_to_message->message_id;
$list = file_get_contents("blocklist.txt");
$rep = $message->reply_to_message->forward_from; 
$id = $rep->id; 
$K5 = file_get_contents("k.txt");
$K6 = file_get_contents("k1.txt");
$message = $update->message;
$chat_id = $message->chat->id;
$textmsg = $message->text;
$user = $message->from->username;
$name = $message->from->first_name;
$for = $message->from->id;
$text = $message->text;
$chat_id2 = $update->callback_query->message->chat->id;
$message = $update->message;
$chat_id = $message->chat->id;
$message_id2 = $update->callback_query->message->message_id;
$data = $update->callback_query->data;
$from_id = $message->from->id;
$name = $update->message->from->first_name;
$from_id = $message->from->id;
$k5 = file_get_contents("data/k5.txt");
$k6 = file_get_contents("data/k6.txt");
$k7 = file_get_contents("data/k7.txt");
$k99 = file_get_contents("data/k99.txt");
$admin2 = file_get_contents("admin2.txt");
$ad = array("$admin","$admin2");
$list = file_get_contents("blocklist.txt");
$ebu = explode("\n",$list);
if(in_array($from_id,$ebu)){
 bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"⛳| عزيزي انت محظور من البوت",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
]);
}
$rembo = $message->from->id;
$from_id = $message->from->id;
$from_id = $message->from->id;
mkdir("alsh");
if(isset($message)){
$al = file_get_contents('memb.txt');
$alo = explode("\n",$al);
if(!in_array($from_id,$alo)){
$alsh2 = fopen("memb.txt", "a") or die("Unable to open file!");
fwrite($alsh2, "$from_id\n");
fclose($alsh2);}}
$first_name = $message->from->first_name;
$username = $message->from->username;
$from_id = $message->from->id;
$marcus = explode("\n",file_get_contents("memb.txt"));
$hassan = count($marcus)-1;
if ($message && !in_array($from_id, $marcus)) {
file_put_contents("memb.txt", $from_id."\n",FILE_APPEND);
}
if($data == "at" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
𝟏 𝟐 𝟑 𝟒 𝟓 𝟔 𝟕 𝟖 𝟗 𝟎
 🇺🇸 ✞ 
ッ ッ 彡 Ω ۞ ۩ ✟
 『』 Ξ 道 凸 父 
个 ¤ 品 〠 ๛ 𖤍 
ᶠᶸᶜᵏᵧₒᵤ ࿐ ⍆ ⍅ 
⇭ ༒   𖠃 
𖠅 𖠆 𖠊 𖡒 𖡗 
𖣩 ꧁ ꧂
〰 𖥓 𖥏 𖥎 
𖥌 𖥋 𖥊 𖥈 
𖥅 𖥃 𖥂 
𖥀 𖤼 𖤹
 𖤸 𖤷 
𖤶 
𖤭 𖤫 
𖤪 𖤨 𖤧 
𖤥 𖤤 𖤣 𖤢 𖤡
 𖤟 𖤞 𖤝 𖤜 𖤛 𖤚 
𖤘 𖤙 𖤗 𖤕 𖤓 𖤒 𖤐 
ဏ ࿘ ࿗ ࿖ ࿕ ࿑ ࿌ ࿋ ࿊ 
࿉ ࿈ ࿇ ࿅ ࿄ ࿃ ࿂ ༼ ༽ ༺ ༻
༗ ༖ ༕ ⏝ ⏜ ⏎ ၄ ߷ ܛ ׀𖠀 
𖠁 𖠂 𖠅 𖠆 𖠇 𖠈 𖠉 𖠍 𖠎 𖠏 𖠐 
𖠑 𖠒 𖠓 𖠔 𖠕 𖠖 𖠗 𖠘 𖠙 
𖠚 𖠛 𖠜 𖠝 𖠞 𖠟 𖠠
 𖠡 𖠢 𖠣 𖠤 𖠥 
𖠦 𖠧 𖠨 ??
 𖠪 𖠫 𖠬 𖠭 
𖠮 𖠯 𖠰 
𖠱 𖠲 
𖠳 
𖠴 𖠵 𖠶 
𖠷 𖠸 𖠹 𖠺
 𖠻 𖠼 𖠽 𖠾 𖠿
 𖡀 𖡁 𖡂 𖡃 𖡄
 𖡅 𖡆 𖡇 𖡈 𖡉 𖡊 𖡋 
𖡌 𖡍 𖡎 𖡏 𖡐 𖡑 𖡒 𖡓 𖡔 
𖡕 𖡖 𖡗 𖡘 𖡙 𖡚 𖡛 𖡜 𖡝 
𖡞 𖡟 𖡠 𖡡 𖡢 𖡣 𖡤 𖡥 𖡦 𖡧 𖡨 
𖡩 𖡪 𖡫 𖡬 𖡭 𖡮 𖡯 𖡰 𖡱 𖡲 𖡳 𖡴 𖡵 𖡶
 𖡷 𖡸 𖡹 𖡺 𖡻 𖡼 𖡽 𖡾 𖡿 𖢀 𖢁 𖢂 𖢃 𖢄 𖢅 𖢆 
𖢇 ?? 𖢉 𖢊 𖢋 𖢌 𖢍 𖢎 𖢏 𖢐 𖢑 𖢒 𖢓 𖢔
 𖢕 𖢖 𖢗 𖢘 𖢙 𖢚 𖢛 𖢜 𖢝 𖢞 𖢟 𖢠 
𖢡 𖢢 𖢣 𖢤 𖢥 𖢦 𖢧 𖢨 𖢩 𖢪 𖢫 𖢬
 𖢭 𖢮 𖢯 𖢰 𖢱 𖢲 𖢳 𖢴 𖢵 𖢶 
𖢷 𖢸 𖢹 𖢺 𖢻 𖢼 𖢽 𖢾 
𖢿 𖣀 𖣁 𖣂 𖣃 𖣄 𖣅 
𖣆 𖣇 𖣈 𖣉 𖣊 
𖣋 𖣌 𖣍 𖣎 𖣏
 𖣐 𖣑 𖣒 
𖣓 𖣔 
𖣕 
𖣖 𖣗 
𖣘 𖣙 𖣚 𖣛 𖣜
 𖣝 𖣞 𖣟 𖣠 𖣡 𖣢 
𖣣 𖣤 𖣥 𖣦 𖣧 𖣨 𖣩 𖣪 
𖣫 𖣬 𖣭 𖣮 𖣯 𖣰 𖣱 𖣲 𖣳 
𖣴 𖣵 𖣶 𖣷 𖣸 𖣹 𖣺 𖣻 𖣼 𖣽 𖣾 𖣿
☽︎☾︎➪︎㋛︎✔︎𑁍︎𓆉︎☏︎☻︎ᴥ︎𓁹︎𓂀︎ꨄ︎
᪥︎✯︎߷︎༆︎༄︎Ꙭ︎⁂︎⌘︎᯾︎❁︎✰︎✫︎★︎
𐂃︎⚣︎𐂊︎␈︎𓄁︎𓃰︎𓆏︎𓅿︎𓀡︎
𓂺︎𓂸︎⌫︎✯︎⁂︎᯽︎
☼︎𓂉︎⚣︎𓀿︎𓀿︎𓃠︎
𓀡︎𐂊︎𓀬︎𓂻︎
𓃗︎♔︎♕︎
𓆏︎
",
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "home" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
• اهلا بك، $datatag_name

- في بوت الزخرفةالشامل؛)

- يمكنك الزخرفه اسمك باللغه الانكليزيه 🧸💕

- بطريقتين الاولى برموز تمبلر 💘🌈 

- والثانيه بدون رموز زخرفه فقط .🦄💘

- وايضا زخرفهاسمك باللغه العربيه 🧸💕

- و صنع بايو قناة تليجرام💕🧸

- و صنع بايو انستكرام🧸💕
-- -- -- -- - -- -- -- -- -- -- -- -- -- 

",
'parse_mode'=>"markdown",'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- عـربي . 🦄💸','callback_data'=>'ii'],['text'=>'- ENGLISH . 🦄💸','callback_data'=>'ww']],
 
[['text'=>'- زخرفه انكلش برموز تمبلر ! 🦄💸','callback_data'=>'eeen']],

[['text'=>'- بايـوأنسـتا . 🦄💸','callback_data'=>'mikbio'],['text'=>'- بايـو قناة تـلي . 🦄💸','callback_data'=>'mikbioch']],

[['text'=>'- أسم ببجـي . 🦄💸' ,'callback_data'=>"bupg"]],

[['text'=>'- أسـماء ججـاهزة . 🦄💸','callback_data'=>'asm'],['text'=>'- نبـذ ججـاهزة . 🦄💸','callback_data'=>'nb']],
]])
]); 
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}
$sta = file_get_contents("start.txt");
$all = file_get_contents("id.txt");
$rabt = file_get_contents("rabt.txt");
$join = file_get_contents("https://api.telegram.org/bot".API_KEY."/getChatMember?chat_id=$all&user_id=".$from_id);
if($message && (strpos($join,'"status":"left"') or strpos($join,'"Bad Request: USER_ID_INVALID"') or strpos($join,'"status":"kicked"'))!== false){
bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"
-عَليڪ ﺄلاشتراك بقناة ﺂلبوت الخاصة .💛.
لأستخدام البوت بشڪل صَحيح 💚.
اشترك ثم اضغط /start من جديد 💘.",
'reply_to_message_id'=>$message->message_id,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"- اضغط ۿنا للأشتراك",'url'=>"$rabt"]],
]])]);return false;}
#شتراك 
$op = file_get_contents("ch.txt");
$join = file_get_contents("https://api.telegram.org/bot".API_KEY."/getChatMember?chat_id=@$op&user_id=".$from_id);
if($message && (strpos($join,'"status":"left"') or strpos($join,'"Bad Request: USER_ID_INVALID"') or strpos($join,'"status":"kicked"'))!== false){
bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"- عَليڪ ﺄلاشتراك بقناة ﺂلبوت الاولى 💛.
لأستخدام البوت بشڪل صَحيح 💚.
اشترك ثم اضغط /start من جديد 💘. * @$op * ؛
",
'reply_to_message_id'=>$message->message_id,
]);return false;}
#شتراك اجباري2
$oop = file_get_contents("chc.txt");
$join = file_get_contents("https://api.telegram.org/bot".API_KEY."/getChatMember?chat_id=@$oop&user_id=".$from_id);
if($message && (strpos($join,'"status":"left"') or strpos($join,'"Bad Request: USER_ID_INVALID"') or strpos($join,'"status":"kicked"'))!== false){
bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"- عَليڪ ﺄلاشتراك بقناة ﺂلبوت الثانيه 💛.
لأستخدام البوت بشڪل صَحيح 💚.
اشترك ثم اضغط /start من جديد 💘.* @$oop * ؛",
'reply_to_message_id'=>$message->message_id,
]);return false;}
if($text == "/start" and !in_array($from_id,$ebu) and !in_array($from_id,$ebu) and !in_array($chat_id,$ad) and $sta == null){
mkdir("data");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
• اهلا بك، $name

- في بوت الزخرفةالشامل؛)

- يمكنك الزخرفه اسمك باللغه الانكليزيه 🧸💕

- بطريقتين الاولى برموز تمبلر 💘🌈 

- والثانيه بدون رموز زخرفه فقط .🦄💘

- وايضا زخرفهاسمك باللغه العربيه 🧸💕

- و صنع بايو قناة تليجرام💕🧸

- و صنع بايو انستكرام🧸💕
-- -- -- -- - -- -- -- -- -- -- -- -- -- 
",
'parse_mode'=>"markdown",'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- عـربي . 🦄💸','callback_data'=>'ii'],['text'=>'- ENGLISH . 🦄💸','callback_data'=>'ww']],
 
[['text'=>'- زخرفه انكلش برموز تمبلر ! 🦄💸','callback_data'=>'eeen']],

[['text'=>'- بايـوأنسـتا . 🦄💸','callback_data'=>'mikbio'],['text'=>'- بايـو قناة تـلي . 🦄💸','callback_data'=>'mikbioch']],

[['text'=>'- أسم ببجـي . 🦄💸' ,'callback_data'=>"bupg"]],

[['text'=>'- أسـماء ججـاهزة . 🦄💸','callback_data'=>'asm'],['text'=>'- نبـذ ججـاهزة . 🦄💸','callback_data'=>'nb']],
]
])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}
if($text == "/start" and !in_array($from_id,$ebu) and !in_array($from_id,$ebu) and !in_array($chat_id,$ad) and $sta != null){
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"$sta",
'parse_mode'=>"markdown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>'- عـربي . 🦄💸','callback_data'=>'ii'],['text'=>'- ENGLISH . 🦄💸','callback_data'=>'ww']],
 
[['text'=>'- زخرفه انكلش برموز تمبلر ! 🦄💸','callback_data'=>'eeen']],

[['text'=>'- بايـوأنسـتا . 🦄💸','callback_data'=>'mikbio'],['text'=>'- بايـو قناة تـلي . 🦄💸','callback_data'=>'mikbioch']],

[['text'=>'- أسم ببجـي . 🦄💸' ,'callback_data'=>"bupg"]],

[['text'=>'- أسـماء ججـاهزة . 🦄💸','callback_data'=>'asm'],['text'=>'- نبـذ ججـاهزة . 🦄💸','callback_data'=>'nb']],
]])
]);
}

if($data =="ww"){
bot('editmessagetext',[
'chat_id'=>$chat_id2, 
'message_id'=>$update->callback_query->message->message_id,
'text'=>'- حسنا قم بأرسال اسمك بلغة الانكليزية فقط !🦄💸',
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
file_put_contents("data/k5.txt","k5");
}
if($data == "ii" ){
file_put_contents("data/k6.txt","k6");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>'- حسنا قم بأرسال اسمك بلغة العربيةة فقط ! 🦄💸',
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
#زخرفه انكلش
if($text != "/start" and $k5 == "k5" and $chat_id !=$k6 and $chat_id != $k7 and $chat_id != $bio and $chat_id != $bioch and $chat_id != $bu and $chat_id != $k99){
file_put_contents("data/k5.txt","none");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"",
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '??' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
$MA1 = str_replace('a','ᵃ',$text);
$MA1 = str_replace('A','ᵃ',$MA1);
$MA1 = str_replace('b','ᵇ',$MA1);
$MA1 = str_replace('B','ᵇ',$MA1);
$MA1 = str_replace('c','ᶜ',$MA1);
$MA1 = str_replace('C','ᶜ',$MA1);
$MA1 = str_replace('d','ᵈ',$MA1);
$MA1 = str_replace('D','ᵈ',$MA1);
$MA1 = str_replace('e','ᵉ',$MA1);
$MA1 = str_replace('E','ᵉ',$MA1);
$MA1 = str_replace('f','ᶠ',$MA1);
$MA1 = str_replace('F','ᶠ',$MA1);
$MA1 = str_replace('g','ᵍ',$MA1);
$MA1 = str_replace('G','ᵍ',$MA1);
$MA1 = str_replace('h','ʰ',$MA1);
$MA1 = str_replace('H','ʰ',$MA1);
$MA1 = str_replace('i','ᶤ',$MA1);
$MA1 = str_replace('I','ᶤ',$MA1);
$MA1 = str_replace('j','ʲ',$MA1);
$MA1 = str_replace('J','ʲ',$MA1);
$MA1 = str_replace('k','ᵏ',$MA1);
$MA1 = str_replace('K','ᵏ',$MA1);
$MA1 = str_replace('l','ˡ',$MA1);
$MA1 = str_replace('L','ˡ',$MA1);
$MA1 = str_replace('m','ᵐ',$MA1);
$MA1 = str_replace('M','ᵐ',$MA1);
$MA1 = str_replace('n','ᶰ',$MA1);
$MA1 = str_replace('N','ᶰ',$MA1);
$MA1 = str_replace('o','ᵒ',$MA1);
$MA1 = str_replace('O','ᵒ',$MA1);
$MA1 = str_replace('p','ᵖ',$MA1);
$MA1 = str_replace('P','ᵖ',$MA1);
$MA1 = str_replace('q','ᵠ',$MA1);
$MA1 = str_replace('Q','ᵠ',$MA1);
$MA1 = str_replace('r','ʳ',$MA1);
$MA1 = str_replace('R','ʳ',$MA1);
$MA1 = str_replace('s','ˢ',$MA1);
$MA1 = str_replace('S','ˢ',$MA1);
$MA1 = str_replace('t','ᵗ',$MA1);
$MA1 = str_replace('T','ᵗ',$MA1);
$MA1 = str_replace('u','ᵘ',$MA1);
$MA1 = str_replace('U','ᵘ',$MA1);
$MA1 = str_replace('v','ᵛ',$MA1);
$MA1 = str_replace('V','ᵛ',$MA1);
$MA1 = str_replace('w','ʷ',$MA1);
$MA1 = str_replace('W','ʷ',$MA1);
$MA1 = str_replace('x','ˣ',$MA1);
$MA1 = str_replace('X','ˣ',$MA1);
$MA1 = str_replace('y','ʸ',$MA1);
$MA1 = str_replace('Y','ʸ',$MA1);
$MA1 = str_replace('z','ᶻ',$MA1);
$MA1 = str_replace('Z','ᶻ',$MA1);
bot('sendMessage',[
'chat_id'=>$chat_id, 
'text'=>'*'.$MA1.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA2 = str_replace('a', 'ᴀ', $text);
$MA2 = str_replace('b', 'ʙ', $MA2);
$MA2 = str_replace('c', 'ᴄ', $MA2);
$MA2 = str_replace('d', 'ᴅ', $MA2);
$MA2 = str_replace('e', 'ᴇ', $MA2);
$MA2 = str_replace('f', 'ғ', $MA2);
$MA2 = str_replace('g', 'ɢ', $MA2);
$MA2 = str_replace('h', 'ʜ', $MA2);
$MA2 = str_replace('i', 'ɪ', $MA2);
$MA2 = str_replace('j', 'ᴊ', $MA2);
$MA2 = str_replace('k', 'ᴋ', $MA2);
$MA2 = str_replace('l', 'ʟ', $MA2);
$MA2 = str_replace('m', 'ᴍ', $MA2);
$MA2 = str_replace('n', 'ɴ', $MA2);
$MA2 = str_replace('o', 'ᴏ', $MA2);
$MA2 = str_replace('p', 'ᴘ', $MA2);
$MA2 = str_replace('q', 'ǫ', $MA2);
$MA2 = str_replace('r', 'ʀ', $MA2);
$MA2 = str_replace('s', 's', $MA2);
$MA2 = str_replace('t', 'ᴛ', $MA2);
$MA2 = str_replace('u', 'ᴜ', $MA2);
$MA2 = str_replace('v', 'ᴠ', $MA2);
$MA2 = str_replace('w', 'ᴡ', $MA2);
$MA2 = str_replace('x', 'x', $MA2);
$MA2 = str_replace('y', 'ʏ', $MA2);
$MA2 = str_replace('z', 'ᴢ', $MA2);
bot('sendMessage',[
'chat_id'=>$chat_id, 
'text'=>'*'.$MA2.' '.$smile.'*',
'parse_mode'=>'MArkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
$MA3 = str_replace('a','α',$text);
$MA3 = str_replace("b","в",$MA3);
$MA3 = str_replace("c","c",$MA3);
$MA3 = str_replace("d","∂",$MA3);
$MA3 = str_replace("e","ε",$MA3);
$MA3 = str_replace("E","ғ",$MA3);
$MA3 = str_replace("g","g",$MA3);
$MA3 = str_replace("h","н",$MA3);
$MA3 = str_replace("i","ι",$MA3);
$MA3 = str_replace("j","נ",$MA3);
$MA3 = str_replace("k","к",$MA3);
$MA3 = str_replace("l","ℓ",$MA3);
$MA3 = str_replace("m","м",$MA3);
$MA3 = str_replace("n","η",$MA3);
$MA3 = str_replace("o","σ",$MA3);
$MA3 = str_replace("p","ρ",$MA3);
$MA3 = str_replace("q","q",$MA3);
$MA3 = str_replace("r","я",$MA3);
$MA3 = str_replace("s","s",$MA3);
$MA3 = str_replace("t","т",$MA3);
$MA3 = str_replace("u","υ",$MA3);
$MA3 = str_replace("v","v",$MA3);
$MA3 = str_replace("w","ω",$MA3);
$MA3 = str_replace("x","x",$MA3);
$MA3 = str_replace("y","ү",$MA3);
$MA3 = str_replace("z","z",$MA3);
bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>'*'.$MA3.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA4 = str_replace('a','𝙰',$text); 
 $MA4 = str_replace('b','𝙱',$MA4); 
 $MA4 = str_replace('c','𝙲',$MA4); 
 $MA4 = str_replace('d','𝙳',$MA4); 
 $MA4 = str_replace('e','𝙴',$MA4); 
 $MA4 = str_replace('f','𝙵',$MA4); 
 $MA4 = str_replace('g','𝙶',$MA4); 
 $MA4 = str_replace('h','𝙷',$MA4); 
 $MA4 = str_replace('i','𝙸',$MA4); 
 $MA4 = str_replace('j','𝚓',$MA4); 
 $MA4 = str_replace('k','𝙺',$MA4); 
 $MA4 = str_replace('l','𝙻',$MA4); 
 $MA4 = str_replace('m','𝙼',$MA4); 
 $MA4 = str_replace('n','𝙽',$MA4); 
 $MA4 = str_replace('o','𝙾',$MA4); 
 $MA4 = str_replace('p','𝙿',$MA4); 
 $MA4 = str_replace('q','𝚀',$MA4); 
 $MA4 = str_replace('r','𝚁',$MA4); 
 $MA4 = str_replace('s','𝚂',$MA4); 
 $MA4 = str_replace('t','𝚃',$MA4); 
 $MA4 = str_replace('u','𝚄',$MA4); 
 $MA4 = str_replace('v','𝚅',$MA4); 
 $MA4 = str_replace('w','𝚆',$MA4); 
 $MA4 = str_replace('x','𝚇',$MA4); 
 $MA4 = str_replace('y','𝚈',$MA4); 
 $MA4 = str_replace('z','𝚉',$MA4);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$MA4.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA5 = str_replace('a','𝘢',$text); 
 $MA5 = str_replace('b','𝘣',$MA5); 
 $MA5 = str_replace('c','𝘤',$MA5); 
 $MA5 = str_replace('d','𝘥',$MA5); 
 $MA5 = str_replace('e','𝘦',$MA5); 
 $MA5 = str_replace('f','𝘧',$MA5); 
 $MA5 = str_replace('g','𝘨',$MA5); 
 $MA5 = str_replace('h','𝘩',$MA5); 
 $MA5 = str_replace('i','𝘪',$MA5); 
 $MA5 = str_replace('j','𝘫',$MA5); 
 $MA5 = str_replace('k','𝘬',$MA5); 
 $MA5 = str_replace('l','𝘭',$MA5); 
 $MA5 = str_replace('m','𝘮',$MA5); 
 $MA5 = str_replace('n','𝘯',$MA5); 
 $MA5 = str_replace('o','𝘰',$MA5); 
 $MA5 = str_replace('p','𝘱',$MA5); 
 $MA5 = str_replace('q','𝘲',$MA5); 
 $MA5 = str_replace('r','𝘳',$MA5); 
 $MA5 = str_replace('s','𝘴',$MA5); 
 $MA5 = str_replace('t','𝘵',$MA5); 
 $MA5 = str_replace('u','𝘶',$MA5); 
 $MA5 = str_replace('v','𝘷',$MA5); 
 $MA5 = str_replace('w','𝘸',$MA5); 
 $MA5 = str_replace('x','𝘹',$MA5); 
 $MA5 = str_replace('y','𝘺',$MA5); 
 $MA5 = str_replace('z','𝘻',$MA5);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$MA5.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA6 = str_replace('a','𝖆',$text); 
 $MA6 = str_replace('b','𝖉',$MA6); 
 $MA6 = str_replace('c','𝖈',$MA6); 
 $MA6 = str_replace('d','𝖉',$MA6); 
 $MA6 = str_replace('e','𝖊',$MA6); 
 $MA6 = str_replace('f','𝖋',$MA6); 
 $MA6 = str_replace('g','𝖌',$MA6); 
 $MA6 = str_replace('h','𝖍',$MA6); 
 $MA6 = str_replace('i','𝖎',$MA6); 
 $MA6 = str_replace('j','𝖏',$MA6); 
 $MA6 = str_replace('k','𝖐',$MA6); 
 $MA6 = str_replace('l','𝖗',$MA6); 
 $MA6 = str_replace('m','𝖒',$MA6); 
 $MA6 = str_replace('n','𝖓',$MA6); 
 $MA6 = str_replace('o','𝖔',$MA6); 
 $MA6 = str_replace('p','𝖕',$MA6); 
 $MA6 = str_replace('q','𝖖',$MA6); 
 $MA6 = str_replace('r','𝖗',$MA6); 
 $MA6 = str_replace('s','𝖘',$MA6); 
 $MA6 = str_replace('t','𝖙',$MA6); 
 $MA6 = str_replace('u','𝖚',$MA6); 
 $MA6 = str_replace('v','𝒗',$MA6); 
 $MA6 = str_replace('w','𝒘',$MA6); 
 $MA6 = str_replace('x','𝖝',$MA6); 
 $MA6 = str_replace('y','𝒚',$MA6); 
 $MA6 = str_replace('z','𝒛',$MA6);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$MA6.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);

$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA7 = str_replace('a','ꪖ',$text); 
 $MA7 = str_replace('b','᥇',$MA7); 
 $MA7 = str_replace('c','ᥴ',$MA7); 
 $MA7 = str_replace('d','ᦔ',$MA7); 
 $MA7 = str_replace('e','ꫀ',$MA7); 
 $MA7 = str_replace('f','ᠻ',$MA7); 
 $MA7 = str_replace('g','ᧁ',$MA7); 
 $MA7 = str_replace('h','ꫝ',$MA7); 
 $MA7 = str_replace('i','𝓲',$MA7); 
 $MA7 = str_replace('j','𝓳',$MA7); 
 $MA7 = str_replace('k','𝘬',$MA7); 
 $MA7 = str_replace('l','ꪶ',$MA7); 
 $MA7 = str_replace('m','ꪑ',$MA7); 
 $MA7 = str_replace('n','ꪀ',$MA7); 
 $MA7 = str_replace('o','ꪮ',$MA7); 
 $MA7 = str_replace('p','ρ',$MA7); 
 $MA7 = str_replace('q','𝘲',$MA7); 
 $MA7 = str_replace('r','𝘳',$MA7); 
 $MA7 = str_replace('s','𝘴',$MA7); 
 $MA7 = str_replace('t','𝓽',$MA7); 
 $MA7 = str_replace('u','ꪊ',$MA7); 
 $MA7 = str_replace('v','ꪜ',$MA7); 
 $MA7 = str_replace('w','᭙',$MA7); 
 $MA7 = str_replace('x','᥊',$MA7); 
 $MA7 = str_replace('y','ꪗ',$MA7); 
 $MA7 = str_replace('z','ɀ',$MA7);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$MA7.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);

$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA8 = str_replace('a','a͜͡',$text); 
 $MA8 = str_replace('b','b͜͡',$MA8); 
 $MA8 = str_replace('c','c͜͡',$MA8); 
 $MA8 = str_replace('d','d͜͡',$MA8); 
 $MA8 = str_replace('e','e͜͡',$MA8); 
 $MA8 = str_replace('f','f͜͡',$MA8); 
 $MA8 = str_replace('g','g͜͡',$MA8); 
 $MA8 = str_replace('h','h͜͡',$MA8); 
 $MA8 = str_replace('i','i͜͡',$MA8); 
 $MA8 = str_replace('j','j͜͡',$MA8); 
 $MA8 = str_replace('k','k͜͡',$MA8); 
 $MA8 = str_replace('l','l͜͡',$MA8); 
 $MA8 = str_replace('m','m͜͡',$MA8); 
 $MA8 = str_replace('n','n͜͡',$MA8); 
 $MA8 = str_replace('o','o͜͡',$MA8); 
 $MA8 = str_replace('p','p͜͡',$MA8); 
 $MA8 = str_replace('q','q͜͡',$MA8); 
 $MA8 = str_replace('r','r͜͡',$MA8); 
 $MA8 = str_replace('s','s͜͡',$MA8); 
 $MA8 = str_replace('t','t͜͡',$MA8); 
 $MA8 = str_replace('u','u͜͡',$MA8); 
 $MA8 = str_replace('v','v͜͡',$MA8); 
 $MA8 = str_replace('w','w͜͡',$MA8); 
 $MA8 = str_replace('x','d͜͡',$MA8); 
 $MA8 = str_replace('y','y͜͡',$MA8); 
 $MA8 = str_replace('z','z͜͡',$MA8);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$MA8.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA9 = str_replace('a','𝖆',$text); 
 $MA9 = str_replace('b','𝖇',$MA9); 
 $MA9 = str_replace('c','𝖈',$MA9); 
 $MA9 = str_replace('d','𝖉',$MA9); 
 $MA9 = str_replace('e','𝖊',$MA9); 
 $MA9 = str_replace('f','𝖋',$MA9); 
 $MA9 = str_replace('g','𝖌',$MA9); 
 $MA9 = str_replace('h','𝖍',$MA9); 
 $MA9 = str_replace('i','𝖎',$MA9); 
 $MA9 = str_replace('j','𝖏',$MA9); 
 $MA9 = str_replace('k','𝖐',$MA9); 
 $MA9 = str_replace('l','𝖑',$MA9); 
 $MA9 = str_replace('m','𝖒',$MA9); 
 $MA9 = str_replace('n','𝖓',$MA9); 
 $MA9 = str_replace('o','𝖔',$MA9); 
 $MA9 = str_replace('p','𝖕',$MA9); 
 $MA9 = str_replace('q','𝖖',$MA9); 
 $MA9 = str_replace('r','𝖗',$MA9); 
 $MA9 = str_replace('s','𝖘',$MA9); 
 $MA9 = str_replace('t','𝖙',$MA9); 
 $MA9 = str_replace('u','𝖚',$MA9); 
 $MA9 = str_replace('v','𝖛',$MA9); 
 $MA9 = str_replace('w','𝖜',$MA9); 
 $MA9 = str_replace('x','𝖝',$MA9); 
 $MA9 = str_replace('y','𝖞',$MA9); 
 $MA9 = str_replace('z','𝖟',$MA9);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$MA9.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA10 = str_replace('a','𝔸',$text);
$MA10 = str_replace("b","𝔹",$MA10);
$MA10 = str_replace("c","ℂ",$MA10);
$MA10 = str_replace("d","𝔻",$MA10);
$MA10 = str_replace("e","𝔼",$MA10);
$MA10 = str_replace("E","𝔽",$MA10);
$MA10 = str_replace("g","𝔾",$MA10);
$MA10 = str_replace("h","ℍ",$MA10);
$MA10 = str_replace("i","𝕀",$MA10);
$MA10 = str_replace("j","𝕁",$MA10);
$MA10 = str_replace("k","𝕂",$MA10);
$MA10 = str_replace("l","𝕃",$MA10);
$MA10 = str_replace("m","𝕄",$MA10);
$MA10 = str_replace("n","ℕ",$MA10);
$MA10 = str_replace("o","𝕆",$MA10);
$MA10 = str_replace("p","ℙ",$MA10);
$MA10 = str_replace("q","ℚ",$MA10);
$MA10 = str_replace("r","ℝ",$MA10);
$MA10 = str_replace("s","𝕊",$MA10);
$MA10 = str_replace("t","𝕋",$MA10);
$MA10 = str_replace("u","𝕌",$MA10);
$MA10 = str_replace("v","𝕍",$MA10);
$MA10 = str_replace("w","𝕎",$MA10);
$MA10 = str_replace("x","𝕏",$MA10);
$MA10 = str_replace("y","Ý",$MA10);
$MA10 = str_replace("z","ℤ",$MA10);
 bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.$MA10.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA11 = str_replace('a','𝐀',$text);
$MA11 = str_replace("b","𝐁",$MA11);
$MA11 = str_replace("c","𝐂",$MA11);
$MA11 = str_replace("d","𝐃",$MA11);
$MA11 = str_replace("e","𝐄",$MA11);
$MA11 = str_replace("E","𝐅",$MA11);
$MA11 = str_replace("g","𝐆",$MA11);
$MA11 = str_replace("h","𝐇",$MA11);
$MA11 = str_replace("i","𝐈",$MA11);
$MA11 = str_replace("j","𝐉",$MA11);
$MA11 = str_replace("k","𝐊",$MA11);
$MA11 = str_replace("l","𝑳",$MA11);
$MA11 = str_replace("m","𝐌",$MA11);
$MA11 = str_replace("n","𝐍",$MA11);
$MA11 = str_replace("o","𝐎",$MA11);
$MA11 = str_replace("p","𝐏",$MA11);
$MA11 = str_replace("q","𝐐",$MA11);
$MA11 = str_replace("r","𝐑",$MA11);
$MA11 = str_replace("s","𝐒",$MA11);
$MA11 = str_replace("t","𝐓",$MA11);
$MA11 = str_replace("u","𝐔",$MA11);
$MA11 = str_replace("v","𝐕",$MA11);
$MA11 = str_replace("w","𝐖",$MA11);
$MA11 = str_replace("x","𝐗",$MA11);
$MA11 = str_replace("y","𝐘",$MA11);
$MA11 = str_replace("z","𝐙",$MA11);
 bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.$MA11.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA13 = str_replace('a','𝗔',$text);
$MA13 = str_replace("b","𝗕",$MA13);
$MA13 = str_replace("c","𝗖",$MA13);
$MA13 = str_replace("d","𝗗",$MA13);
$MA13 = str_replace("e","𝗘",$MA13);
$MA13 = str_replace("E","𝗙",$MA13);
$MA13 = str_replace("g","𝗚",$MA13);
$MA13 = str_replace("h","𝗛",$MA13);
$MA13 = str_replace("i","𝗜",$MA13);
$MA13 = str_replace("j","𝗝",$MA13);
$MA13 = str_replace("k","𝗞",$MA13);
$MA13 = str_replace("l","𝗟",$MA13);
$MA13 = str_replace("m","𝗠",$MA13);
$MA13 = str_replace("n","𝗡",$MA13);
$MA13 = str_replace("o","𝗢",$MA13);
$MA13 = str_replace("p","𝗣",$MA13);
$MA13 = str_replace("q","𝗤",$MA13);
$MA13 = str_replace("r","𝗥",$MA13);
$MA13 = str_replace("s","𝗦",$MA13);
$MA13 = str_replace("t","𝗧",$MA13);
$MA13 = str_replace("u","𝗨",$MA13);
$MA13 = str_replace("v","𝗩",$MA13);
$MA13 = str_replace("w","𝗪",$MA13);
$MA13 = str_replace("x","𝗫",$MA13);
$MA13 = str_replace("y","𝗬",$MA13);
$MA13 = str_replace("z","𝗔",$MA13);
 bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.$MA13.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$MA14 = str_replace('a','𝘼',$text);
$MA14 = str_replace("b","𝘽",$MA14);
$MA14 = str_replace("c","𝘾",$MA14);
$MA14 = str_replace("d","𝘿",$MA14);
$MA14 = str_replace("e","𝙀",$MA14);
$MA14 = str_replace("E","𝙁",$MA14);
$MA14 = str_replace("g","𝙂",$MA14);
$MA14 = str_replace("h","𝙃",$MA14);
$MA14 = str_replace("i","𝙄",$MA14);
$MA14 = str_replace("j","𝙅",$MA14);
$MA14 = str_replace("k","𝙆",$MA14);
$MA14 = str_replace("l","𝙇",$MA14);
$MA14 = str_replace("m","𝙈",$MA14);
$MA14 = str_replace("n","𝙉",$MA14);
$MA14 = str_replace("o","𝙊",$MA14);
$MA14 = str_replace("p","𝙋",$MA14);
$MA14 = str_replace("q","𝙌",$MA14);
$MA14 = str_replace("r","𝙍",$MA14);
$MA14 = str_replace("s","𝙎",$MA14);
$MA14 = str_replace("t","𝙏",$MA14);
$MA14 = str_replace("u","𝙐",$MA14);
$MA14 = str_replace("v","𝙑",$MA14);
$MA14 = str_replace("w","𝙒",$MA14);
$MA14 = str_replace("x","𝙓",$MA14);
$MA14 = str_replace("y","𝙔",$MA14);
$MA14 = str_replace("z","𝙕",$MA14);
 bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.$MA14.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
 bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"
- تم زخرفة الاسم $text . 🦄💸
- ويمكنك رؤية الرموز ايضاً بالضغط على رموز.🦄💸
- يرجى الضغط على زر عوده في الاسفل . 🦄💸"
,'parse_mode'=>"markdown",'disable_web_page_preview'=>true,'reply_markup'=>json_encode(['inline_keyboard'=>[
[['text'=>'- زخرفة مرة اخرى ! 🦄💸' ,'callback_data'=>"ww"],['text'=>'- ألرمـوز . 🦄💸' ,'callback_data'=>"at"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}

if($data == "at"){
bot('editMessageText',[
 'chat_id'=>$chat_id2,
 'message_id'=>$message_id,
'text'=>"
𝟏 𝟐 𝟑 𝟒 𝟓 𝟔 𝟕 𝟖 𝟗 𝟎
 🇺🇸 ✞ 
ッ ッ 彡 Ω ۞ ۩ ✟
 『』 Ξ 道 凸 父 
个 ¤ 品 〠 ๛ 𖤍 
ᶠᶸᶜᵏᵧₒᵤ ࿐ ⍆ ⍅ 
⇭ ༒   𖠃 
𖠅 𖠆 𖠊 𖡒 𖡗 
𖣩 ꧁ ꧂
〰 𖥓 𖥏 𖥎 
𖥌 𖥋 𖥊 𖥈 
𖥅 𖥃 𖥂 
𖥀 𖤼 𖤹
 𖤸 𖤷 
𖤶 
𖤭 𖤫 
𖤪 𖤨 𖤧 
𖤥 𖤤 𖤣 𖤢 𖤡
 𖤟 𖤞 𖤝 𖤜 𖤛 𖤚 
𖤘 𖤙 𖤗 𖤕 𖤓 𖤒 𖤐 
ဏ ࿘ ࿗ ࿖ ࿕ ࿑ ࿌ ࿋ ࿊ 
࿉ ࿈ ࿇ ࿅ ࿄ ࿃ ࿂ ༼ ༽ ༺ ༻
༗ ༖ ༕ ⏝ ⏜ ⏎ ၄ ߷ ܛ ׀𖠀 
𖠁 𖠂 𖠅 𖠆 𖠇 𖠈 𖠉 𖠍 𖠎 𖠏 𖠐 
𖠑 𖠒 𖠓 𖠔 𖠕 𖠖 𖠗 𖠘 𖠙 
𖠚 𖠛 𖠜 𖠝 𖠞 𖠟 𖠠
 𖠡 𖠢 𖠣 𖠤 𖠥 
𖠦 𖠧 𖠨 𖠩
 𖠪 𖠫 𖠬 𖠭 
𖠮 𖠯 𖠰 
𖠱 𖠲 
𖠳 
𖠴 𖠵 𖠶 
𖠷 𖠸 𖠹 𖠺
 𖠻 𖠼 𖠽 𖠾 𖠿
 𖡀 𖡁 𖡂 𖡃 𖡄
 𖡅 𖡆 𖡇 𖡈 𖡉 𖡊 𖡋 
𖡌 𖡍 𖡎 𖡏 𖡐 𖡑 𖡒 𖡓 𖡔 
𖡕 𖡖 𖡗 𖡘 𖡙 𖡚 𖡛 𖡜 𖡝 
𖡞 𖡟 𖡠 𖡡 𖡢 𖡣 𖡤 𖡥 𖡦 𖡧 𖡨 
𖡩 𖡪 𖡫 𖡬 𖡭 𖡮 𖡯 𖡰 𖡱 𖡲 𖡳 𖡴 𖡵 𖡶
 𖡷 𖡸 𖡹 𖡺 𖡻 𖡼 𖡽 𖡾 𖡿 𖢀 𖢁 𖢂 𖢃 𖢄 𖢅 𖢆 
𖢇 𖢈 𖢉 𖢊 𖢋 𖢌 𖢍 𖢎 𖢏 𖢐 𖢑 𖢒 𖢓 𖢔
 𖢕 𖢖 𖢗 𖢘 𖢙 𖢚 𖢛 𖢜 𖢝 𖢞 𖢟 𖢠 
𖢡 𖢢 𖢣 𖢤 𖢥 𖢦 𖢧 𖢨 𖢩 𖢪 𖢫 𖢬
 𖢭 𖢮 𖢯 𖢰 𖢱 𖢲 𖢳 𖢴 𖢵 𖢶 
𖢷 𖢸 𖢹 𖢺 𖢻 𖢼 𖢽 𖢾 
𖢿 𖣀 𖣁 𖣂 𖣃 𖣄 𖣅 
𖣆 𖣇 𖣈 𖣉 𖣊 
𖣋 𖣌 𖣍 𖣎 𖣏
 𖣐 𖣑 𖣒 
𖣓 𖣔 
𖣕 
𖣖 𖣗 
𖣘 𖣙 𖣚 𖣛 𖣜
 𖣝 𖣞 𖣟 𖣠 𖣡 𖣢 
𖣣 𖣤 𖣥 𖣦 𖣧 𖣨 𖣩 𖣪 
𖣫 𖣬 𖣭 𖣮 𖣯 𖣰 𖣱 𖣲 𖣳 
𖣴 𖣵 𖣶 𖣷 𖣸 𖣹 𖣺 𖣻 𖣼 𖣽 𖣾 𖣿
☽︎☾︎➪︎㋛︎✔︎𑁍︎𓆉︎☏︎☻︎ᴥ︎𓁹︎𓂀︎ꨄ︎
᪥︎✯︎߷︎༆︎༄︎Ꙭ︎⁂︎⌘︎᯾︎❁︎✰︎✫︎★︎
𐂃︎⚣︎𐂊︎␈︎𓄁︎𓃰︎𓆏︎𓅿︎𓀡︎
𓂺︎𓂸︎⌫︎✯︎⁂︎᯽︎
☼︎𓂉︎⚣︎𓀿︎𓀿︎𓃠︎
𓀡︎𐂊︎𓀬︎𓂻︎
𓃗︎♔︎♕︎
𓆏︎
 ",'reply_markup'=>json_encode([ 
'inline_keyboard'=>[
[['text'=>'🔙' ,'callback_data'=>"home"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}

#زخرفه عربي
if($text != "/start"and$k6 == "k6" and $chat_id !=$k99 and $chat_id != $k7 and $chat_id != $bio and $chat_id != $bioch and $chat_id != $bu and $chat_id != $k5){
file_put_contents("data/k6.txt","none");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"",
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
 $marcus = str_replace('ض', 'ضِٰـِۢ', $text);
 $marcus = str_replace('ص', 'صِٰـِۢ', $marcus);
 $marcus = str_replace('ث', 'ثِٰـِۢ', $marcus);
 $marcus = str_replace('ق', 'قِٰـِۢ', $marcus);
 $marcus = str_replace('ف', 'فِٰ͒ـِۢ', $marcus);
 $marcus = str_replace('غ', 'غِٰـِۢ', $marcus);
 $marcus = str_replace('ع', 'عِٰـِۢ', $marcus);
 $marcus = str_replace('خ', 'خِٰ̐ـِۢ', $marcus);
 $marcus = str_replace('ح', 'حِٰـِۢ', $marcus);
 $marcus = str_replace('ج', 'جِٰـِۢ', $marcus);
 $marcus = str_replace('ش', 'شِٰـِۢ', $marcus);
 $marcus = str_replace('س', 'سِٰـِۢ', $marcus);
 $marcus = str_replace('ي', 'يِٰـِۢ', $marcus);
 $marcus = str_replace('ب', 'بِٰـِۢ', $marcus);
 $marcus = str_replace('ل', 'لِٰـِۢ', $marcus);
 $marcus = str_replace('ا', 'آ', $marcus);
 $marcus = str_replace('ت', 'تِٰـِۢ', $marcus);
 $marcus = str_replace('ن', 'نََ', $marcus);
 $marcus = str_replace('م', 'مِٰـِۢ', $marcus);
 $marcus = str_replace('ك', 'ڪِٰـِۢ', $marcus);
 $marcus = str_replace('ط', 'طِٰـِۢ', $marcus);
 $marcus = str_replace('ظ', 'ظِٰـِۢ', $marcus);
 $marcus = str_replace('ء', 'ء', $marcus);
 $marcus = str_replace('ؤ', 'ؤ', $marcus);
 $marcus = str_replace('ر', 'ر', $marcus);
 $marcus = str_replace('ى', 'ى', $marcus);
 $marcus = str_replace('ز', 'ز', $marcus);
 $marcus = str_replace('و', 'ﯛ̲୭', $marcus);
 $marcus = str_replace("ه", "ۿۿہ", $marcus);
 bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
 $marcus = str_replace('ض', 'ﺿ', $text);
 $marcus = str_replace('ص', 'ﺻ', $marcus);
 $marcus = str_replace('ث', 'ﺚ', $marcus);
 $marcus = str_replace('ق', 'ﭱ', $marcus);
 $marcus = str_replace('ف', 'ﭫ', $marcus);
 $marcus = str_replace('غ', 'ڠ', $marcus);
 $marcus = str_replace('؏', 'ع', $marcus);
 $marcus = str_replace('خ', 'ݗ', $marcus);
 $marcus = str_replace('ح', 'حُ', $marcus);
 $marcus = str_replace('ج', 'ݘ', $marcus);
 $marcus = str_replace('ش', 'ﺸ', $marcus);
 $marcus = str_replace('س', 'ﺴ', $marcus);
 $marcus = str_replace('ي', 'ﯥ', $marcus);
 $marcus = str_replace('ب', 'ﭘ', $marcus);
 $marcus = str_replace('ل', 'ڸ', $marcus);
 $marcus = str_replace('ا', 'آ', $marcus);
 $marcus = str_replace('ت', 'ٿ', $marcus);
 $marcus = str_replace('ن', 'ﮡ', $marcus);
 $marcus = str_replace('م', 'ﻢ', $marcus);
 $marcus = str_replace('ك', 'ﮗ', $marcus);
 $marcus = str_replace('ظ', 'ظ', $marcus);
 $marcus = str_replace('ظ', 'ظ', $marcus);
 $marcus = str_replace('ء', 'ء', $marcus);
 $marcus = str_replace('ؤ', 'ؤ', $marcus);
 $marcus = str_replace('ر', 'ر', $marcus);
 $marcus = str_replace('ى', 'ى', $marcus);
 $marcus = str_replace('ز', 'ز', $marcus);
 $marcus = str_replace('و', 'ﯛ̲୭', $marcus);
 $marcus = str_replace("ه", "ۿۿہ", $marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('ض','ضٰہٰٖ',$text);
$marcus = str_replace('ص','صٰہٰٖ',$marcus);
$marcus = str_replace('ث','ثٰہٰٖ',$marcus);
$marcus = str_replace('ق','قٰہٰٖ',$marcus);
$marcus = str_replace('ف','فٰہٰٖ',$marcus);
$marcus = str_replace('غ','غٰہٰٖ',$marcus);
$marcus = str_replace('ع','عٰہٰٖ',$marcus);
$marcus = str_replace('ه','هٰہٰٖ',$marcus);
$marcus = str_replace('خ','خٰہٰٖ',$marcus);
$marcus = str_replace('ح','حٰہٰٖ',$marcus);
$marcus = str_replace('ج','جٰہٰٖ',$marcus);
$marcus = str_replace('ش','شٰہٰٖ',$marcus);
$marcus = str_replace('س','سٰہٰٖ',$marcus);
$marcus = str_replace('ي','يٰہٰٖ',$marcus);
$marcus = str_replace('ب','بٰہٰٖ',$marcus);
$marcus = str_replace('ل','لہٰٖ',$marcus);
$marcus = str_replace('ا','اٰ',$marcus);
$marcus = str_replace('ت','تٰہٰٖ',$marcus);
$marcus = str_replace('ن','نٰہٰٖ',$marcus);
$marcus = str_replace('م','مٰہٰٖ',$marcus);
$marcus = str_replace('ك','كٰہٰٖ',$marcus);
$marcus = str_replace('ة','ةً',$marcus);
$marcus = str_replace('ء','ء',$marcus);
$marcus = str_replace('ظ','ظٰہٰٖ',$marcus);
$marcus = str_replace('ط','طٰہٰٖ',$marcus);
$marcus = str_replace('ذ','ذٖ',$marcus);
$marcus = str_replace('د','دٰ',$marcus);
$marcus = str_replace('ز','زٖ',$marcus);
$marcus = str_replace('ر','رٰ',$marcus);
$marcus = str_replace('و','وٰ',$marcus);
$marcus = str_replace('ى','ى',$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('ض','ضـٰ๋۪͜ﮧٰ',$text); 
$marcus = str_replace('ص','صـٌٍ๋ۤ͜ﮧْ',$marcus); 
$marcus = str_replace('ث','ث̲ꫭـﮧ',$marcus); 
$marcus = str_replace('ق','قٰٰྀ̲ـِٰ̲ﮧْ',$marcus); 
$marcus = str_replace('ف','',$marcus); 
$marcus = str_replace('غ','فـٌٍ๋ۤ͜ﮧ',$marcus); 
$marcus = str_replace('ع','غـّٰ̐ہٰٰ',$marcus); 
$marcus = str_replace('ه','ٰ̲ھہ',$marcus); 
$marcus = str_replace('خ','خ̲ﮧ',$marcus); 
$marcus = str_replace('ح','ح̲ꪳـﮧ',$marcus); 
$marcus = str_replace('ج','ج̲ꪸـﮧ',$marcus); 
$marcus = str_replace('ش','ش̲ꪾـﮧ',$marcus); 
$marcus = str_replace('س','سـ̷ٰٰﮧْ',$marcus); 
$marcus = str_replace('ي','يـِٰ̲ﮧ',$marcus); 
$marcus = str_replace('ب','ب̲ꪰـﮧ',$marcus);
$marcus = str_replace('ل','لٍُـّٰ̐ہ',$marcus); 
$marcus = str_replace('ا',' ཻا ',$marcus); 
$marcus = str_replace('ت','تـٰۧﮧ',$marcus); 
$marcus = str_replace('ن','نٰ̲̐ـﮧْ',$marcus); 
$marcus = str_replace('م','مٰٰྀ̲ـِٰ̲ﮧْ',$marcus); 
$marcus = str_replace('ك','كـِّﮧْٰٖ',$marcus); 
$marcus = str_replace('ة','ةً',$marcus); 
$marcus = str_replace('ء','ء',$marcus); 
$marcus = str_replace('ظ','ظَـ๋͜ﮧْ',$marcus); 
$marcus = str_replace('ط','ط̲꫁ـﮧ',$marcus); 
 $marcus = str_replace('ذ','ذٖ',$marcus); 
$marcus = str_replace('د','دُ',$marcus); 
$marcus = str_replace('ز','ژٰ',$marcus); 
$marcus = str_replace('ر','',$marcus); 
$marcus = str_replace('و','ﯛ૭',$marcus); 
 $marcus = str_replace('ى','ىِ',$marcus); 
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('ض','ضً',$text); 
$marcus = str_replace('ص','صً',$marcus); 
$marcus = str_replace('ث','ثہ',$marcus); 
$marcus = str_replace('ق','قہً',$marcus); 
$marcus = str_replace('ف','فُہ',$marcus); 
$marcus = str_replace('غ','غہ',$marcus); 
$marcus = str_replace('ع','عہُ',$marcus); 
$marcus = str_replace('ه','ه',$marcus); 
$marcus = str_replace('خ','خہ',$marcus); 
$marcus = str_replace('ح','حہ',$marcus); 
$marcus = str_replace('ج','جہ',$marcus); 
$marcus = str_replace('ش','شہ',$marcus); 
$marcus = str_replace('س','سہ',$marcus); 
$marcus = str_replace('ي','يہ',$marcus); 
$marcus = str_replace('ب',' ٻً',$marcus);
$marcus = str_replace('ل','لہ',$marcus); 
$marcus = str_replace('ا',' ٳ',$marcus); 
$marcus = str_replace('ت','تہ',$marcus); 
$marcus = str_replace('ن','نٍ',$marcus); 
$marcus = str_replace('ك','كُہ',$marcus); 
$marcus = str_replace('م','مْ',$marcus); 
$marcus = str_replace('ة','ةً',$marcus); 
$marcus = str_replace('ء','ء',$marcus); 
$marcus = str_replace('ظ','ظً',$marcus); 
$marcus = str_replace('ط','طہ',$marcus); 
 $marcus = str_replace('ذ','ذً',$marcus); 
$marcus = str_replace('د','دِ',$marcus); 
$marcus = str_replace('ز','زً',$marcus); 
$marcus = str_replace('ر','ڒٍ',$marcus); 
$marcus = str_replace('و','وٌ',$marcus); 
 $marcus = str_replace('ى','ىّ',$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('ا','ٱ',$text); 
$marcus = str_replace('ب','ﭜ',$marcus); 
$marcus = str_replace('ج','چ',$marcus); 
$marcus = str_replace('ث','ﭦ',$marcus); 
$marcus = str_replace('ت','ﭠ',$marcus); 
$marcus = str_replace('ح','ڂ',$marcus); 
$marcus = str_replace('خ','خ',$marcus); 
$marcus = str_replace('د','ﮃ',$marcus); 
$marcus = str_replace('ذ','ڎ',$marcus); 
$marcus = str_replace('ر','ر',$marcus); 
$marcus = str_replace('ز','ژ',$marcus); 
$marcus = str_replace('س','ﺳ̭͠ ',$marcus); 
$marcus = str_replace('ش','شَ',$marcus); 
$marcus = str_replace('ص','ڝ',$marcus); 
$marcus = str_replace('ض','ڞ',$marcus); 
$marcus = str_replace('ط','ط',$marcus); 
$marcus = str_replace('ظ','ڟ',$marcus); 
$marcus = str_replace('ع','؏',$marcus); 
$marcus = str_replace('غ','ﻏ̐ ',$marcus); 
$marcus = str_replace('ف','ڤ',$marcus); 
$marcus = str_replace('ق','ڦ',$marcus); 
$marcus = str_replace('ك','ڳ',$marcus); 
$marcus = str_replace('ل','لَ',$marcus);
$marcus = str_replace('م','م',$marcus); 
$marcus = str_replace('ن','ڻ',$marcus);
$marcus = str_replace('ه','هـﮧ',$marcus); 
$marcus = str_replace('و','و',$marcus); 
$marcus = str_replace('ي','يِّ',$marcus); 
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
$items = ['𝄮' , '𝄵' , '𓃠' , 'ま' , '†' , '⁦♡⁩' , '⁦˖꒰' , '⁦ਊ' , '❥' , '⁦㉨' , '𝆹𝅥𝅮' , '𝄬' , '𝄋' , '𖤍' , '𖠛' , ' 𝅘𝅥𝅮' , '⁦♬⁩' , '⁦⁦ㇱ' , '𝅘𝅥𝅯' , 'メ', '〠' , '〄' , '⩫',]; 
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('ض','ضً',$text); 
$marcus = str_replace('ص','صً',$marcus); 
$marcus = str_replace('ث','ثہ',$marcus); 
$marcus = str_replace('ق','قہً',$marcus); 
$marcus = str_replace('ف','فُہ',$marcus); 
$marcus = str_replace('غ','غہ',$marcus); 
$marcus = str_replace('ع','عہُ',$marcus); 
$marcus = str_replace('ه','ه',$marcus); 
$marcus = str_replace('خ','خہ',$marcus); 
$marcus = str_replace('ح','حہ',$marcus); 
$marcus = str_replace('ج','جہ',$marcus); 
$marcus = str_replace('ش','شہ',$marcus); 
$marcus = str_replace('س','سہ',$marcus); 
$marcus = str_replace('ي','يہ',$marcus); 
$marcus = str_replace('ب',' ٻً',$marcus);
$marcus = str_replace('ل','لہ',$marcus); 
$marcus = str_replace('ا',' ٳ',$marcus); 
$marcus = str_replace('ت','تہ',$marcus); 
$marcus = str_replace('ن','نٍ',$marcus); 
$marcus = str_replace('ك','كُہ',$marcus); 
$marcus = str_replace('م','مْ',$marcus); 
$marcus = str_replace('ة','ةً',$marcus); 
$marcus = str_replace('ء','ء',$marcus); 
$marcus = str_replace('ظ','ظً',$marcus); 
$marcus = str_replace('ط','طہ',$marcus); 
 $marcus = str_replace('ذ','ذً',$marcus); 
$marcus = str_replace('د','دِ',$marcus); 
$marcus = str_replace('ز','زً',$marcus); 
$marcus = str_replace('ر','ڒٍ',$marcus); 
$marcus = str_replace('و','وٌ',$marcus); 
 $marcus = str_replace('ى','ىّ',$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.$marcus.' '.$smile.'*',
'parse_mode'=>'MarkDown',
]);
 bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"
- تم زخرفة الاسم $text . 🦄💸
- ويمكنك رؤية الرموز ايضاً بالضغط على رموز.🦄💸
- يرجى الضغط على زر عوده في الاسفل . 🦄💸"
,'parse_mode'=>"markdown",'disable_web_page_preview'=>true,'reply_markup'=>json_encode(['inline_keyboard'=>[
[['text'=>'- زخرفة مرة اخرى ! 🦄💸' ,'callback_data'=>"ii"],['text'=>'- ألرمـوز . 🦄💸' ,'callback_data'=>"at"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}
if($data == "nb" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`اعـﹻٰـدآئي يمتلكون اجـﹻٰـمل خوات✗ْٰ̯⃕͡”㋡`

`ﻋيـﻧيۦثڪۑلهہۦﻣاټـﺸﯢڣۦٵڜڪالڮم✗ْٰ̯⃕͡”㋡`

`ۦﻣـ؏ـتڒڵۦٲڵـ؏ـڵاقـاﭢۦٲﻟـﻐـږﺍﻣـيہ✗ْٰ̯⃕͡”㋡`

`الي علمتهَم ؏ الحجـﮧٰۑ صـارو برآسي شيـوخ،✗ْٰ̯⃕͡”㋡`

`- ٱنـهہَ لجابتنـۑِ زلمـةهَ ولابسـةهَ ؏ـكال،✗ْٰ̯⃕͡”㋡`


`‏أقرأ كل يوم ، لا تنام بنفس العقل الذي أستيقظت به.`

`ترا شما خسرنا ، نعيش`

`ليحترق قلبك وانا لســــت اســف .`

`سنسمع الشيطان يستعيذ بالله منكم ذات يوم🖤،`

`الله موجود انتو شنو🤤🖤`

`: مَينزل رآسي ادوس فُوك رآسچ وارجع #عـاليةهَ .`

`• ۿناك قوة في كونك ۿادئاً 💗💧*.`

`آ̀ن̀ـآ̀ آ̀لـش̀́ـيـط̀́ـآ̀ن̀ـة آ̀لـتـي م̀ـيـزه̀ـآ̀ آ̀لـر̀ب ع̀́ن̀ آ̀لـكـل`

`• الشخـص المناسب لك لايرحل لاتقلقً💜`

`ֆ☺ فــقدت الــكثير ولازلــت أبتــسم`
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- التالي ! 🦄💸' ,'callback_data'=>"nb1"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}

if($data == "nb1" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`اصـيـله وتـكشـخ بخـيالـههاا🐎👑`

`الزلمهَ الشال العرآق بگلبه يشيلچ بروحه .♡،`

`لاتخبرني انهم تحدثُ عنِ بسوء 🙂اخبرني لماذا رتاحوا بالحديث امامك😏`

`اتعبني العالم مجدداً اين اذهب ♱`

`كـــان عــلى احــدنـا ان يـكـون بهــذه الـقسـوة لـيكمـل الاخــر طــريقـه`

`حتة من اريد اقبل عذر ماشوف ترضه جروحي ساعتهه راح ادخل حرب ما بين روحي وروحي`

`‏ان استطعت ان تبتعد يوما عني، فلا تعود ∝.`

`نحن نعيش في أرض تُدعى أرض ألسافلين.`

`كأنـي شيطان،وقَـع من السماء ليُلوث الارض .`

‏`لايحق لي أن أكتب عن الحُزن وأنتَ هنا .`

`◄يــٰٰٖــٰـا مــٰٰٖــٰـن ينتظــٰٰٖــٰـر سقوطــٰٰٖــٰـي ليتشفــٰٰٖــٰـى`

`-لن اهزم لانني اؤمن بنفسي دائما 🖤،`

`ءنــي ححـمـار ءنتـهه ششـنـو؟ حـمــار.،ڪك تشـرفـتت😹🌝`

`أقـسم لڪم بأني إتألم لڪن بأ ؏ـصاب جداً هادئة👋🏿🖤`
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- التالي ! 🦄💸' ,'callback_data'=>"nb2"]],
[['text'=>'- الى الخلف ! 🦄💸' ,'callback_data'=>"nb"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "nb2" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`- أ‏حـب نظــراتڪ ، وضحڪتك واحـب الأسـود عليڪ`

`ٱࢦيـتݛڪنـﯥ ٱتـݛڪھٰـہ ﯛ ٱتـفࢦ ؏ ﯛ جـهـﭑ ✗ ❭`

`مرات أحـسك عـدو بـــس!! أخـتل بسده 🙂♥️`

`سهولةه إلتڪلم معي ، لا تعني سهولةه ٲمتلٱڪي !‘✗ْٰ̯⃕͡㋡`

`-لا تُهمل وردتك حتي لا يسقيها غيرَك🙇🏿‍♂🖤`

`- زلـمۿ ومحد يڪـسرلي ڪـلمـۿ ، وحيد وقـوي وبـألف زلمـۿ 🙇🏿‍♀🖤.`

`ﺇﻥّ ﺍﻟﺤﻴﺎﺓ ﻻ ﺗﺘﻮﻗﻒ ﺃﺑﺪﺍً, ﻭﻣﻴﺎﻩ ﺍﻟﻨﻬﺮ ﻻ ﺗﻜﻒ ﻋﻦ ﺍﻟﺠﺮﻳﺎﻥ.`

`ﭑنـُﭑ لـۧسـِٰ̲ت مثڵٰهـِمʾ ﺂﻧـٰﺂ ﺂﻋٰ̲ـضـﮧم☻ ᴖ̈ ♩`

`- من يفكر في خسارتك ، ساعِده ،😹🙂`

`- فوَڪـٓۦ ءآنـٖيَ واآلٍڪًـٓلۦ جُؤآيٍ - ءسَطﭑ وٍڪـٓلۿا ) رﭑضﭑيًۦ ۦ 💗.`

`_ ولتـربو ؏ جتـآفـي بصيتيِ ڪبرِ رـآسسهم ، 🙇‍♀🖤.`

`ترهۂ ة ﺂﺂني ححلم ععشيرتـج ⁽♪̮͒₎🇺🇸`

`التاريخ لا يعيد نفسه بل الانسان يكرر غبائه .`

`ﭑنـُﭑ لـۧسـِٰ̲ت مثڵٰهـِمʾ ﺂﻧـٰﺂ ﺂﻋٰ̲ـضـﮧم☻ ᴖ̈ ♩`

`- تخوض حرباً لأجل احدهم فيقتلك هوه..𖤐`

`أنـآ أكذب .. لـآ شَـٰيٓء بخير يـآ صدِيقِـٰيٓ،🖤❕.`

`‏لا تستسلم لكلام الناس أسكتهم بنجاحك 🖤`

`‏آنه الحـــرگولي گلبي، بدون جــدحــة نار !`

﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- التالي ! 🦄💸' ,'callback_data'=>"nb3"]],
[['text'=>'- الى الخلف ! 🦄💸' ,'callback_data'=>"nb1"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "nb3" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`نبذة :-‏ע تحٰحن لـ شِخصٰء ﺄسٰتغنۍ ٰعٰنڪٰك ،`

`• مَ فــآد ڪـثر ألتوآجد ﻧججرب ألغــيآب ء ֆ #☻`

`• ﭑﻧﻧﭑ ملاڪك مـٰن. ﭑلـٰسمـﭑ وطـآحت ❥ 🍂.🖤

`ـآنــا ـآلسلطآن اﺑن ذآك لمآ نزلِ رـآسه🌝🖖🏾،`

`نَْبـْۦٰــذْھ•||• ﻣﺂﺂﺿېۦﯠﭤڕڪتهہۦۄطژۦﺑﻟﺨﺳڕتهہۦ`

`نَْبـْۦٰــذْھ•|| ؏ـرضك ﯛنـعـاﭑل ﯛثـنـيـنـهن ﯛصـخـات ،﴿`

`لاتغرڪ ضحٍڪتي شُمآيعٍلُِهـ صيتڪم بَلُِقٌندِرآ) ⁵⁶`

`أزيـن شاربڪك يلععفت اخوڪك بـضيـچ𓆩`

`ﻧـ؏ـثڕۙ ﺑس ﻧّڕډ ڼڪﯞ۾ ﯝ ﻣـٵ تهزنهہ همـﯢ۾ ✗ْٰ̯⃕͡”㋡`

`- ‏خسـارة البعـض ، مڪسب لصحتـكك النفـسـيـہۦة 🐸🖕`

`تــڕآ ڪﻟڪــﻡ تتعــﯛضـﯗن ! ﻟحــد يســﯛي ﻧفســهہ آخــړ ﻗطعــه ›!💔🐸`

`ﻋقلڪ برٱﺳڪ ونـﻋالڪ برﺟلڪ لاتبـدل بينهم بارڪ الله بيڪ?️☻🖕 ـٰ`

`•قويةه وححݪوھﮧ ومو بحاجةه لاي ﺂحد يلة دﯾﯿﮧ͡ـي☻🖕🏿،`

`ݥاِخخِذۿُ خـۧﺂاوۿ ؏ ؋ـٰرۏخ ﺗـﻠﻲٍ ᴖ̈ )`

`عـقلـــي بعـآالـم وَ ﭑنـا بعـآالـم وَ ﭑلعـآلـم بعـآالــم 💔☻`

`لقد ضا؏ ﺣذٱئي أتسمحون لي أن أرتـدي ﻋقـﯛلكم .‏ֆ ☻`

`•‏¦‹ﺂﺻْﺒّْﺣت ݛجـﯡݪتٌٍّْكّْم بٌّضْحّْكٌّْــﺈٌﺕٌ آݪحَْںݛيّمٌ هْــﮥ㋡!! ۦ`

`ـآليترسِ ظهِريٓ حچيٖ مِ ردَ عليهِ، ـآلچلبِ يكبر صيتهِ من تعآركهِ`

`ٱࢦيـتݛڪنـﯥ ٱتـݛڪھٰـہ ﯛ ٱتـفࢦ ؏ ﯛ جـهـﭑ ✗ ❭`

﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- الى الخلف ! 🦄💸' ,'callback_data'=>"nb2"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}

if($data == "asm" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`『 ﺂيَۈﺷۿ』`

`『مَݪۈڪۿ』`

`『بَنۈڼـۿ』`

`『ﺂﺳۈﺷۿ』`

`『تَبۈﺷۿ』`

`『𝚂𝙾𝚂𝙰𝙷』`

`『𝙱𝙰𝙽𝙾𝚂𝙰𝙷』`

`『𝚏𝚊𝚝??𝚜𝚊𝚑』`

`『𝙼𝙰𝙽𝙾??𝙰𝙷』`

`『𝚉𝙰𝙷𝙾𝚂𝙰𝙷』`
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- التالي ! 🦄💸' ,'callback_data'=>"asm1"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "asm1" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`داملاﭑ ఌ︎`

`ديلارﭑ ꨄ︎`

`نارفين ❥︎`

`ۿازال ♔︎`

`نيلۉفر ᴥ︎`

` ‏ٖ ٖتبوٰ ༗ 𖨆︎`

`ٖ ٖړنوٰ ༗ ㋛︎`

`ٖ ٖتبآركہٰ ✞︎༗`

`ٖ ٖآيمانہٰ ༗␈︎`

`ٖ ٖ␈︎ملآكہٰ ༗.`

`ٖ ٖنډى␈︎༗.`

`ٖ ٖطيبۿہٰ𓄁︎༗.`

`『𝙻𝙾𝚂𝙶』`

`『𝚉𝙴𝙴𝙽』`

`『𝙵𝚃𝙾𝚂𝙷𝙰』`

`『𝙼𝙽𝚃𝙰𝚉』`

`『𝙺𝙾𝙰𝙺𝙿』`
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- التالي ! 🦄💸' ,'callback_data'=>"asm2"]],
[['text'=>'- الى الخلف ! 🦄💸' ,'callback_data'=>"asm"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "asm2" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`⌯﮼ڪـمَـَٰـَُٰٰٰيـل𖤍༿`

`⌯﮼ ذوٰ୭‏ فقـَٰـَُٰٰٰـاﺂࢪ𖤍༿`

`⌯﮼ مـٛڵوڪـهہ𖤍༿`

`⌯﮼‌‏ ࢪضــاﺂويــۂ𖤍༿`

`⌯﮼‌‏ تبـٱࢪڪۂ𖤍༿`

`⌯﮼‌‏ نيـࢪمـﺂن𖤍༿`

`⌯﮼ ࢪ࣪ۿـࢪا۽𖤍༿`

• `ﭼـٰ̲ٱﺳـۧيڪَآ ،`

• `ـٱﻣـۧٱڹـڊـآ `

• `ﻟﮧۅڕيـۧڹ ؛`

• `ـٱﻣـۧيڵي ،`

`ΔᗰᗨNᗪΔ`

`Ꮮ𝑎𝑢𝑟𝑒𝑛`

` 𝐄𝐌𝐄𝐋𝐘`

` 𝐉𝒂𝒔𝒔𝒊𝒄𝒂`

﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- التالي ! 🦄💸' ,'callback_data'=>"asm3"]],
[['text'=>'- الى الخلف ! 🦄💸' ,'callback_data'=>"asm1"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "asm3" ){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎

`• ﭑسٰـيݪ ⁽️. ⁽𝒂𝒔𝒆𝒆𝒍`

`• ݪـمٰـﭑࢪ ⁽️. ⁽𝒍𝒂𝒎𝒂𝒓`

`• فٰـࢪحَ ⁽️. ⁽𝒇𝒂𝒓𝒂𝒉`

`• مٰيـﭑمٰيـטּ ⁽️. ⁽𝒎𝒚𝒂𝒎𝒚𝒏`

`• مٰـيࢪﭑ ⁽️. ⁽𝒎𝒊𝒓𝒂`

`• مٰـﭑࢪۉݪا ⁽️. ⁽𝒎𝒂𝒓𝒖𝒍𝒂`

`• مٰـﭑࢪݪـي ⁽️. ⁽𝒎𝒂𝒓𝒍𝒆𝒚`

`• جٰـۉدي ⁽️. ⁽𝒋𝒖𝒅𝒚`

`• مٰـﭑيـٰﭑ ⁽️. ⁽𝒎𝒂𝒚𝒂`

`• ڪـﭑتيـﭑ ⁽️. ⁽𝒌𝒂𝒕𝒊𝒂`

`• مٰـيݪا ⁽️. ⁽𝒎𝒆𝒍𝒂`

`• ࢪنٰـۉۉ ⁽️. ⁽𝒓𝒏??`

`• ٰﺂيٰـۉۉ ⁽️. ⁽𝒂𝒚𝒐`

`• ٰۿۿـِدﯛ ⁽️. ⁽𝒉𝒅𝒐`

`• سٓـࢪۉۉ ⁽️. ⁽𝒔𝒓𝒐𝒐`

`• سٓـجۉۉ ⁽️. ⁽𝒔𝒋𝒐𝒐`

`• حنٰـۉۉ ⁽️. ⁽𝒉𝒏𝒐`

`• ٰﺂسٓـۉۉ ⁽️. ⁽𝒂𝒔𝒐`
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
",
'parse_mode'=>'MarkDown',
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- الى الخلف ! 🦄💸' ,'callback_data'=>"asm2"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($data == "eeen" ){
file_put_contents("data/k99.txt","k99");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>'- حسنا قم بأرسال اسمك بلغة الانكليزية فقط !🦄💸',
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]); 
}
if($text != "/start" and $k99 == "k99" and $chat_id !=$k6 and $chat_id != $k7 and $chat_id != $bio and $chat_id != $bioch and $chat_id != $bu and $chat_id != $k5){
if (preg_match('/[a-z]/', $text) and !in_array($chat_id,$ad)){
file_put_contents("data/k99.txt","none");
bot('sendmessage',[ 'chat_id'=>$chat_id, 'text'=>"", ]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
$marcus = str_replace('a','𝗔',$text);
$marcus = str_replace("b","𝗕",$marcus);
$marcus = str_replace("c","𝗖",$marcus);
$marcus = str_replace("d","𝗗",$marcus);
$marcus = str_replace("e","𝗘",$marcus);
$marcus = str_replace("E","𝗙",$marcus);
$marcus = str_replace("g","𝗚",$marcus);
$marcus = str_replace("h","𝗛",$marcus);
$marcus = str_replace("i","𝗜",$marcus);
$marcus = str_replace("j","𝗝",$marcus);
$marcus = str_replace("k","𝗞",$marcus);
$marcus = str_replace("l","𝗟",$marcus);
$marcus = str_replace("m","𝗠",$marcus);
$marcus = str_replace("n","𝗡",$marcus);
$marcus = str_replace("o","𝗢",$marcus);
$marcus = str_replace("p","𝗣",$marcus);
$marcus = str_replace("q","𝗤",$marcus);
$marcus = str_replace("r","𝗥",$marcus);
$marcus = str_replace("s","𝗦",$marcus);
$marcus = str_replace("t","𝗧",$marcus);
$marcus = str_replace("u","𝗨",$marcus);
$marcus = str_replace("v","𝗩",$marcus);
$marcus = str_replace("w","𝗪",$marcus);
$marcus = str_replace("x","𝗫",$marcus);
$marcus = str_replace("y","𝗬",$marcus);
$marcus = str_replace("z","𝗭",$marcus);bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'〞'.$marcus.'༒𓄹〝'.$smile.'*',
'parse_mode'=>'MarkDown', ]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','𝐀',$text);
$marcus = str_replace("b","𝐁",$marcus);
$marcus = str_replace("c","𝐂",$marcus);
$marcus = str_replace("d","𝐃",$marcus);
$marcus = str_replace("e","𝐄",$marcus);
$marcus = str_replace("E","𝐅",$marcus);
$marcus = str_replace("g","𝐆",$marcus);
$marcus = str_replace("h","𝐇",$marcus);
$marcus = str_replace("i","𝐈",$marcus);
$marcus = str_replace("j","𝐉",$marcus);
$marcus = str_replace("k","𝐊",$marcus);
$marcus = str_replace("l","𝑳",$marcus);
$marcus = str_replace("m","𝐌",$marcus);
$marcus = str_replace("n","𝐍",$marcus);
$marcus = str_replace("o","𝐎",$marcus);
$marcus = str_replace("p","𝐏",$marcus);
$marcus = str_replace("q","𝐐",$marcus);
$marcus = str_replace("r","𝐑",$marcus);
$marcus = str_replace("s","𝐒",$marcus);
$marcus = str_replace("t","𝐓",$marcus);
$marcus = str_replace("u","𝐔",$marcus);
$marcus = str_replace("v","𝐕",$marcus);
$marcus = str_replace("w","𝐖",$marcus);
$marcus = str_replace("x","𝐗",$marcus);
$marcus = str_replace("y","𝐘",$marcus);
$marcus = str_replace("z","𝐙",$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'- 𝑰𝑻𝑺 »'.$marcus.'»'.$smile.'*',
'parse_mode'=>'MarkDown',]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','𝔸',$text);
$marcus = str_replace("b","𝔹",$marcus);
$marcus = str_replace("c","ℂ",$marcus);
$marcus = str_replace("d","𝔻",$marcus);
$marcus = str_replace("e","𝔼",$marcus);
$marcus = str_replace("E","𝔽",$marcus);
$marcus = str_replace("g","𝔾",$marcus);
$marcus = str_replace("h","ℍ",$marcus);
$marcus = str_replace("i","𝕀",$marcus);
$marcus = str_replace("j","𝕁",$marcus);
$marcus = str_replace("k","𝕂",$marcus);
$marcus = str_replace("l","𝕃",$marcus);
$marcus = str_replace("m","𝕄",$marcus);
$marcus = str_replace("n","ℕ",$marcus);
$marcus = str_replace("o","𝕆",$marcus);
$marcus = str_replace("p","ℙ",$marcus);
$marcus = str_replace("q","ℚ",$marcus);
$marcus = str_replace("r","ℝ",$marcus);
$marcus = str_replace("s","𝕊",$marcus);
$marcus = str_replace("t","𝕋",$marcus);
$marcus = str_replace("u","𝕌",$marcus);
$marcus = str_replace("v","𝕍",$marcus);
$marcus = str_replace("w","𝕎",$marcus);
$marcus = str_replace("x","𝕏",$marcus);
$marcus = str_replace("y","𝕪",$marcus);
$marcus = str_replace("z","ℤ",$marcus);bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'• ﴾'.$marcus.'﴿ ✬'.$smile.'*',
'parse_mode'=>'MarkDown',]); $items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','𝑨',$text); $marcus = str_replace('b','𝑩',$marcus); $marcus = str_replace('c','𝑪',$marcus); $marcus = str_replace('d','𝑫',$marcus); $marcus = str_replace('e','𝑬',$marcus); $marcus = str_replace('f','𝑭',$marcus); $marcus = str_replace('g','𝑮',$marcus); $marcus = str_replace('h','𝑯',$marcus); $marcus = str_replace('i','𝑰',$marcus); $marcus = str_replace('j','𝑱',$marcus); $marcus = str_replace('k','𝑲',$marcus); $marcus = str_replace('l','𝑳',$marcus); $marcus = str_replace('m','𝑴',$marcus); $marcus = str_replace('n','𝑵',$marcus); $marcus = str_replace('o','𝑶',$marcus); $marcus = str_replace('p','𝑷',$marcus); $marcus = str_replace('q','𝑸',$marcus); $marcus = str_replace('r','𝑹',$marcus); $marcus = str_replace('s','𝑺',$marcus); $marcus = str_replace('t','𝑻',$marcus); $marcus = str_replace('u','𝑽',$marcus); $marcus = str_replace('v','𝑽',$marcus); $marcus = str_replace('w','𝑾',$marcus); $marcus = str_replace('x','𝑿',$marcus); $marcus = str_replace('y','𝒀',$marcus); $marcus = str_replace('z','𝒁',$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.'- 𓊆'.$marcus.'𓊇✞'.$smile.'*',
'parse_mode'=>'MarkDown',]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','𝙰',$text); $marcus = str_replace('b','𝙱',$marcus); $marcus = str_replace('c','𝙲',$marcus); $marcus = str_replace('d','𝙳',$marcus); $marcus = str_replace('e','𝙴',$marcus); $marcus = str_replace('f','𝙵',$marcus); $marcus = str_replace('g','𝙶',$marcus); $marcus = str_replace('h','𝙷',$marcus); $marcus = str_replace('i','𝙸',$marcus); $marcus = str_replace('j','𝚓',$marcus); $marcus = str_replace('k','𝙺',$marcus); $marcus = str_replace('l','𝙻',$marcus); $marcus = str_replace('m','𝙼',$marcus); $marcus = str_replace('n','𝙽',$marcus); $marcus = str_replace('o','𝙾',$marcus); $marcus = str_replace('p','𝙿',$marcus); $marcus = str_replace('q','𝚀',$marcus); $marcus = str_replace('r','𝚁',$marcus); $marcus = str_replace('s','𝚂',$marcus); $marcus = str_replace('t','𝚃',$marcus); $marcus = str_replace('u','𝚞',$marcus); $marcus = str_replace('v','𝚅',$marcus); $marcus = str_replace('w','𝚆',$marcus); $marcus = str_replace('x','𝚇',$marcus); $marcus = str_replace('y','𝚈',$marcus); $marcus = str_replace('z','𝚉',$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.'ᯓ 𓆩'.$marcus.'𓆪 🇮??,'.$smile.'*',
'parse_mode'=>'MarkDown',]); 
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
$marcus = str_replace('a', '𝐴', $text);
$marcus = str_replace('b', 'b', $marcus);
$marcus = str_replace('c', '𝐶', $marcus);
$marcus = str_replace('d', '𝐷', $marcus);
$marcus = str_replace('e', '𝐸', $marcus);
$marcus = str_replace('f', '𝐹', $marcus);
$marcus = str_replace('g', '𝐺', $marcus);
$marcus = str_replace('h', '𝐻', $marcus);
$marcus = str_replace('i', '𝐼', $marcus);
$marcus = str_replace('j', '𝐽', $marcus);
$marcus = str_replace('k', '𝐾', $marcus);
$marcus = str_replace('l', '𝐿', $marcus);
$marcus = str_replace('m', '𝑀', $marcus);
$marcus = str_replace('n', '𝑁', $marcus);
$marcus = str_replace('o', '𝑂', $marcus);
$marcus = str_replace('p', '𝑃', $marcus);
$marcus = str_replace('q', '𝑄', $marcus);
$marcus = str_replace('r', '𝑅', $marcus);
$marcus = str_replace('s', '𝑆', $marcus);
$marcus = str_replace('t', '𝑇', $marcus);
$marcus = str_replace('u', '𝑉', $marcus);
$marcus = str_replace('v', '𝑊', $marcus);
$marcus = str_replace('w', '𝑊', $marcus);
$marcus = str_replace('x', '𝑋', $marcus);
$marcus = str_replace('y', '𝑌', $marcus);
$marcus = str_replace('z', '𝒖', $marcus);bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.'«「'.$marcus.'༗」»'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count($text); $marcus = str_replace('a',"ꪖ",$text);
$marcus = str_replace('A',"ꪖ",$marcus);
$marcus = str_replace("b","᥇",$marcus);
$marcus = str_replace("c","ᥴ",$marcus);
$marcus = str_replace("d","ᦔ",$marcus);
$marcus = str_replace("e","ꫀ",$marcus);
$marcus = str_replace("f","ᠻ",$marcus);
$marcus = str_replace("g","ᧁ",$marcus);
$marcus = str_replace("h","ꫝ",$marcus);
$marcus = str_replace("i","𝓲",$marcus);
$marcus = str_replace("j","𝓳",$marcus);
$marcus = str_replace("k","𝘬",$marcus);
$marcus = str_replace("l","ꪶ",$marcus);
$marcus = str_replace("m","ꪑ",$marcus);
$marcus = str_replace("n","ꪀ",$marcus);
$marcus = str_replace("o","ꪮ",$marcus);
$marcus = str_replace("p","ρ",$marcus);
$marcus = str_replace("q","𝘲",$marcus);
$marcus = str_replace("r","𝘳",$marcus);
$marcus = str_replace("s","𝘴",$marcus);
$marcus = str_replace("t","𝓽",$marcus);
$marcus = str_replace("u","ꪊ",$marcus);
$marcus = str_replace("v","ꪜ",$marcus);
$marcus = str_replace("w","᭙",$marcus);
$marcus = str_replace("x","᥊",$marcus);
$marcus = str_replace("y","ꪗ",$marcus);
$marcus = str_replace("z","ɀ",$marcus);
bot('sendMessage',[
'chat_id'=>$chat_id, 
'text'=>'*'.'˹'.$marcus.'˼༒'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ ??','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count(`$text`);$marcus = str_replace('a', 'ᴀ', $text);
$marcus = str_replace('b', 'ʙ', $marcus);
$marcus = str_replace('c', 'ᴄ', $marcus);
$marcus = str_replace('d', 'ᴅ', $marcus);
$marcus = str_replace('e', 'ᴇ', $marcus);
$marcus = str_replace('f', 'ᴈ', $marcus);
$marcus = str_replace('g', 'ɢ', $marcus);
$marcus = str_replace('h', 'ʜ', $marcus);
$marcus = str_replace('i', 'ɪ', $marcus);
$marcus = str_replace('j', 'ᴊ', $marcus);
$marcus = str_replace('k', 'ᴋ', $marcus);
$marcus = str_replace('l', 'ʟ', $marcus);
$marcus = str_replace('m', 'ᴍ', $marcus);
$marcus = str_replace('n', 'ɴ', $marcus);
$marcus = str_replace('o', 'ᴏ', $marcus);
$marcus = str_replace('p', 'ᴘ', $marcus);
$marcus = str_replace('q', 'ᴓ', $marcus);
$marcus = str_replace('r', 'ʀ', $marcus);
$marcus = str_replace('s', 'ᴤ', $marcus);
$marcus = str_replace('t', 'ᴛ', $marcus);
$marcus = str_replace('u', 'ᴜ', $marcus);
$marcus = str_replace('v', 'ᴠ', $marcus);
$marcus = str_replace('w', 'ᴡ', $marcus);
$marcus = str_replace('x', 'ᴥ', $marcus);
$marcus = str_replace('y', 'ʏ', $marcus);
$marcus = str_replace('z', 'ᴢ', $marcus);
bot('sendMessage',[
'chat_id'=>$chat_id, 
'text'=>'*'.' 『'.$marcus.'𖠛 』𖨬'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','ᗩ',$text);
$marcus = str_replace("b","ᗷ",$marcus);
$marcus = str_replace("c","ᑕ",$marcus);
$marcus = str_replace("d","ᗪ",$marcus);
$marcus = str_replace("e","E",$marcus);
$marcus = str_replace("E","E",$marcus);
$marcus = str_replace("g","G",$marcus);
$marcus = str_replace("h","ᕼ",$marcus);
$marcus = str_replace("i","I",$marcus);
$marcus = str_replace("j","ᒍ",$marcus);
$marcus = str_replace("k","K",$marcus);
$marcus = str_replace("l","ᒪ",$marcus);
$marcus = str_replace("m","ᗰ",$marcus);
$marcus = str_replace("n","ᑎ",$marcus);
$marcus = str_replace("o","O",$marcus);
$marcus = str_replace("p","ᑭ",$marcus);
$marcus = str_replace("q","ᑫ",$marcus);
$marcus = str_replace("r","ᖇ",$marcus);
$marcus = str_replace("s","ᔕ",$marcus);
$marcus = str_replace("t","T",$marcus);
$marcus = str_replace("u","ᑌ",$marcus);
$marcus = str_replace("v","ᐯ",$marcus);
$marcus = str_replace("w","ᗯ",$marcus);
$marcus = str_replace("x","᙭",$marcus);
$marcus = str_replace("y","Y",$marcus);
$marcus = str_replace("z","ᘔ",$marcus);bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'- 𓆪˹'.$marcus.'˼𓆩 𐂂”'.$smile.'*',
'parse_mode'=>'MarkDown',]); 
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','Ꭿ',$text);
$marcus = str_replace("b","Ᏸ",$marcus);
$marcus = str_replace("c","Ꮸ",$marcus);
$marcus = str_replace("d","Ꮷ",$marcus);
$marcus = str_replace("e","Ꮛ",$marcus);
$marcus = str_replace("f","Ꭶ",$marcus);
$marcus = str_replace("g","Ᏻ",$marcus);
$marcus = str_replace("h","Ᏺ",$marcus);
$marcus = str_replace("i","Ꭸ",$marcus);
$marcus = str_replace("j","Ꮰ",$marcus);
$marcus = str_replace("k","Ꮵ",$marcus);
$marcus = str_replace("l","Ꮭ",$marcus);
$marcus = str_replace("m","ᗰ",$marcus);
$marcus = str_replace("n","Ꮑ",$marcus);
$marcus = str_replace("o","Ꭷ",$marcus);
$marcus = str_replace("p","Ꭾ",$marcus);
$marcus = str_replace("q","Ꮕ",$marcus);
$marcus = str_replace("r","ᖇ",$marcus);
$marcus = str_replace("s","Ꮥ",$marcus);
$marcus = str_replace("t","Ꮱ",$marcus);
$marcus = str_replace("u","Ꮼ",$marcus);
$marcus = str_replace("v","Ꮙ",$marcus);
$marcus = str_replace("w","Ꮗ",$marcus);
$marcus = str_replace("x","Ꮂ",$marcus);
$marcus = str_replace("y","Ꮍ",$marcus);
$marcus = str_replace("z","ᔓ",$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'• ﴾'.$marcus.'﴿ ✬'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a', 'Ꭿ', $text);
$marcus = str_replace('b', 'ℬ', $marcus);
$marcus = str_replace('c', 'Ꮯ', $marcus);
$marcus = str_replace('d', 'Ꭰ', $marcus);
$marcus = str_replace('e', 'ℰ', $marcus);
$marcus = str_replace('f', 'ℱ', $marcus);
$marcus = str_replace('g', 'Ꮆ', $marcus);
$marcus = str_replace('h', 'ℋ', $marcus);
$marcus = str_replace('i', 'ℐ', $marcus);
$marcus = str_replace('j', 'Ꭻ', $marcus);
$marcus = str_replace('k', 'Ꮶ', $marcus);
$marcus = str_replace('l', 'ℒ', $marcus);
$marcus = str_replace('m', 'ℳ', $marcus);
$marcus = str_replace('n', 'Ꮑ', $marcus);
$marcus = str_replace('o', 'Ꮎ', $marcus);
$marcus = str_replace('p', 'Ꮲ', $marcus);
$marcus = str_replace('q', 'ℚ', $marcus);
$marcus = str_replace('r', 'ℛ', $marcus);
$marcus = str_replace('s', 'Ѕ', $marcus);
$marcus = str_replace('t', 'Ꮖ', $marcus);
$marcus = str_replace('u', 'U', $marcus);
$marcus = str_replace('v', 'Ꮙ', $marcus);
$marcus = str_replace('w', 'Ꮗ', $marcus);
$marcus = str_replace('x', 'Ж', $marcus);
$marcus = str_replace('y', '‏ϒ', $marcus);
$marcus = str_replace('z', 'Ž', $marcus); bot('sendMessage',[ 'chat_id'=>$chat_id, 'text'=>'*'.'𖣂 -'.$marcus.'༆”'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text);
$marcus = str_replace('a','𝙰',$text); $marcus = str_replace('b','𝙱',$marcus); $marcus = str_replace('c','𝙲',$marcus); $marcus = str_replace('d','𝙳',$marcus); $marcus = str_replace('e','𝙴',$marcus); $marcus = str_replace('f','𝙵',$marcus); $marcus = str_replace('g','𝙶',$marcus); $marcus = str_replace('h','𝙷',$marcus); $marcus = str_replace('i','𝙸',$marcus); $marcus = str_replace('j','𝚓',$marcus); $marcus = str_replace('k','𝙺',$marcus); $marcus = str_replace('l','𝙻',$marcus); $marcus = str_replace('m','𝙼',$marcus); $marcus = str_replace('n','𝙽',$marcus); $marcus = str_replace('o','𝙾',$marcus); $marcus = str_replace('p','𝙿',$marcus); $marcus = str_replace('q','𝚀',$marcus); $marcus = str_replace('r','𝚁',$marcus); $marcus = str_replace('s','𝚂',$marcus); $marcus = str_replace('t','𝚃',$marcus); $marcus = str_replace('u','𝚞',$marcus); $marcus = str_replace('v','𝚅',$marcus); $marcus = str_replace('w','𝚆',$marcus); $marcus = str_replace('x','𝚇',$marcus); $marcus = str_replace('y','𝚈',$marcus); $marcus = str_replace('z','𝚉',$marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.'ᯓ 「'.$marcus.'」، ⦃'.$smile.'*',
'parse_mode'=>'MarkDown',]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count($text); 
$marcus = str_replace('a', 'A҉', $text);
$marcus = str_replace('b', 'B҉', $marcus);
$marcus = str_replace('c', 'C҉', $marcus);
$marcus = str_replace('d', 'D҉', $marcus);
$marcus = str_replace('e', 'E҉', $marcus);
$marcus = str_replace('f', 'F҉', $marcus);
$marcus = str_replace('g', 'G҉', $marcus);
$marcus = str_replace('h', 'H҉', $marcus);
$marcus = str_replace('i', ' I҉ ', $marcus);
$marcus = str_replace('j', 'J҉', $marcus);
$marcus = str_replace('k', 'K҉', $marcus);
$marcus = str_replace('l', 'L҉', $marcus);
$marcus = str_replace('m', 'M҉', $marcus);
$marcus = str_replace('n', 'N҉', $marcus);
$marcus = str_replace('o', 'O҉', $marcus);
$marcus = str_replace('p', 'P҉', $marcus);
$marcus = str_replace('q', 'Q҉', $marcus);
$marcus = str_replace('r', 'R҉', $marcus);
$marcus = str_replace('s', 'S҉', $marcus);
$marcus = str_replace('t', 'T҉', $marcus);
$marcus = str_replace('u', 'U҉', $marcus);
$marcus = str_replace('v', 'V҉', $marcus);
$marcus = str_replace('w', 'W҉', $marcus);
$marcus = str_replace('x', 'X҉', $marcus);
$marcus = str_replace('y', 'Y҉', $marcus);
$marcus = str_replace('z', 'Z҉', $marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'ᯓ 𓆩 ˹'.$marcus.'˼ 𓆪 '.$smile.'*',
'parse_mode'=>'MarkDown',]); $items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count($text); 
$marcus = str_replace('a','𝙰',$text); $marcus = str_replace('b','𝙱',$marcus); $marcus = str_replace('c','𝙲',$marcus); $marcus = str_replace('d','𝙳',$marcus); $marcus = str_replace('e','𝙴',$marcus); $marcus = str_replace('f','𝙵',$marcus); $marcus = str_replace('g','𝙶',$marcus); $marcus = str_replace('h','𝙷',$marcus); $marcus = str_replace('i','𝙸',$marcus); $marcus = str_replace('j','𝚓',$marcus); $marcus = str_replace('k','𝙺',$marcus); $marcus = str_replace('l','𝙻',$marcus); $marcus = str_replace('m','𝙼',$marcus); $marcus = str_replace('n','𝙽',$marcus); $marcus = str_replace('o','𝙾',$marcus); $marcus = str_replace('p','𝙿',$marcus); $marcus = str_replace('q','𝚀',$marcus); $marcus = str_replace('r','𝚁',$marcus); $marcus = str_replace('s','𝚂',$marcus); $marcus = str_replace('t','𝚃',$marcus); $marcus = str_replace('u','𝚞',$marcus); $marcus = str_replace('v','𝚅',$marcus); $marcus = str_replace('w','𝚆',$marcus); $marcus = str_replace('x','𝚇',$marcus); $marcus = str_replace('y','𝚈',$marcus); $marcus = str_replace('z','𝚉',$marcus);bot('sendMessage',[
'chat_id'=>$chat_id, 
'text'=>'*'.'#1🇮🇶𖨤𓆩'.$marcus.'𓆪'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count($text); 
$marcus = str_replace('a','𝗔',$text); $marcus = str_replace('b','𝗕',$marcus); $marcus = str_replace('c','𝗖',$marcus); $marcus = str_replace('d','𝗗',$marcus); $marcus = str_replace('e','𝗘',$marcus); $marcus = str_replace('f','𝗙',$marcus); $marcus = str_replace('g','𝗚',$marcus); $marcus = str_replace('h','𝗛',$marcus); $marcus = str_replace('i','𝗜',$marcus); $marcus = str_replace('j','𝗝',$marcus); $marcus = str_replace('k','𝗞',$marcus); $marcus = str_replace('l','𝗟',$marcus); $marcus = str_replace('m','𝗠',$marcus); $marcus = str_replace('n','𝗡',$marcus); $marcus = str_replace('o','𝗢',$marcus); $marcus = str_replace('p','𝗣',$marcus); $marcus = str_replace('q','𝗤',$marcus); $marcus = str_replace('r','𝗥',$marcus); $marcus = str_replace('s','𝗦',$marcus); $marcus = str_replace('t','𝗧',$marcus); $marcus = str_replace('u','𝗨',$marcus); $marcus = str_replace('v','𝗩',$marcus); $marcus = str_replace('w','𝗪',$marcus); $marcus = str_replace('x','𝗫',$marcus); $marcus = str_replace('y','𝗬',$marcus); $marcus = str_replace('z','𝗭',$marcus);bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>'*'.'𓂐『 𝒊𝒕’𝒔 ⌯'.$marcus.'』♱..'.$smile.'*',
'parse_mode'=>'MarkDown',]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count($text); $marcus = str_replace('a', '𝘢', $text);
$marcus = str_replace('b', '𝘣', $marcus);
$marcus = str_replace('c', '𝘤', $marcus);
$marcus = str_replace('d', '𝘥', $marcus);
$marcus = str_replace('e', '𝘦', $marcus);
$marcus = str_replace('f', '𝘧', $marcus);
$marcus = str_replace('g', '𝘨', $marcus);
$marcus = str_replace('h', '𝘩', $marcus);
$marcus = str_replace('i', '𝘪', $marcus);
$marcus = str_replace('j', '𝘫', $marcus);
$marcus = str_replace('k', '𝘬', $marcus);
$marcus = str_replace('l', '𝘭', $marcus);
$marcus = str_replace('m', '𝘮', $marcus);
$marcus = str_replace('n', '𝘯', $marcus);
$marcus = str_replace('o', '𝘰', $marcus);
$marcus = str_replace('p', '𝘱', $marcus);
$marcus = str_replace('q', '𝘲', $marcus);
$marcus = str_replace('r', '𝘳', $marcus);
$marcus = str_replace('s', '𝘴', $marcus);
$marcus = str_replace('t', '??', $marcus);
$marcus = str_replace('u', '𝘶', $marcus);
$marcus = str_replace('v', '𝘷', $marcus);
$marcus = str_replace('w', '𝘸', $marcus);
$marcus = str_replace('x', '𝘹', $marcus);
$marcus = str_replace('y', '𝘺', $marcus);
$marcus = str_replace('z', '𝘻', $marcus);bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>'*'.'ᯓ『'.$marcus.' 𖠛 』𖨬 🇮🇶'.$smile.'*',
'parse_mode'=>'MarkDown',]);
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
$marcus = str_replace('a', 'Ａ', $text);
$marcus = str_replace('b', 'Ｂ', $marcus);
$marcus = str_replace('c', 'Ｃ', $marcus);
$marcus = str_replace('d', 'Ｄ', $marcus);
$marcus = str_replace('e', 'Ｅ', $marcus);
$marcus = str_replace('f', 'Ｆ', $marcus);
$marcus = str_replace('g', 'Ｇ', $marcus);
$marcus = str_replace('h', 'Ｈ', $marcus);
$marcus = str_replace('i', 'Ｉ', $marcus);
$marcus = str_replace('j', 'Ｊ', $marcus);
$marcus = str_replace('k', 'Ｋ', $marcus);
$marcus = str_replace('l', 'Ｌ', $marcus);
$marcus = str_replace('m', 'Ｍ', $marcus);
$marcus = str_replace('n', 'Ｎ', $marcus);
$marcus = str_replace('o', 'Ｏ', $marcus);
$marcus = str_replace('p', 'Ｐ', $marcus);
$marcus = str_replace('q', 'Ｑ', $marcus);
$marcus = str_replace('r', 'Ｒ', $marcus);
$marcus = str_replace('s', 'Ｓ', $marcus);
$marcus = str_replace('t', 'Ｔ', $marcus);
$marcus = str_replace('u', 'Ｕ', $marcus);
$marcus = str_replace('v', 'Ｖ', $marcus);
$marcus = str_replace('w', 'Ｗ', $marcus);
$marcus = str_replace('x', 'Ｘ', $marcus);
$marcus = str_replace('y', 'Ｙ', $marcus);
$marcus = str_replace('z', 'Ｚ', $marcus);
bot('sendMessage',[ 
'chat_id'=>$chat_id,
'text'=>'*'.'«「'.$marcus.'༗」»'.$smile.'*',
'parse_mode'=>'MarkDown',]); 
$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',];
$_smile = array_rand($items,1);
$smile = $items[$_smile];
$count = count($text); 
$marcus = str_replace('a', '۰۪۫A۪۫۰', $text);
$marcus = str_replace('b', '۰۪۫B۪۫۰', $marcus);
$marcus = str_replace('c', '۰۪۫C۪۫۰', $marcus);
$marcus = str_replace('d', '۰۪۫D۪۫۰', $marcus);
$marcus = str_replace('e', '۰۪۫E۪۫۰', $marcus);
$marcus = str_replace('f', '۰۪۫F۪۫۰', $marcus);
$marcus = str_replace('g', '۰۪۫G۪۫۰', $marcus);
$marcus = str_replace('h', '۰۪۫H۪۫۰', $marcus);
$marcus = str_replace('i', '۰۪۫I۪۫۰', $marcus);
$marcus = str_replace('j', '۰۪۫J۪۫۰', $marcus);
$marcus = str_replace('k', '۰۪۫K۪۫۰', $marcus);
$marcus = str_replace('l', '۰۪۫L۪۫۰', $marcus);
$marcus = str_replace('m', '۰۪۫M۪۫۰', $marcus);
$marcus = str_replace('n', '۰۪۫N۪۫۰', $marcus);
$marcus = str_replace('o', '۰۪۫O۪۫۰', $marcus);
$marcus = str_replace('p', '۰۪۫P۪۫۰', $marcus);
$marcus = str_replace('q', '۰۪۫Q۪۫۰', $marcus);
$marcus = str_replace('r', '۰۪۫R۪۫۰', $marcus);
$marcus = str_replace('s', '۰۪۫S۪۫۰', $marcus);
$marcus = str_replace('t', '۰۪۫T۪۫۰', $marcus);
$marcus = str_replace('u', '۰۪۫U۪۫۰', $marcus);
$marcus = str_replace('v', '۰۪۫V۪۫۰', $marcus);
$marcus = str_replace('w', '۰۪۫W۪۫۰', $marcus);
$marcus = str_replace('x', '۰۪۫X۪۫۰', $marcus);
$marcus = str_replace('y', '۰۪۫Y۪۫۰', $marcus);
$marcus = str_replace('z', '۰۪۫Z۪۫۰', $marcus);bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'｟'.$marcus.'｠'.$smile.'*',
'parse_mode'=>'MarkDown',]);$items = $items = ['࿅ 𓆙','࿅ 𓆈','࿅ 𓀌','࿅ 𓀎','࿅ 𓅻','࿅ 𓉀','࿅ 𓈪','࿅ 𓌬','࿅ 𓃼','࿅ 𓅉','࿅ 𓈯','࿅ 𓀎',]; $_smile = array_rand($items,1); $smile = $items[$_smile];$count = count($text); 
$marcus = str_replace('a','𝙰',$text); $marcus = str_replace('b','𝙱',$marcus); $marcus = str_replace('c','𝙲',$marcus); $marcus = str_replace('d','𝙳',$marcus); $marcus = str_replace('e','𝙴',$marcus); $marcus = str_replace('f','𝙵',$marcus); $marcus = str_replace('g','𝙶',$marcus); $marcus = str_replace('h','𝙷',$marcus); $marcus = str_replace('i','𝙸',$marcus); $marcus = str_replace('j','𝚓',$marcus); $marcus = str_replace('k','𝙺',$marcus); $marcus = str_replace('l','𝙻',$marcus); $marcus = str_replace('m','𝙼',$marcus); $marcus = str_replace('n','𝙽',$marcus); $marcus = str_replace('o','𝙾',$marcus); $marcus = str_replace('p','𝙿',$marcus); $marcus = str_replace('q','𝚀',$marcus); $marcus = str_replace('r','𝚁',$marcus); $marcus = str_replace('s','𝚂',$marcus); $marcus = str_replace('t','𝚃',$marcus); $marcus = str_replace('u','𝚞',$marcus); $marcus = str_replace('v','𝚅',$marcus); $marcus = str_replace('w','𝚆',$marcus); $marcus = str_replace('x','𝚇',$marcus); $marcus = str_replace('y','𝚈',$marcus); $marcus = str_replace('z','𝚉',$marcus);bot('sendMessage',[ 
'chat_id'=>$chat_id, 
'text'=>'*'.'ᯓ 𓆩 ˹'.$marcus.'˼ 𓆪☬,'.$smile.'*',
'parse_mode'=>'MarkDown',]); 
bot('sendMessage',[
'chat_id'=>$chat_id, 
 'text'=>"
- تم زخرفة الاسم $text . 🦄💸
- ويمكنك رؤية الرموز ايضاً بالضغط على رموز.🦄💸
- يرجى الضغط على زر عوده في الاسفل . 🦄💸
"
,'parse_mode'=>"markdown",'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>'- زخرفة مرة اخرى ! 🦄💸' ,'callback_data'=>"eeen"],['text'=>'- ألرمـوز . 🦄💸' ,'callback_data'=>"at"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}}

$bu = file_get_contents("data/bu.txt");
$bioch = file_get_contents("data/bioch.txt");
$bio = file_get_contents("data/bio.txt");
$quotech3 = ["⌯ 𝗡𝗼𝘁 𝗲𝘃𝗲𝗿𝘆𝗼𝗻𝗲 𝘆𝗼𝘂 𝗹𝗼𝘀𝗲 𝗶𝘀 𝗮 𝗹𝗼𝘀𝘀༯",
"↬ 𝑖 𝑗𝑢𝑠𝑡 𝑤𝑎𝑛𝑡 𝑠𝑘𝑖𝑝 𝑚𝑦 𝑙𝑖𝑓𝑒 .",
"- 𝚗𝚘𝚋𝚘𝚍𝚊𝚢 𝚞𝚗𝚍𝚎𝚛𝚜𝚝𝚊𝚗𝚍𝚜 𝚢𝚘𝚞𝚛 𝚍𝚒𝚏𝚏𝚎𝚛𝚎𝚗𝚌𝚎 .ོ",
"- 𝙄‘𝙈 𝘽𝘼𝘿 𝘿𝙊𝙉𝙏 𝘾𝙊𝙈𝙀 𝘾𝙇𝙊𝙎𝙀༒ ٫",
"- 𓆰 𝙸𝙵 𝚆𝙴 𝙳𝙾𝙽 𝚃 𝙴𝙽𝙳 𝚆𝙰𝚁, 𝚆𝙰𝚁 𝚆𝙸𝙻𝙻 𝙴𝙽𝙳 𝚄𝚂 . ♰",
"- 𝖨 𝖺𝗆 𝗀𝗈𝗈𝖽 𝖺𝗍 𝗉𝗋𝖾𝗍𝖾𝗇𝖽𝗂𝗇𝗀 𝗍𝗁𝖺𝗍 𝗂 𝖺𝗆 𝖿𝗂𝗇𝖾 . 𓆩༒𓆪",
"⌁ 𝒊 𝒎 𝒕𝒉𝒆 𝒐𝒏𝒆 𝒚𝒐𝒖 𝒔𝒉𝒐𝒖𝒍𝒅 𝒍𝒐𝒗𝒆 𖠲",
"⌯ Don t Try To Fix Me ٫ i'm Not Broken 𖣂",
"𓄼 𝑱𝒖𝒔𝒕 𝑴𝒆 𓄹",]; 
$quotech2 = array_rand($quotech3,1);
$quotech = $quotech3[$quotech2];
$ex = explode("\n",$text);
$byy = $ex[0];
$linkk = $ex[1];
if($data == "mikbioch" ){
file_put_contents("data/bioch.txt","bioch");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>'
- حسنا أرسال معلومات قناتك
- رجاءا المعلومات حسبالتالي :
- معرف المنشئ
- معرف او رابط القناة ',
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
}
if($text != "/start" and $bioch == "bioch" and $chat_id !=$k6 and $chat_id != $k7 and $chat_id != $bio and $chat_id != $k5 and $chat_id != $bu){
file_put_contents("data/bioch.txt","none");
 bot('Sendmessage',[
'chat_id'=>$chat_id,
'text'=>"

 $quotech
__________
𝙱𝚈 ➤ : $byy
𝙻𝙸𝙽𝙺 ➤ : $linkk 𖢒
",
]);
 bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"
- تم صنع بايو قناة الى المعلومات التاليه 
- المنشئ : [$byy]
- القناة : [$linkk]
- ويمكنك رؤية الرموز ايضاً بالضغط على رموز 
- يرجى الضغط على زر عوده في الاسفل"
,'parse_mode'=>"markdown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>'- ألرمـوز . 🦄💸' ,'callback_data'=>"at"],['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
[['text'=>'- صنع مرة أخرى ! 🦄💸' ,'callback_data'=>"mikbioch"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}
 $quote3 = [
"I 𝘀𝘁𝗶𝗹𝗹 𝗳𝗮𝗹𝗹 𝗶𝗻 𝗹𝗼𝘃𝗲 𝘄𝗶𝘁𝗵 𝘆𝗼𝘂, 𝗲𝘃𝗲𝗿𝘆 𝗱𝗮𝘆",
"𝒀𝑶𝑼 𝑭𝑶𝑹𝑮𝑶𝑻 𝑯𝑶𝑾 𝑻𝑶 𝑳𝑶𝑽𝑬. 𝑨𝑮𝑨𝑰𝑵",
"𝗠𝘂𝘀𝗶𝗰 𝗱𝗶𝗱𝗻'𝘁 𝗸𝗶𝗹𝗹 𝗮𝗻𝘆𝗼𝗻𝗲",
"< 𝙄’𝙈 𝙏𝙃𝙀 𝙊𝙉𝙀 𝙔𝙊𝙐 𝙎𝙃𝙊𝙐𝙇𝘿 𝙇𝙊𝙑𝙀 >",
"- 𝕹𝖔𝖙𝖍𝖎𝖓𝖌 𝕳𝖊𝖆𝖑𝖘,𝕿𝖍𝖊 𝕻𝖆𝖘𝖙 𝕷𝖎𝖐𝖊 𝕿𝖎𝖒𝖊..",
"𝗟𝗲𝘁𝘀 𝗳𝗼𝗿𝗴𝗲𝘁 𝘁𝗵𝗲 𝗽𝗮𝘀𝘁 𝗮𝗻𝗱 𝗺𝗼𝘃𝗲 𝗼𝗻",
"٠〈 .𝘪 𝘴𝘦𝘦 𝘺𝘰𝘶 𝘪𝘯 𝘢𝘭𝘭 𝘮𝘺 𝘧𝘢𝘷𝘰𝘳𝘪𝘵𝘦. 〉٠—",
"𝗜 𝘄𝗮𝘀 𝗮 𝗴𝗼𝗼𝗱 𝗳𝗿𝗶𝗲𝗻𝗱 𝘁𝗼 𝗲𝘃𝗲𝗿𝘆𝗼𝗻𝗲 𝗯𝘂𝘁 𝗺𝘆𝘀𝗲𝗹𝗳.",
"𝗜 𝘄𝗮𝗻𝘁𝗲𝗱 𝘁𝗼 𝘁𝗲𝗹𝗹 𝘆𝗼𝘂 𝗮 𝗹𝗼𝘁.",
"< 𝘛𝘏𝘌 𝘍𝘜𝘛𝘜𝘙𝘌 𝘐𝘚 𝘕𝘖𝘛 𝘛𝘏𝘌 𝘚𝘈𝘔𝘌 >",
"𝗗?? 𝗡𝗢𝗧 𝗧𝗘𝗠𝗣𝗧 𝗠𝗘 𝗣𝗥𝗔𝗜𝗦𝗘 𝗢𝗥 𝗖𝗥𝗜𝗧𝗜𝗖𝗜𝗦𝗠",]; 
$quote2 = array_rand($quote3,1);
$quote = $quote3[$quote2];
$count = count($text);
$textbio = str_replace('a','𝗮',$text);
$textbio = str_replace("b","𝗯",$textbio);
$textbio = str_replace("c","𝗰",$textbio);
$textbio = str_replace("d","𝗱",$textbio);
$textbio = str_replace("e","𝗲",$textbio);
$textbio = str_replace("E","𝗳",$textbio);
$textbio = str_replace("g","𝗴",$textbio);
$textbio = str_replace("h","𝗵",$textbio);
$textbio = str_replace("i","𝗶",$textbio);
$textbio = str_replace("j","𝗷",$textbio);
$textbio = str_replace("k","𝗸",$textbio);
$textbio = str_replace("l","𝗹",$textbio);
$textbio = str_replace("m","𝗺",$textbio);
$textbio = str_replace("n","𝗻",$textbio);
$textbio = str_replace("o","𝗼",$textbio);
$textbio = str_replace("p","𝗽",$textbio);
$textbio = str_replace("q","𝗾",$textbio);
$textbio = str_replace("r","𝗿",$textbio);
$textbio = str_replace("s","𝘀",$textbio);
$textbio = str_replace("t","𝘁",$textbio);
$textbio = str_replace("u","𝘂",$textbio);
$textbio = str_replace("v","𝘃",$textbio);
$textbio = str_replace("w","𝘄",$textbio);
$textbio = str_replace("x","𝘅",$textbio);
$textbio = str_replace("y","𝘆",$textbio);
$textbio = str_replace("z","𝘇",$textbio);
$textbio = str_replace('A','𝗔',$textbio);
$textbio = str_replace("B","𝗕",$textbio);
$textbio = str_replace("C","𝗖",$textbio);
$textbio = str_replace("D","𝗗",$textbio);
$textbio = str_replace("E","𝗘",$textbio);
$textbio = str_replace("F","𝗙",$textbio);
$textbio = str_replace("G","𝗚",$textbio);
$textbio = str_replace("H","𝗛",$textbio);
$textbio = str_replace("I","𝗜",$textbio);
$textbio = str_replace("J","𝗝",$textbio);
$textbio = str_replace("K","𝗞",$textbio);
$textbio = str_replace("L","𝗟",$textbio);
$textbio = str_replace("M","𝗠",$textbio);
$textbio = str_replace("N","𝗡",$textbio);
$textbio = str_replace("O","𝗢",$textbio);
$textbio = str_replace("P","𝗣",$textbio);
$textbio = str_replace("Q","𝗤",$textbio);
$textbio = str_replace("R","𝗥",$textbio);
$textbio = str_replace("S","𝗦",$textbio);
$textbio = str_replace("T","𝗧",$textbio);
$textbio = str_replace("U","𝗨",$textbio);
$textbio = str_replace("V","𝗩",$textbio);
$textbio = str_replace("W","𝗪",$textbio);
$textbio = str_replace("X","𝗫",$textbio);
$textbio = str_replace("Y","𝗬",$textbio);
$textbio = str_replace("Z","𝙕",$textbio);
$textbio = str_replace("0","𝟎",$textbio);
$textbio = str_replace("1","𝟏",$textbio);
$textbio = str_replace("2","𝟐",$textbio);
$textbio = str_replace("3","𝟑",$textbio);
$textbio = str_replace("4","𝟒",$textbio);
$textbio = str_replace("5","𝟓",$textbio);
$textbio = str_replace("6","𝟔",$textbio);
$textbio = str_replace("7","𝟕",$textbio);
$textbio = str_replace("8","𝟖",$textbio);
$textbio = str_replace("9","𝟗",$textbio);
$ex = explode("\n",$textbio);
$name = $ex[0];
$age = $ex[1];
$frrom = $ex[2];
if($data == "mikbio" ){
file_put_contents("data/bio.txt","bio");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>'
- حسنا أرسالمعلوماتك لصنع بايو لك 
- رجاءا المعلومات حسبالتالي :
اسمك
عمرك
بلدك 
#ملاحضه / باللغه الانكليزيه فقط ، ',
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
}
$sme3 = ["🌼","🔱","📩","🧿","🐼","🧸","🌈",];
$sme2 = array_rand($sme3);
$sme = $sme3[$sme2];
if($text != "/start" and $bio == "bio" and $chat_id !=$k6 and $chat_id != $k7 and $chat_id != $k5 and $chat_id != $bioch and $chat_id != $bu){
file_put_contents("data/bio.txt","none");
 bot('Sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
$sme | 𝗻𝗮𝗺𝗲 : $name
$sme | 𝗳𝗿𝗼𝗺 : $frrom
$sme | 𝗮𝗴𝗲 : $age
$sme | 𝗤𝘂𝗼𝘁𝗲 :
 $quote
",
]);
 bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"
- تم صنع بايو الى المعلومات التاليه 
- الاسم : [$name]
- العمر : [$age]
- البلد :[$frrom]
- ويمكنك رؤية الرموز ايضاً بالضغط على رموز 
- يرجى الضغط على زر عوده في الاسفل"
,'parse_mode'=>"markdown",'disable_web_page_preview'=>true,'reply_markup'=>json_encode(['inline_keyboard'=>[
[['text'=>'- ألرمـوز . 🦄💸' ,'callback_data'=>"at"],['text'=>'- صنع مرة أخرى ! 🦄💸' ,'callback_data'=>"mikbio"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");

}

 if($data == "bupg" ){
file_put_contents("data/bu.txt","bu");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>'- حسنا قم بأرسال الاسم! 🦄💸',
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
}
$pu = ['ㄨ' , '卍' , 'ヾ' , 'ヽ' , 'ゞ' , '⁦ゝ' , '⁦᥊' , '⁦〃' , 'チ' , '⁦艾' , '𖡏' , '𖡊' , '𝄋' , '𖠛' , '𖠛' , ' ㇱ' , '⁦𖡘' , '⁦⁦ㇱ' , 'メ' , 'メ', '彡' , '仚' , '𖡞',]; 
$pg= array_rand($pu,1);
$bupg= $pu[$pg];
$pui = ['ㄨ' , '卍' , 'ヾ' , 'ヽ' , 'ゞ' , '⁦ゝ' , '⁦᥊' , '⁦〃' , 'チ' , '⁦艾' , '𖡏' , '𖡊' , '𝄋' , '𖠛' , '𖠛' , ' ㇱ' , '⁦𖡘' , '⁦⁦ㇱ' , 'メ' , 'メ', '彡' , '仚' , '𖡞',]; 
$pgi = array_rand($pui,1);
$bupgi = $pui[$pgi];
if($text != "/start" and $bu == "bu" and $chat_id !=$k6 and $chat_id != $k7 and $chat_id != $bio and $chat_id != $bioch and $chat_id != $k5){
file_put_contents("data/bu.txt","none");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"`".$bupgi.$text.$bupg."`"
,'parse_mode'=>"markdown",
'reply_to_message_id'=>$message->message_id
]);
 bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"
- تم صنع اسم الى لعبه ببجي
- الاسم : [$text]
- ويمكنك رؤية الرموز ايضاً بالضغط على رموز 
- يرجى الضغط على زر عوده في الاسفل"
,'parse_mode'=>"markdown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>'- صنع مرة أخرى ! 🦄💸' ,'callback_data'=>"bupg"],['text'=>'- ألرمـوز . 🦄💸' ,'callback_data'=>"at"]],
[['text'=>'- ألرجـوع . 🦄💸' ,'callback_data'=>"home"]],
]])
]);
unlink("data/bu.txt");
 unlink("data/k6.txt");
 unlink("data/k7.txt");
 unlink("data/k5.txt");
 unlink("data/bio.txt");
 unlink("data/k99.txt");
 unlink("data/bioch.txt");
}

$bot = file_get_contents("com.txt");
if($text == "/start" and in_array($chat_id,$ad)){
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
اهلا بك مطوري $name
",
'parse_mode'=>"Markdown",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"تغيير /start🎗","callback_data"=>"start"]],
[["text"=>"تفعيل التواصل🎫","callback_data"=>"utws"],["text"=>"تعطيل التواصل💫","callback_data"=>"ntws"]],
[["text"=>"حظر عضو💔","callback_data"=>"bn"],["text"=>"الغاء حظر عضو💥","callback_data"=>"unbn"]],
[["text"=>"اضافه ادمن🎟","callback_data"=>"admin"]],
[["text"=>"احصائيات الاعضاء🕳","callback_data"=>"mem"]],
[["text"=>"معلومات عضو بالايدي🧧","callback_data"=>"info"]],
[["text"=>"الاشتراك الاجباري🎴","callback_data"=>"chh"],["text"=>"الااذاعه💌","callback_data"=>"bcc"]],
[["text"=>"حذف كل الاحصائيات🃏","callback_data"=>"delbot"]],
]])
]); 
unlink("com.txt");
}
#رجوع
if($data == "bk" and in_array($chat_id2,$ad)){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
اهلا بك مطوري $name
",
'parse_mode'=>"Markdown",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"تغيير /start🎗","callback_data"=>"start"]],
[["text"=>"تفعيل التواصل🎫","callback_data"=>"utws"],["text"=>"تعطيل التواصل💫","callback_data"=>"ntws"]],
[["text"=>"حظر عضو💔","callback_data"=>"bn"],["text"=>"الغاء حظر عضو💥","callback_data"=>"unbn"]],
[["text"=>"اضافه ادمن🎟","callback_data"=>"admin"]],
[["text"=>"احصائيات الاعضاء🕳","callback_data"=>"mem"]],
[["text"=>"معلومات عضو بالايدي🧧","callback_data"=>"info"]],
[["text"=>"الاشتراك الاجباري🎴","callback_data"=>"chh"],["text"=>"الااذاعه💌","callback_data"=>"bcc"]],
[["text"=>"حذف كل الاحصائيات🃏","callback_data"=>"delbot"]],
]])
]); 
unlink("com.txt");
}
if($data == "delbot" and in_array($chat_id2,$ad)){
 bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- سيتم حذف اجصائيات البوت وكلشي . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- تأكيد . 🦄💸","callback_data"=>"dell"],["text"=>"- الغاء . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
if($data == "dell" and in_array($chat_id2,$ad)){
 bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- تمت العمليه بالفعل عاد البوت كبدايته . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
unlink("start.txt");
unlink("tw.txt");
unlink("blocklist.txt");
unlink("admin2.txt");
unlink("memb.txt");
unlink("rabt.txt");
unlink("id.txt");
unlink("ch.txt");
unlink("chc.txt");
unlink("zkf.txt");
}

if($data == "bcc" and in_array($chat_id2,$ad)){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- اختر نوع الاذاعه المطلوبه . 🦄💸",
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- اذاعه رساله . 🦄💸","callback_data"=>"bc"],["text"=>"- اذاعه بالتوجيه . 🦄💸","callback_data"=>"for"]],
[["text"=>"- اذاعه شفاف . 🦄💸","callback_data"=>"inln"],["text"=>"- اذاعه بالميديا . 🦄💸","callback_data"=>"med"]],
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
#قسم شتراك اجباري
if($data == "chh" and in_array($chat_id2,$ad)){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- قسم الاشتراك الاجباري . 🦄💸",
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- قناة عامه1 . 🦄💸","callback_data"=>"add2"],["text"=>"- قناة عامه2 . 🦄💸","callback_data"=>"add1"]],
[["text"=>"- قناة خاصه . 🦄💸","callback_data"=>"add"]],
[["text"=>"- حذف الاشتراك الاجباري . 🦄💸","callback_data"=>"remch"]],
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
$meb = explode("\n",file_get_contents("memb.txt"));
$band = explode("\n",file_get_contents("blocklist.txt"));
$mem = count($meb)-1;
$bnn = count($band)-1;
if($data == "mem" and in_array($chat_id2,$ad)){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"
💌--< $mem >-- - الاعضاء . 🦄💸

💟-- < $bnn >-- - المحظورين . 🦄💸
",
'parse_mode'=>"Markdown",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
#رساله ستارت
if($data == "start" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","start");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل كليشه ستارت الجديده علما يمكنك استخدام الماركداون . 🦄💸",
'disable_web_page_preview'=>true,
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
if($bot == "start" and $text != "/h" and $text != "/start" and in_array($chat_id,$ad)){
file_put_contents("start.txt","$text");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حفظ الستارت . 🦄💸",
'reply_to_message_id'=>$message->message_id,
]);
unlink("com.txt");
}
#تفعيل تواصل
if($data == "utws" and in_array($chat_id2,$ad)){
file_put_contents("tw.txt","on");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- تم تفعيل التواصل . 🦄💸",
]); 
}
#تعطيل تواصل
if($data == "ntws" and in_array($chat_id2,$ad)){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- تم تعطيل التواصل . 🦄💸",
]); 
unlink("tw.txt");
}
if($text and !in_array($from_id,$ebu) and !in_array($chat_id,$ad) and $tws == "on"){
bot('forwardMessage',[
'chat_id'=>$admin,
'from_chat_id'=>$chat_id,
'message_id'=>$update->message->message_id,
'text'=>$text,
]);
}
if($text and $message->reply_to_message && $text!="/info" && $text!="/ban" && $text!="/unban" && $text!="/forward" and !$data ){
bot('sendMessage',[
'chat_id'=>$message->reply_to_message->forward_from->id,
'text'=>$text,
]);
}
#اضافه ادمن
if($data == "admin" and $chat_id2 == $admin){
file_put_contents("com.txt","ad");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل ايدي المراد رفعه ادمن . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
if($bot == "ad" and $text != "/start" and $chat_id == $admin){
bot('sendMessage',[
'chat_id'=>$chat_id,
'text'=>"- تم رفعه بالتأكيد . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
bot('sendMessage',[
'chat_id'=>$text,
'text'=>"- تم رفعك ادمن في البوت . 🦄💸",
'parse_mode'=>'MarkDown',
]);
unlink("com.txt");
file_put_contents("admin2.txt","$text");
}
#مـآيخصـك
if($data == "admin" and $chat_id2 == $admin2){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- الامر لا يخصك . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
#حظر
if($data == "bn" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","bn");
 bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل ايدي العضو الان . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
if($bot == "bn" and $text != "/start" and in_array($chat_id,$ad)){
$myfile2 = fopen("blocklist.txt", "a") or die("Unable to open file!");	
fwrite($myfile2, "$text\n");
fclose($myfile2);
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حظره بالتأكيد . 🦄💸",
]);
bot('sendmessage',[
'chat_id'=>$text,
'text'=>"- تم حظرك من قبل مطور البوت . 🦄💸",
]);
unlink("com.txt");
}
#الغاء حظر
$listt = file_get_contents("blocklist.txt");
if($data == "unbn" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","unbn");
 bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل ايدي العضو الان . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
if($bot == "unbn" and $text != "/start" and in_array($chat_id,$ad)){
$newlist = str_replace($text,"",$listt);
file_put_contents("blocklist.txt",$newlist);
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- بالتأكيد تم الغاء الحظر . 🦄💸",
]);
bot('sendmessage',[
'chat_id'=>$text,
'text'=>"- تم رفع الحظر عنك . 🦄💸",
]);
unlink("com.txt");
}
#معلومات
if($data == "info" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","info");
 bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل ايدي العضو #-يجب ان يكون مشترك في البوت . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
}
if($bot == "info" and $text != "/start"and in_array($chat_id,$ad)){
$ine = json_decode(file_get_contents("http://api.telegram.org/bot".API_KEY."/getChat?chat_id=$text"));
$infe4 =$ine->result->first_name;
$infe2 =$ine->result->id;
$infe3 =$ine->result->username;
bot('sendMessage', [
'chat_id'=>$chat_id,
'text'=>"*- معلومات العضو هي . 🦄💸*
- الاسم . 🦄💸 : *$infe4* 
- المعرف . 🦄💸 : [@$infe3] 
- الايدي . 🦄💸 : `$infe2`",
'reply_to_message_id'=>$message->message_id,
'parse_mode'=>'MarkDown', 
]);
unlink("com.txt");
}
#شتراك اجباري1
if($data == "add2" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","ab");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل معرف قناتك بدون @ . 🦄💸",
'parse_mode'=>"Markdown",
]);
}
if($bot == "ab" and $text != "/h" and $text != "/start" and in_array($chat_id,$ad)){
file_put_contents("chc.txt","$text");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حفظ القناة . 🦄💸
- ارفع البوت ادمن في القناة . 🦄💸
- ارسل  /start للرجوع . 🦄💸",
'reply_to_message_id'=>$message->message_id,
]);
unlink("com.txt");
}
#شـترآك اجباري1
if($data == "add1" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","al");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل معرف قناتك بدون @ . 🦄💸",
'parse_mode'=>"Markdown",
]);
}

if($bot == "al" and $text != "/h" and $text != "/start" and in_array($chat_id,$ad)){
file_put_contents("ch.txt","$text");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حفظ القناة . 🦄💸
- ارفع البوت ادمن في القناة . 🦄💸
- ارسل  /start للرجوع . 🦄💸",
'reply_to_message_id'=>$message->message_id,
]);
unlink("com.txt");
}
#شتراك خاص
if($data == "add"and in_array($chat_id2,$ad)){
file_put_contents("com.txt","vv");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل ايدي قناتك  . 🦄💸
- مثال / -100078267657 . 🦄💸",
'parse_mode'=>"Markdown",
]);
}

if($bot == "vv" and $text != "/o" and $text != "/start" and in_array($chat_id,$ad)){
file_put_contents("com.txt","alo");
file_put_contents("id.txt","$text");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حفظ الايدي ارسل رابط قناتك الان . 🦄💸",
'reply_to_message_id'=>$message->message_id,
]);
}
if($bot == "alo" and $text != "/o" and $text != "/start" and in_array($chat_id,$ad)){
file_put_contents("rabt.txt","$text");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حفظ رابط قناتك . 🦄💸
- رابط القناة . 🦄💸 : `[$text]`
- ايدي القناة . 🦄💸 : `$al`
- ارسل /start للرجوع  . 🦄💸 ",
'parse_mode'=>"Markdown",
'reply_to_message_id'=>$message->message_id,
]);
unlink("com.txt");
}
#حذف قنوات
if($data == "remch" and in_array($chat_id2,$ad)){
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- تم حذف جميع قنوات الاشتراك الاجباري . 🦄💸",
'parse_mode'=>"Markdown",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]); 
unlink("rabt.txt");
unlink("id.txt");
unlink("ch.txt");
unlink("chc.txt");
}
#اذاعه
if($data == "bc" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","send");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل رسالتك الان يمكنك استخدام الماركداون . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]);
}
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$alshh3 = fgets($ali);
if($bot == "send" and in_array($chat_id,$ad)){
bot('sendMessage', [
'chat_id' =>$alshh3,
'text'=>$text,
'parse_mode'=>"MarkDown",
'disable_web_page_preview' =>"true"
]);
unlink("com.txt");
}
}
$tx = file_get_contents("alh.txt");
if($data == "inln" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","sn");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل النص الذي تريده كرساله للازرار يمكنك استخدام الماركداون . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]);
}
if($bot == "sn" and $text != "/start" and in_array($chat_id,$ad)){
file_put_contents("alh.txt","$text");
file_put_contents("com.txt","snn");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- استخدم الاوامر اسفل لانشاء الكيبورد الشفاف . 🦄💸
text = link
text = link + text = link
نص = رابط
نص = رابط + نص = رابط",
'reply_to_message_id'=>$message->message_id,
]);
}
$i=0;
$keyboard = [];
$keyboard["inline_keyboard"] = [];
$rows = explode("\n",$text);
foreach($rows as $row){
$j=0;
$keyboard["inline_keyboard"][$i]=[];
$bottons = explode("+",$row);
foreach($bottons as $botton){
$alsh = explode("=",$botton."=");
$Ibotton = ["text" => trim($alsh[0]), "url" => trim($alsh[1])];
$keyboard["inline_keyboard"][$i][$j] = $Ibotton;
$j++;}$i++;}
$reply_markup=json_encode($keyboard);
if($bot == "snn" and $text != "/start" and in_array($chat_id,$ad)){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$alshh = fgets($ali);
bot('sendmessage',[
'chat_id'=>$alshh,
'text'=>$tx,
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
'reply_markup'=>($reply_markup)
]);
}
unlink("com.txt");
unlink("alh.txt");
}
if($data == "for" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","fd");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل توجيهك الان . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]);
}
if($bot == "fd" and $text != "/start" and in_array($chat_id,$ad)){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$ali2 = fgets($ali);
bot('forwardMessage',[
 'chat_id'=>$ali2,
 'from_chat_id'=>$chat_id,
 'message_id'=>$message->message_id,
 ]);
 unlink("com.txt");
 }
 }
 if($data == "med" and in_array($chat_id2,$ad)){
file_put_contents("com.txt","mide");
bot('EditMessageText',[
'chat_id'=>$chat_id2,
'message_id'=>$message_id2,
'text'=>"- ارسل احده الميديا الان . 🦄💸",
"reply_markup"=>json_encode([
"inline_keyboard"=>[
[["text"=>"- ألرجـوع . 🦄💸","callback_data"=>"bk"]],
]])
]);
}
 if($message->video and $bot == "mide" and in_array($chat_id,$ad) and $text != "/start"){
 $ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$aly = fgets($ali);
bot('sendvideo',[
'chat_id'=>$aly,
'video'=>$message->video->file_id,
'caption'=>$message->caption,
'parse_mode'=>"MARKDOWN",'disable_web_page_preview'=>true,
]);
unlink("com.txt"); 
}
bot('sendmessage',[ 
'chat_id'=>$chat_id,
 'text'=>"- تم نشر الفيديو . 🦄💸",
]); 
}

if($message->document and $bot == "mide" and in_array($chat_id,$ad) and $text != "/start"){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){ 
$aly = fgets($ali);
bot('Senddocument',['chat_id'=>$aly,'document'=>$message->document->file_id,'caption'=>$message->caption,'parse_mode'=>"MARKDOWN",'disable_web_page_preview'=>true,
]);
unlink("com.txt");
}
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم نشر الملف او المتحركه . 🦄💸", 
]); 
} 

 if($message->audio and $bot == "mide" and in_array($chat_id,$ad) and $text != "/start"){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$aly = fgets($ali);
 bot('sendaudio',[
 'chat_id'=>$aly, 
'audio'=>$message->audio->file_id, 
 'caption'=>$message->caption,
'parse_mode'=>"MARKDOWN",'disable_web_page_preview'=>true,
 ]); 
 unlink("com.txt");
}
bot('sendmessage',[ 
'chat_id'=>$chat_id,
 'text'=>"- تم نشر الاغنيه . 🦄💸", 
]); 
} 

if($message->photo and $bot == "mide" and in_array($chat_id,$ad) and $text != "/start"){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$aly = fgets($ali);
bot('sendPhoto',[ 
 'chat_id'=>$aly,
'photo'=>$message->photo[0]->file_id,'caption'=>$message->caption,'parse_mode'=>"MARKDOWN",'disable_web_page_preview'=>true,
]);
unlink("com.txt");
}
bot('sendmessage',[ 
'chat_id'=>$chat_id, 
'text'=>"- تم نشر الصوره . 🦄💸", 
]); 
} 

if($message->voice and $bot == "mide" and in_array($chat_id,$ad) and $text != "/start"){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$aly = fgets($ali);
bot('sendvoice',[
 'chat_id'=>$aly, 
 'voice'=>$message->voice->file_id, 
'caption'=>$message->caption,'parse_mode'=>"MARKDOWN",'disable_web_page_preview'=>true,
]);
unlink("com.txt");
}
bot('sendmessage',[ 
'chat_id'=>$chat_id,
 'text'=>"- تم نشر البصمه . 🦄💸", 
]); 
} 
if($message->sticker and $bot == "mide" and in_array($chat_id,$ad) and $text != "/start"){
$ali = fopen( "memb.txt", 'r');
while(!feof( $ali)){
$aly = fgets($ali);
bot('sendsticker',[
'chat_id'=>$aly,
'sticker'=>$message->sticker->file_id
]);
unlink("com.txt"); 
}
bot('sendmessage',[
'chat_id'=>$chat_id,
 'text'=>"- تم نشر الملصق . 🦄💸", 
]); 
unlink("com.txt"); 
}



