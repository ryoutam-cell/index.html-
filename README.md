<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>スルリム - この夏、自信を。きれいに、スルリム。</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;700&family=Shippori+Mincho:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            scroll-behavior: smooth;
        }
        .font-serif {
            font-family: 'Shippori Mincho', serif;
        }
        .bg-gradient-soft {
            background: linear-gradient(135deg, #fff5f5 0%, #f0f9ff 100%);
        }
        .floating-cta {
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        .card-shadow {
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Hero Section -->
    <header class="relative h-screen min-h-[600px] flex items-center overflow-hidden bg-white">
        <div class="absolute inset-0 z-0">
            <!-- Background Image Placeholder (Beach/Summer vibe) -->
            <div class="w-full h-full bg-cover bg-center opacity-80" style="background-image: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&q=80&w=2000');"></div>
            <div class="absolute inset-0 bg-gradient-to-r from-white/90 via-white/40 to-transparent"></div>
        </div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="max-w-2xl">
                <span class="inline-block px-4 py-1 mb-4 border border-rose-300 text-rose-500 text-sm tracking-widest font-bold rounded-full bg-white/80">
                    20代、忙しいあなたのための15分革命
                </span>
                <h1 class="text-5xl md:text-7xl font-serif leading-tight mb-6 text-gray-900">
                    この夏、自信を。<br>
                    <span class="text-rose-400">きれいに、スルリム。</span>
                </h1>
                <p class="text-lg md:text-xl text-gray-600 mb-10 leading-relaxed">
                    水着をあきらめたくないあなたへ。<br>
                    数回の注射で、理想のボディラインをデザイン。
                </p>
                <a href="#cta" class="inline-block bg-rose-400 hover:bg-rose-500 text-white font-bold py-4 px-10 rounded-full transition-all transform hover:scale-105 shadow-xl">
                    無料カウンセリングを予約する
                </a>
            </div>
        </div>
    </header>

    <!-- Trust Stats Section (New Info Added) -->
    <section class="py-12 bg-white border-b">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-4">
                    <p class="text-rose-400 text-sm font-bold mb-1">SAFETY</p>
                    <p class="text-2xl font-bold">10年間無事故</p>
                    <p class="text-xs text-gray-400 mt-2">※開院以来の累計</p>
                </div>
                <div class="p-4 border-l">
                    <p class="text-rose-400 text-sm font-bold mb-1">RESULTS</p>
                    <p class="text-2xl font-bold">症例15万人突破</p>
                    <p class="text-xs text-gray-400 mt-2">※グループ合計実績</p>
                </div>
                <div class="p-4 border-l">
                    <p class="text-rose-400 text-sm font-bold mb-1">QUALITY</p>
                    <p class="text-2xl font-bold">治験検証済み</p>
                    <p class="text-xs text-gray-400 mt-2">安全性を徹底追求</p>
                </div>
                <div class="p-4 border-l">
                    <p class="text-rose-400 text-sm font-bold mb-1">ORIGIN</p>
                    <p class="text-2xl font-bold">韓国独自開発</p>
                    <p class="text-xs text-gray-400 mt-2">最先端の美容技術</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pain Points Section -->
    <section class="py-20 bg-rose-50">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-serif mb-16 relative inline-block">
                水着の夢、あきらめていませんか？
                <span class="absolute -bottom-4 left-1/2 -translate-x-1/2 w-20 h-1 bg-rose-200"></span>
            </h2>
            
            <div class="grid md:grid-cols-3 gap-10 max-w-5xl mx-auto">
                <div class="bg-white p-8 rounded-2xl card-shadow">
                    <div class="w-16 h-16 bg-rose-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-rose-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                    </div>
                    <p class="font-bold mb-4">ボディラインが気になる</p>
                    <p class="text-gray-500 text-sm leading-relaxed">「でも自信がなくて、海に行くのが少し怖い…」</p>
                </div>
                
                <div class="bg-white p-8 rounded-2xl card-shadow">
                    <div class="w-16 h-16 bg-rose-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-rose-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    </div>
                    <p class="font-bold mb-4">運動する時間がない</p>
                    <p class="text-gray-500 text-sm leading-relaxed">「仕事が忙しくてジムに通う暇も体力もない…」</p>
                </div>
                
                <div class="bg-white p-8 rounded-2xl card-shadow">
                    <div class="w-16 h-16 bg-rose-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-rose-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
                    </div>
                    <p class="font-bold mb-4">即効性を求めている</p>
                    <p class="text-gray-500 text-sm leading-relaxed">「イベントまであと少し。手軽に変化を実感したい」</p>
                </div>
            </div>

            <div class="mt-16 p-8 bg-white rounded-3xl border-2 border-rose-200 max-w-3xl mx-auto">
                <p class="text-xl font-bold text-rose-500 mb-4">そんなあなたにおすすめの治療があります！</p>
                <h3 class="text-4xl font-serif font-bold mb-6">「そんなあなたにのスルリム」</h3>
                <p class="text-gray-600">治療時間はわずか<span class="text-rose-500 font-bold text-2xl mx-1">15分</span>程度。<br>短期間で理想の自分へ、その名はスルリム！</p>
            </div>
        </div>
    </section>

    <!-- Before/After Simulation -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-serif">スルリムで、理想の自分へ</h2>
                <p class="text-gray-500 mt-4">水着を着てもためらわない美しさを獲得できます。</p>
            </div>

            <div class="grid md:grid-cols-2 gap-12 max-w-4xl mx-auto">
                <!-- Case 1 -->
                <div class="relative group">
                    <div class="flex items-center space-x-4 mb-4">
                        <span class="bg-rose-400 text-white w-8 h-8 rounded-full flex items-center justify-center font-bold italic">1</span>
                        <p class="font-bold">カウンセリング〜施術</p>
                    </div>
                    <div class="aspect-square bg-gray-100 rounded-2xl overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1576091160550-2173dba999ef?auto=format&fit=crop&q=80&w=800" alt="Consultation" class="w-full h-full object-cover">
                        <div class="absolute bottom-4 right-4 bg-white/90 px-3 py-1 rounded text-xs font-bold">Step 1</div>
                    </div>
                    <p class="mt-4 text-sm text-gray-500 text-center">水着を着て遊んでいる自分をイメージしながら相談</p>
                </div>

                <!-- Case 2 -->
                <div class="relative group">
                    <div class="flex items-center space-x-4 mb-4">
                        <span class="bg-rose-400 text-white w-8 h-8 rounded-full flex items-center justify-center font-bold italic">2</span>
                        <p class="font-bold">理想のラインへ</p>
                    </div>
                    <div class="aspect-square bg-gray-100 rounded-2xl overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&q=80&w=800" alt="Result" class="w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-rose-500 text-white px-4 py-1 rounded-full text-xs font-bold shadow-lg">After</div>
                        <div class="absolute bottom-4 right-4 bg-white/90 px-3 py-1 rounded text-xs font-bold">Step 2</div>
                    </div>
                    <p class="mt-4 text-sm text-gray-500 text-center">自信を持って海で楽しむ、そんな美しい姿に</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Sururimu -->
    <section class="py-20 bg-sky-50">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-serif mb-12">スルリムが選ばれる理由</h2>
            <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div class="flex items-start bg-white p-6 rounded-xl shadow-sm text-left">
                    <div class="text-sky-400 mr-4 mt-1">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    </div>
                    <div>
                        <h4 class="font-bold mb-2">韓国の先端技術 × 日本の安心感</h4>
                        <p class="text-sm text-gray-500">美容大国韓国で独自開発された成分を、日本の厳しい基準に合わせ治験検証。最高品質を提供します。</p>
                    </div>
                </div>
                <div class="flex items-start bg-white p-6 rounded-xl shadow-sm text-left">
                    <div class="text-sky-400 mr-4 mt-1">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    </div>
                    <div>
                        <h4 class="font-bold mb-2">ダウンタイムを最小限に</h4>
                        <p class="text-sm text-gray-500">メスを使わない施術なので、腫れや痛みが少なく、翌日から普段通りの生活が可能です。</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Campaign Section / CTA -->
    <section id="cta" class="py-24 bg-gradient-to-b from-rose-50 to-white">
        <div class="container mx-auto px-6 max-w-4xl">
            <div class="bg-rose-400 rounded-[3rem] p-10 md:p-16 text-center text-white shadow-2xl relative overflow-hidden">
                <!-- Decor -->
                <div class="absolute top-0 right-0 -mr-10 -mt-10 w-40 h-40 bg-white/10 rounded-full"></div>
                <div class="absolute bottom-0 left-0 -ml-10 -mb-10 w-40 h-40 bg-white/10 rounded-full"></div>
                
                <h2 class="text-3xl md:text-5xl font-serif font-bold mb-6">
                    今なら<span class="text-yellow-300">初回特別価格</span>で<br>体験できる！
                </h2>
                <p class="text-xl opacity-90 mb-10">気になったそこのあなた、詳細はこちらから</p>
                
                <div class="space-y-4">
                    <button class="bg-white text-rose-500 text-xl font-bold py-6 px-12 rounded-full w-full max-w-md transition-all hover:shadow-2xl hover:scale-105 floating-cta">
                        まずは無料カウンセリングへ
                    </button>
                    <p class="text-xs opacity-75">（キャンペーン詳細は遷移先にて）</p>
                </div>
                
                <div class="mt-12 pt-8 border-t border-white/20 grid grid-cols-2 md:grid-cols-4 gap-4 text-xs font-bold tracking-tighter opacity-80">
                    <div>10年間無事故</div>
                    <div>実績15万人</div>
                    <div>治験検証済</div>
                    <div>韓国独自開発</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-gray-100 text-center">
        <div class="container mx-auto px-6">
            <p class="font-serif text-2xl text-gray-400 mb-4 tracking-widest">SURURIMU</p>
            <p class="text-xs text-gray-400">&copy; 2024 SURURIMU Beauty Clinic. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- Floating CTA for Mobile -->
    <div class="fixed bottom-6 right-6 z-50 md:hidden">
        <a href="#cta" class="bg-rose-500 text-white p-4 rounded-full shadow-2xl block">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"/></svg>
        </a>
    </div>

</body>
</html>
