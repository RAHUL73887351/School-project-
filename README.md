<!DOCTYPE html>      <html lang="hi">      
<head>      
  <meta charset="UTF-8">      
  <meta name="viewport" content="width=device-width, initial-scale=1.0">      
  <title>वायुमंडलीय जल संकलन यंत्र</title>      
  <link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;600&display=swap" rel="stylesheet">      
  <style>      
    * { box-sizing: border-box; }      
    body {      
      margin: 0;      
      font-family: 'Baloo 2', cursive;      
      background: linear-gradient(135deg, #e0f7fa, #f1f8e9);      
      color: #222;      
    }      
    .top-banner {      
      background-color: #03045e;      
      color: #ffffff;      
      text-align: center;      
      padding: 10px 0;      
      font-size: 28px;      
      font-weight: bold;      
      text-shadow: 0 0 10px #00b4d8, 0 0 20px #0077b6;      
      position: sticky;      
      top: 0;      
      z-index: 1000;      
    }      
    header {      
      background-color: #00b4d8;      
      color: white;      
      padding: 20px;      
      text-align: center;      
      font-size: 2.2em;      
      border-bottom: 5px solid #03045e;      
    }      
    .typing {      
      font-size: 20px;      
      font-weight: bold;      
      padding: 10px 20px;      
      text-align: center;      
      white-space: nowrap;      
      overflow: hidden;      
      border-right: 2px solid;      
      width: 0;      
      animation: typing 4s steps(50, end) forwards, blink 0.75s step-end infinite;      
    }      
    @keyframes typing {      
      from { width: 0; }      
      to { width: 100%; }      
    }      
    @keyframes blink {      
      50% { border-color: transparent; }      
    }      
    .container {      
      max-width: 960px;      
      margin: 30px auto;      
      background: #ffffff;      
      padding: 30px;      
      border-radius: 16px;      
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);      
      animation: slideIn 1s ease-out forwards;      
      opacity: 0;      
      transform: translateY(100px);      
    }      
    @keyframes slideIn {      
      to {      
        opacity: 1;      
        transform: translateY(0);      
      }      
    }      
    h2 {      
      color: #0077b6;      
      font-size: 24px;      
      margin-top: 30px;      
    }      
    ul, ol {      
      padding-left: 20px;      
    }      
    li {      
      margin-bottom: 10px;      
    }      
    button.print-btn {      
      display: block;      
      margin: 30px auto;      
      padding: 10px 20px;      
      background-color: #00b4d8;      
      color: white;      
      border: none;      
      border-radius: 8px;      
      font-size: 16px;      
      cursor: pointer;      
      transition: background 0.3s ease;      
    }      
    button.print-btn:hover {      
      background-color: #0077b6;      
    }      
    footer {      
      text-align: center;      
      margin: 40px auto 20px;      
      color: #444;      
      font-size: 14px;      
    }      
  </style>      
</head>      
<body>      <div class="top-banner">🌟 Rahul Bharti 🌟</div>      
<header>🌍 वायुमंडलीय जल संकलन यंत्र</header>      
<div class="typing">👋 नमस्ते सर, सुप्रभात 🌅 यह प्रोजेक्ट आपके लिए </div>      <div class="container">      
  <h2>🔎 प्रस्तावना:</h2>      
  <p>विश्व स्तर पर जल संकट एक विकराल रूप ले चुका है। विशेषकर शहरी झुग्गियों, ग्रामीण इलाकों और मरुस्थलीय क्षेत्रों में पीने योग्य स्वच्छ जल की अनुपलब्धता ने जनजीवन को अत्यंत प्रभावित किया है। ऐसी परिस्थिति में, वैज्ञानिक नवाचारों द्वारा जलस्रोतों की खोज एक नितांत आवश्यक कदम बन जाता है। <strong>वायुमंडलीय जल संकलन यंत्र</strong> एक ऐसा ही अभिनव उपकरण है, जो वातावरण में उपस्थित अदृश्य जलवाष्प को संघनित करके उसे उपयोग योग्य जल में परिवर्तित करता है।</p>        <h2>🎯 उद्देश्य:</h2>      
  <ul>      
    <li>वायुमंडल में व्याप्त जलवाष्प का वैज्ञानिक विधियों द्वारा दोहन करना।</li>      
    <li>एकत्रित जल को आधुनिक तकनीकों से शुद्ध कर मानव उपभोग योग्य बनाना।</li>      
    <li>सौर ऊर्जा आधारित पोर्टेबल यंत्र का निर्माण करना।</li>      
    <li>जल संरक्षण के प्रति समाज को जागरूक करना।</li>      
  </ul>        <h2>🔧 आवश्यक सामग्री:</h2>      
  <ol>      
    <li>एल्यूमिनियम/स्टील प्लेट (संघनन हेतु ठंडी सतह)</li>      
    <li>पेल्टियर कूलिंग यूनिट या पंखा</li>      
    <li>सोलर पैनल और 12V बैटरी</li>      
    <li>जल संग्रह टैंक</li>      
    <li>तीन-स्तरीय फ़िल्टर: रेत, चारकोल, UV</li>      
    <li>PVC पाइप</li>      
    <li>Arduino (वैकल्पिक – स्मार्ट कंट्रोल के लिए)</li>      
  </ol>        <h2>🛠️ बनाने की विधि:</h2>      
  <ol>      
    <li><strong>1. सतह तैयार करें:</strong> प्लेट को ढलान में लगाएँ ताकि जल बह सके।</li>      
    <li><strong>2. कूलिंग यूनिट लगाएँ:</strong> प्लेट के नीचे पेल्टियर यूनिट लगाकर सतह को ठंडा बनाएँ।</li>      
    <li><strong>3. संघनन:</strong> हवा की नमी सतह पर टकराकर जल बूंदों में बदलेगी।</li>      
    <li><strong>4. जल संग्रह:</strong> यह बूंदें पाइप की सहायता से टैंक में पहुँचेंगी।</li>      
    <li><strong>5. शुद्धिकरण:</strong> जल को रेत, चारकोल व UV फिल्टर से गुजारें।</li>      
    <li><strong>6. ऊर्जा आपूर्ति:</strong> सौर पैनल बैटरी को चार्ज कर सभी यंत्रों को ऊर्जा देगा।</li>      
    <li><strong>7. Arduino द्वारा नियंत्रण:</strong> वैकल्पिक रूप से तापमान व नमी की निगरानी करें।</li>      
  </ol>        <h2>📦 डिज़ाइन सुझाव:</h2>      
  <p>इसे पोर्टेबल बॉक्स के रूप में डिज़ाइन करें, जो हल्का, वाटरप्रूफ और सौर ऊर्जा चालित हो, ताकि यह आसानी से किसी भी क्षेत्र में ले जाया जा सके।</p>        <h2>💡 उपयोगी सुझाव:</h2>      
  <ul>      
    <li>तटीय क्षेत्रों में यह अधिक प्रभावशाली कार्य करता है।</li>      
    <li>गर्मी में बेहतर प्रदर्शन करता है यदि सतह अच्छी तरह ठंडी हो।</li>      
    <li>उच्च स्थान पर इसे स्थापित करने से वायुमंडलीय नमी अधिक मिलती है।</li>      
  </ul>        <h2>✅ निष्कर्ष:</h2>      
  <p><strong>वायुमंडलीय जल संकलन यंत्र</strong> एक सरल, प्रभावी और हरित तकनीकी समाधान है, जो जल संकट को कम करने में सहायक सिद्ध हो सकता है। यह न केवल नवाचार का उदाहरण है, बल्कि जल संरक्षण की दिशा में एक सशक्त कदम भी है।</p>        <h2>📘 उपयोगिता:</h2>      
  <ul>      
    <li>विज्ञान प्रदर्शनी</li>      
    <li>गांव या मरुस्थलीय क्षेत्र</li>      
    <li>आपातकालीन स्थिति में</li>      
    <li>पर्यावरण शिक्षा कार्यक्रमों में</li>      
  </ul>      <button class="print-btn" onclick="window.print()">🖨️ प्रिंट करें</button>

</div>      <footer>📄 प्रोजेक्ट प्रस्तुतकर्ता: Rahul Bharti</footer>      </body>      
</html>      
