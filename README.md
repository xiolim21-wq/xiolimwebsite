<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VIP MT GENERATOR</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="min-h-screen flex items-center justify-center bg-gradient-to-br from-gray-900 to-gray-800 text-white font-sans">

  <div class="bg-gray-900/95 p-8 rounded-2xl shadow-2xl w-full max-w-lg relative overflow-hidden">
    <!-- Gambar Header -->
    <img src="https://i.postimg.cc/9MCKdRtf/perverso-fondo3.jpg'" alt="Header Image" 
         class="w-full h-40 object-cover rounded-xl mb-5 shadow-md">

    <!-- Header -->
    <h1 class="text-3xl font-bold text-center text-blue-400 mb-2">METODE BAND/UNBAND WA</h1>
    <p class="text-center text-gray-400 mb-6">By Developer: <span class="text-read-500 font-semibold">Xiolim케</span></p>

    <!-- Dropdown -->
    <label for="template" class="block mb-2 font-semibold text-gray-300">Pilih Template:</label>
    <select id="template" onchange="updateText()" class="w-full p-3 rounded-lg bg-gray-800 text-white border border-gray-700 focus:ring-2 focus:ring-blue-500">
      <option value="spam">Spam To Manen</option>
      <option value="unban">Metode Unban Permanen</option>
    </select>

    <!-- Textarea -->
    <textarea id="output" class="w-full h-56 mt-4 p-4 rounded-lg bg-gray-800 text-gray-200 border border-gray-700 focus:ring-2 focus:ring-blue-500" readonly></textarea>

    <!-- Tombol -->
    <button onclick="copyText()" class="w-full mt-6 py-3 bg-blue-600 hover:bg-blue-700 text-white font-bold rounded-xl shadow-lg transition transform hover:scale-105">
      Salin Teks
    </button>
  </div>

  <script>
    const templates = {
      spam: `Xiolim케



Por favor, desative o número da minha conta (). O meu número de WhatsApp foi banido. Por favor, ative-o novamente. O meu número pessoal. Os meus amigos e familiares estão à minha espera. A minha conta comercial está muito chateada. Por favor, Sr. Assim que o meu número for aberto, ficarei muito grato. Se tiver algum erro, peço desculpa.

O meu número de WhatsApp está 🙏 imediatamente porque o número foi perdido.`,

      unban: `Xiolim케



𝗠𝗘𝗧𝗛𝗢𝗗𝗘 𝗣𝗘𝗥𝗠 𝗟𝗔𝗞𝗨𝗞𝗔𝗡 𝗕𝗔𝗡𝗗𝗜𝗡𝗚 𝗠𝗘𝗟𝗔𝗟𝗨𝗜 𝗕𝗔𝗡𝗧𝗨𝗔𝗡 𝗪𝗛𝗔𝗧𝗦𝗔𝗣𝗣 𝗕𝗜𝗦𝗡𝗜𝗦/𝗕𝗜𝗔𝗦𝗔

To the WhatsApp Support Team and to Mr. Mark Zuckerberg,

I would like to submit a request regarding the permanent blocking of my WhatsApp account. I have been a loyal WhatsApp user since 2016 and have always used my account in accordance with the Terms of Service:
https://www.whatsapp.com/legal/terms-of-service?lang=id_ID.
I have also been using WhatsApp officially as described here:
https://faq.whatsapp.com/641572844337957?locale=id_ID.

However, my WhatsApp account has recently been permanently blocked. I do not know the reason why the WhatsApp team decided to block my number. Therefore, I kindly request assistance from the WhatsApp Help Center (https://faq.whatsapp.com/) to help restore my WhatsApp account as soon as possible.

My blocked WhatsApp number is: https://wa.me/62xxx@support.com

I sincerely hope that WhatsApp and the Support Team can immediately recover my WhatsApp account. I will be waiting for the restoration as soon as possible.

Sincerely,
[xiolim케]
Thank you.

𝗡𝗢𝗧𝗘 :
𝗝𝗜𝗞𝗔 𝗠𝗘𝗡𝗗𝗔𝗣𝗧𝗞𝗔𝗡 𝗕𝗔𝗟𝗔𝗦𝗔𝗡 𝗣𝗥𝗢𝗦𝗘𝗦, 𝗞𝗘𝗥𝗔𝗠𝗔𝗧 𝗗𝗜𝗔𝗠𝗞𝗔𝗡 𝟭-𝟳 𝗝𝗔𝗠 𝗜𝗡𝗦𝗬𝗔𝗔𝗟𝗟𝗔𝗛 𝗝𝗘𝗕𝗢𝗟, 𝗚𝗔 𝗝𝗘𝗕𝗢𝗟? 𝗡𝗢 𝗠𝗨 𝗕𝗔𝗨, 𝗠𝗘𝗧𝗛𝗢𝗗𝗘 𝗜𝗡𝗜 𝗦𝗨𝗗𝗔𝗛 𝗗𝗜 𝗧𝗥𝗬 𝗗𝗔𝗡 𝗔𝗟𝗛𝗔𝗠𝗗𝗨𝗟𝗟𝗜𝗔𝗛 𝗧𝗘𝗥𝗕𝗨𝗞𝗧𝗜 𝗪𝗢𝗥𝗞`
    };

    function updateText() {
      const choice = document.getElementById("template").value;
      document.getElementById("output").value = templates[choice];
    }

    function copyText() {
      const text = document.getElementById("output");
      text.select();
      document.execCommand("copy");
      alert("✅ Teks berhasil disalin!");
    }

    // Load default
    updateText();
  </script>

</body>
</html>
