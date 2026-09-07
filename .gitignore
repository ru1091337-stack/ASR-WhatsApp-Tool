<!DOCTYPE html>
<html lang="ps" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="عصرالجمال هلمندي - WhatsApp Appeal Helper">
<title>عصرالجمال هلمندي | WhatsApp Appeal Helper</title>
<style>
:root{
  --bg1:#07131f; --bg2:#102b35; --card:rgba(255,255,255,.09);
  --line:rgba(255,255,255,.16); --text:#f4fbff; --muted:#b9cbd2;
  --accent:#25d366; --accent2:#00bfa5; --danger:#ff647c;
}
*{box-sizing:border-box}
body{
  margin:0; min-height:100vh; font-family:Arial,"Noto Sans",sans-serif;
  color:var(--text); background:
  radial-gradient(circle at 15% 10%,rgba(37,211,102,.20),transparent 28%),
  radial-gradient(circle at 90% 20%,rgba(0,191,165,.18),transparent 30%),
  linear-gradient(135deg,var(--bg1),var(--bg2));
}
.container{width:min(940px,92%);margin:auto;padding:25px 0 45px}
.top{display:flex;justify-content:space-between;align-items:center;gap:15px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px}
.logo{
 width:62px;height:62px;border-radius:20px;display:grid;place-items:center;
 background:linear-gradient(135deg,#25d366,#00a884);
 box-shadow:0 10px 35px rgba(37,211,102,.28);font-size:29px;font-weight:bold;
}
.brand h1{font-size:20px;margin:0 0 5px}
.brand p{font-size:12px;color:var(--muted);margin:0}
select{
 background:rgba(255,255,255,.10);color:#fff;border:1px solid var(--line);
 border-radius:12px;padding:10px 13px;outline:none
}
select option{color:#111}
.hero{text-align:center;padding:42px 0 25px}
.hero h2{font-size:clamp(28px,6vw,48px);margin:0 0 12px}
.hero p{max-width:680px;margin:auto;color:var(--muted);line-height:1.9}
.card{
 margin-top:22px;padding:25px;border:1px solid var(--line);border-radius:24px;
 background:var(--card);backdrop-filter:blur(15px);
 box-shadow:0 20px 60px rgba(0,0,0,.22)
}
label{display:block;margin-bottom:9px;font-weight:bold}
.input-row{display:flex;gap:10px}
input{
 width:100%;padding:15px;border-radius:14px;border:1px solid var(--line);
 background:rgba(0,0,0,.20);color:#fff;font-size:17px;outline:none;direction:ltr;
}
input:focus{border-color:var(--accent)}
button{
 border:0;border-radius:14px;padding:14px 19px;font-size:16px;font-weight:bold;
 cursor:pointer;transition:.2s
}
button:hover{transform:translateY(-1px)}
.primary{background:linear-gradient(135deg,#25d366,#00bfa5);color:#052018}
.email{background:#fff;color:#15242a;width:100%;margin-top:14px}
.email:disabled{opacity:.45;cursor:not-allowed;transform:none}
.result{display:none;margin-top:15px;padding:14px;border-radius:14px;line-height:1.8}
.error{background:rgba(255,100,124,.13);border:1px solid rgba(255,100,124,.35);color:#ffd9df}
.ok{background:rgba(37,211,102,.12);border:1px solid rgba(37,211,102,.3);color:#d7ffe5}
.small{font-size:12px;color:var(--muted);line-height:1.8;margin-top:12px}
.preview{
 margin-top:20px;padding:18px;border-radius:16px;background:rgba(0,0,0,.18);
 border:1px dashed var(--line);display:none
}
.preview h3{margin-top:0}
pre{
 white-space:pre-wrap;word-break:break-word;font-family:inherit;
 color:#e9f7fb;line-height:1.8;margin:0
}
.footer{text-align:center;color:var(--muted);font-size:12px;margin-top:25px}
@media(max-width:560px){.input-row{flex-direction:column}.primary{width:100%}}
</style>
</head>
<body>
<div class="container">
  <header class="top">
    <div class="brand">
      <div class="logo">✦</div>
      <div>
        <h1 id="brandPS">عصرالجمال هلمندي</h1>
        <p>𝑨𝑺𝑹 𝑨𝑳𝑱𝑨𝑴𝑳 𝑯𝑬𝑳𝑴𝑨𝑵𝑫𝑰</p>
      </div>
    </div>
    <select id="lang" aria-label="Language">
      <option value="ps">پښتو</option>
      <option value="en">English</option>
      <option value="fa">دری</option>
      <option value="ar">العربية</option>
    </select>
  </header>

  <section class="hero">
    <h2 id="title">د WhatsApp د ملاتړ غوښتنه</h2>
    <p id="intro">خپله WhatsApp شمېره په نړیوال فارمیټ کې ولیکه. که فورمټ سم وي، ستا شمېره به په لاندې Appeal متن کې په اتومات ډول واچول شي.</p>
  </section>

  <main class="card">
    <label id="numberLabel" for="phone">د WhatsApp شمېره</label>
    <div class="input-row">
      <input id="phone" type="tel" inputmode="tel" autocomplete="tel"
             placeholder="+937XXXXXXXXX" aria-describedby="help">
      <button class="primary" id="checkBtn" type="button">شمېره وګوره</button>
    </div>
    <div class="small" id="help">شمېره باید د + او د هېواد له کوډ سره وي؛ تش ځایونه، قوسونه او ډشونه مه کاروه.</div>
    <div id="result" class="result" role="alert"></div>

    <div class="preview" id="preview">
      <h3 id="previewTitle">ستاسې Appeal متن</h3>
      <pre id="appealText"></pre>
    </div>

    <button class="email" id="emailBtn" type="button" disabled>✉️ د ایمیل له لارې Appeal لېږل</button>
    <div class="small" id="emailNote">دا تڼۍ ستا د موبایل/کمپیوټر Email اپلیکیشن پرانیزي او همدا متن او ستا شمېره پکې چمتو کوي. د لېږلو وروستی کار ته کوې.</div>
  </main>

  <footer class="footer">© <span id="year"></span> عصرالجمال هلمندي — 𝑨𝑺𝑹 𝑨𝑳𝑱𝑨𝑴𝑳 𝑯𝑬𝑳𝑴𝑨𝑵𝑫𝑰</footer>
</div>

<script>
const I18N = {
 ps:{
  dir:"rtl",brand:"عصرالجمال هلمندي",title:"د WhatsApp د ملاتړ غوښتنه",
  intro:"خپله WhatsApp شمېره په نړیوال فارمیټ کې ولیکه. که فورمټ سم وي، ستا شمېره به په لاندې Appeal متن کې په اتومات ډول واچول شي.",
  number:"د WhatsApp شمېره",check:"شمېره وګوره",
  help:"شمېره باید د + او د هېواد له کوډ سره وي؛ تش ځایونه، قوسونه او ډشونه مه کاروه.",
  invalid:"❌ نمبر غلط دی. مهرباني وکړئ نړیوال فارمیټ وکاروئ، لکه +937XXXXXXXXX.",
  valid:"✅ شمېره د نړیوال فارمیټ له مخې سمه ده.",
  preview:"ستاسې Appeal متن",email:"✉️ د ایمیل له لارې Appeal لېږل",
  note:"دا تڼۍ ستا د موبایل/کمپیوټر Email اپلیکیشن پرانیزي او همدا متن او ستا شمېره پکې چمتو کوي. د لېږلو وروستی کار ته کوې.",
  subject:"WhatsApp Number Appeal",
  appeal:"Hello WhatsApp Support Team,\\n\\nI am having a problem using WhatsApp with the following phone number:\\n{NUMBER}\\n\\nPlease review the issue with this number and let me know what I need to do to use WhatsApp again. I believe there may be a mistake or an issue that needs review.\\n\\nThank you for your help.\\n\\nRegards,\\nASR ALJAML HELMANDI"
 },
 en:{
  dir:"ltr",brand:"Asr Aljaml Helmandi",title:"WhatsApp Support Request",
  intro:"Enter your WhatsApp number in international format. If the format is valid, your number will automatically be inserted into the Appeal text below.",
  number:"WhatsApp number",check:"Check number",
  help:"Use + and the country code; do not use spaces, brackets, or dashes.",
  invalid:"❌ Invalid number format. Please use international format, for example +937XXXXXXXXX.",
  valid:"✅ The number format is valid.",
  preview:"Your Appeal text",email:"✉️ Open Email with Appeal",
  note:"This button opens your device's Email app with the number and Appeal text prepared. You make the final decision to send it.",
  subject:"WhatsApp Number Appeal",
  appeal:"Hello WhatsApp Support Team,\\n\\nI am having a problem using WhatsApp with the following phone number:\\n{NUMBER}\\n\\nPlease review the issue with this number and let me know what I need to do to use WhatsApp again. I believe there may be a mistake or an issue that needs review.\\n\\nThank you for your help.\\n\\nRegards,\\nASR ALJAML HELMANDI"
 },
 fa:{
  dir:"rtl",brand:"عصرالجمال هلمندی",title:"درخواست پشتیبانی واتساپ",
  intro:"شماره واتساپ خود را با فرمت بین‌المللی وارد کنید. اگر فرمت درست باشد، شماره شما به‌صورت خودکار در متن درخواست درج می‌شود.",
  number:"شماره واتساپ",check:"بررسی شماره",
  help:"شماره باید با + و کد کشور باشد؛ فاصله، پرانتز و خط تیره استفاده نکنید.",
  invalid:"❌ شماره نادرست است. لطفاً فرمت بین‌المللی مانند +937XXXXXXXXX را وارد کنید.",
  valid:"✅ فرمت شماره درست است.",
  preview:"متن درخواست شما",email:"✉️ باز کردن ایمیل با متن درخواست",
  note:"این دکمه برنامه ایمیل دستگاه شما را با شماره و متن درخواست آماده باز می‌کند. ارسال نهایی را خودتان انجام می‌دهید.",
  subject:"درخواست بررسی شماره واتساپ",
  appeal:"Hello WhatsApp Support Team,\\n\\nI am having a problem using WhatsApp with the following phone number:\\n{NUMBER}\\n\\nPlease review the issue with this number and let me know what I need to do to use WhatsApp again. I believe there may be a mistake or an issue that needs review.\\n\\nThank you for your help.\\n\\nRegards,\\nASR ALJAML HELMANDI"
 },
 ar:{
  dir:"rtl",brand:"عصرالجمال هلمندي",title:"طلب دعم واتساب",
  intro:"أدخل رقم واتساب بصيغة دولية. إذا كانت الصيغة صحيحة، سيتم إدراج الرقم تلقائياً في نص الطلب أدناه.",
  number:"رقم واتساب",check:"فحص الرقم",
  help:"يجب أن يبدأ الرقم بـ + ورمز الدولة؛ لا تستخدم المسافات أو الأقواس أو الشرطات.",
  invalid:"❌ صيغة الرقم غير صحيحة. استخدم الصيغة الدولية مثل +937XXXXXXXXX.",
  valid:"✅ صيغة الرقم صحيحة.",
  preview:"نص طلب الدعم",email:"✉️ فتح البريد الإلكتروني مع الطلب",
  note:"يفتح هذا الزر تطبيق البريد في جهازك مع تجهيز الرقم ونص الطلب. أنت من يقرر الإرسال النهائي.",
  subject:"طلب مراجعة رقم واتساب",
  appeal:"Hello WhatsApp Support Team,\\n\\nI am having a problem using WhatsApp with the following phone number:\\n{NUMBER}\\n\\nPlease review the issue with this number and let me know what I need to do to use WhatsApp again. I believe there may be a mistake or an issue that needs review.\\n\\nThank you for your help.\\n\\nRegards,\\nASR ALJAML HELMANDI"
 }
};

let current="ps", validPhone="";

const $ = id => document.getElementById(id);

function applyLanguage(lang){
 current=lang;
 const t=I18N[lang];
 document.documentElement.lang=lang;
 document.documentElement.dir=t.dir;
 $("brandPS").textContent=t.brand;
 $("title").textContent=t.title;
 $("intro").textContent=t.intro;
 $("numberLabel").textContent=t.number;
 $("checkBtn").textContent=t.check;
 $("help").textContent=t.help;
 $("previewTitle").textContent=t.preview;
 $("emailBtn").textContent=t.email;
 $("emailNote").textContent=t.note;
 $("result").style.display="none";
 $("preview").style.display="none";
 $("emailBtn").disabled=true;
 validPhone="";
}

function normalizePhone(raw){
  return raw.trim().replace(/[\\s().-]/g,"");
}

function isValidInternationalPhone(phone){
  // E.164-style validation: + followed by 8-15 digits.
  return /^\\+[1-9]\\d{7,14}$/.test(phone);
}

function buildAppeal(number){
  return I18N[current].appeal.replace("{NUMBER}", number);
}

$("checkBtn").addEventListener("click",()=>{
  const t=I18N[current];
  const phone=normalizePhone($("phone").value);
  const result=$("result");
  $("preview").style.display="none";
  $("emailBtn").disabled=true;
  validPhone="";

  if(!isValidInternationalPhone(phone)){
    result.className="result error";
    result.textContent=t.invalid;
    result.style.display="block";
    return;
  }

  validPhone=phone;
  result.className="result ok";
  result.textContent=t.valid;
  result.style.display="block";
  $("appealText").textContent=buildAppeal(phone);
  $("preview").style.display="block";
  $("emailBtn").disabled=false;
});

$("emailBtn").addEventListener("click",()=>{
  if(!validPhone) return;
  const t=I18N[current];
  const subject=encodeURIComponent(t.subject);
  const body=encodeURIComponent(buildAppeal(validPhone));
  // No hard-coded recipient: this opens the user's email client,
  // so they can choose the official support address they intend to contact.
  window.location.href=`mailto:?subject=${subject}&body=${body}`;
});

$("phone").addEventListener("input",()=>{
  $("result").style.display="none";
  $("preview").style.display="none";
  $("emailBtn").disabled=true;
  validPhone="";
});

$("phone").addEventListener("keydown",e=>{
  if(e.key==="Enter") $("checkBtn").click();
});

$("lang").addEventListener("change",e=>applyLanguage(e.target.value));
$("year").textContent=new Date().getFullYear();
applyLanguage("ps");
</script>
</body>
</html>
