[mapa_mental_estrat_gico_alento.html](https://github.com/user-attachments/files/34953636/mapa_mental_estrat_gico_alento.html)[Uploading ma<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />
  <title>.alento. — Mapa Mental Estratégico & Branding</title>

  <!-- Configurações de Web App (PWA) para iOS e Android -->
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="default" />
  <meta name="apple-mobile-web-app-title" content=".alento." />
  <meta name="mobile-web-app-capable" content="yes" />
  <meta name="theme-color" content="#FF6F61" />
  <meta name="description" content="Painel de branding, encomendas e projeto satélite da .alento. — bordado feito à mão." />

  <!-- Ícone oficial .a. gerado em SVG para Tela Inicial e Favicon -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Crect width='512' height='512' rx='112' fill='%23FF6F61'/%3E%3Ccircle cx='256' cy='256' r='208' fill='none' stroke='%23FFFFFF' stroke-opacity='0.45' stroke-width='6' stroke-dasharray='12 10'/%3E%3Ctext x='256' y='305' font-family='Georgia, serif' font-weight='bold' font-size='210' fill='%23FFFFFF' text-anchor='middle'%3E.a.%3C/text%3E%3C/svg%3E" />
  <link rel="apple-touch-icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Crect width='512' height='512' fill='%23FF6F61'/%3E%3Ccircle cx='256' cy='256' r='208' fill='none' stroke='%23FFFFFF' stroke-opacity='0.45' stroke-width='6' stroke-dasharray='12 10'/%3E%3Ctext x='256' y='305' font-family='Georgia, serif' font-weight='bold' font-size='210' fill='%23FFFFFF' text-anchor='middle'%3E.a.%3C/text%3E%3C/svg%3E" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Fraunces (Display/Logo) & Figtree (UI/Body) -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Figtree:wght@400;500;600;700&family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            alento: {
              coral: '#FF6F61',       /* Pantone 16-1546 Living Coral */
              deep: '#E2493B',        /* Coral Profundo */
              soft: '#FFF3F1',        /* Rosado Claro */
              border: '#FFDAD5',      /* Contorno */
              dark: '#3A2420',        /* Texto Principal */
              muted: '#7A5B56',       /* Texto Secundário */
              cream: '#FFFDFC'        /* Fundo Papel */
            }
          },
          fontFamily: {
            display: ['Fraunces', 'Georgia', 'serif'],
            sans: ['Figtree', 'system-ui', 'sans-serif']
          },
          boxShadow: {
            'soft': '0 10px 30px -5px rgba(255, 111, 97, 0.12)',
            'card': '0 4px 20px -2px rgba(58, 36, 32, 0.06)',
            'glow': '0 0 0 6px rgba(255, 111, 97, 0.15)'
          }
        }
      }
    }
  </script>

  <style>
    body {
      background-color: #FFFDFC;
      color: #3A2420;
      font-family: 'Figtree', sans-serif;
      background-image: radial-gradient(#FFDAD5 1px, transparent 1px);
      background-size: 24px 24px;
    }

    @keyframes floatSlow {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-5px); }
    }

    .animate-float {
      animation: floatSlow 5s ease-in-out infinite;
    }

    .stitch-line {
      stroke-dasharray: 6 6;
      animation: dashFlow 40s linear infinite;
    }

    @keyframes dashFlow {
      to { stroke-dashoffset: -1000; }
    }

    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #FFF3F1;
    }
    ::-webkit-scrollbar-thumb {
      background: #FFDAD5;
      border-radius: 999px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #FF6F61;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col selection:bg-alento-coral selection:text-white">

  <!-- Cabeçalho Institucional -->
  <header class="sticky top-0 z-30 bg-white/90 backdrop-blur-md border-b border-alento-border px-4 sm:px-8 py-3.5">
    <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-4">
      <div class="flex items-center gap-3.5">
        <div class="w-10 h-10 rounded-full bg-alento-coral flex items-center justify-center text-white font-display font-semibold text-xl shadow-sm select-none">
          .a.
        </div>
        <div>
          <div class="flex items-center gap-2">
            <h1 class="font-display font-semibold text-2xl tracking-tight text-alento-dark leading-none">.alento.</h1>
            <span class="text-xs font-medium px-2.5 py-0.5 rounded-full bg-alento-soft text-alento-deep border border-alento-border">
              Mapa Estratégico
            </span>
          </div>
          <p class="text-xs text-alento-muted mt-0.5">bordado feito à mão • Planejamento & Identidade</p>
        </div>
      </div>

      <!-- Controles de Visualização e Ação -->
      <div class="flex items-center gap-2 sm:gap-3 flex-wrap">
        <div class="bg-alento-soft p-1 rounded-full border border-alento-border flex items-center text-xs font-medium">
          <button id="btnViewMap" onclick="switchView('map')" class="px-3.5 py-1.5 rounded-full bg-alento-coral text-white shadow-sm transition-all cursor-pointer">
            Mapa Conectado
          </button>
          <button id="btnViewBoard" onclick="switchView('board')" class="px-3.5 py-1.5 rounded-full text-alento-muted hover:text-alento-dark transition-all cursor-pointer">
            Quadro Completo
          </button>
          <button id="btnViewOrders" onclick="switchView('orders')" class="px-3.5 py-1.5 rounded-full text-alento-muted hover:text-alento-dark transition-all cursor-pointer flex items-center gap-1.5">
            <span>Encomendas</span>
            <span id="ordersNavBadge" class="px-1.5 py-0.2 rounded-full bg-alento-coral/15 text-alento-deep text-[10px] font-bold">0</span>
          </button>
          <button id="btnViewSatellite" onclick="switchView('satellite')" class="px-3.5 py-1.5 rounded-full text-alento-muted hover:text-alento-dark transition-all cursor-pointer flex items-center gap-1.5">
            <span>Projeto Satélite</span>
          </button>
        </div>

        <button onclick="openQuickIdeaModal()" class="inline-flex items-center gap-1.5 px-4 py-2 rounded-full bg-alento-dark hover:bg-alento-deep text-white text-xs font-medium transition-colors shadow-sm cursor-pointer">
          <span class="text-base leading-none">+</span> Ideia Solta
        </button>

        <button id="btnInstallApp" onclick="openAppInstallGuide()" title="Como instalar no celular" class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-full bg-alento-soft hover:bg-alento-border/70 text-alento-deep border border-alento-border text-xs font-semibold transition-colors cursor-pointer">
          <span>📱</span> <span class="hidden sm:inline">App Celular</span>
        </button>

        <button onclick="exportMarkdown()" title="Exportar planejamento em texto" class="p-2 rounded-full bg-white hover:bg-alento-soft text-alento-dark border border-alento-border transition-colors cursor-pointer">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"/>
          </svg>
        </button>
      </div>
    </div>
  </header>

  <!-- Conteúdo Principal -->
  <main class="flex-1 max-w-7xl w-full mx-auto px-4 sm:px-8 py-6">

    <!-- VISÃO 1: MAPA MENTAL RADIAL INTERATIVO -->
    <section id="viewMap" class="block">
      <div class="flex flex-wrap items-center justify-between gap-2 mb-4 bg-white/80 border border-alento-border rounded-2xl px-4 py-2.5 text-xs text-alento-muted">
        <div class="flex items-center gap-2">
          <span class="text-alento-coral font-bold text-sm">✳</span>
          <span>Clique em qualquer <strong>pilar ao redor do núcleo</strong> para explorar os tópicos, valores e adicionar suas ideias.</span>
        </div>
        <div class="flex items-center gap-3">
          <span class="inline-flex items-center gap-1"><span class="w-2 h-2 rounded-full bg-alento-coral"></span> Pantone 16-1546</span>
          <button onclick="resetDefaultData()" class="underline hover:text-alento-deep cursor-pointer">Restaurar base</button>
        </div>
      </div>

      <!-- Canvas Radial (Desktop) -->
      <div class="hidden lg:block relative w-full h-[650px] bg-white/75 rounded-3xl border border-alento-border shadow-card overflow-hidden">
        <svg class="absolute inset-0 w-full h-full pointer-events-none" viewBox="0 0 1000 650" preserveAspectRatio="none">
          <!-- Lado Esquerdo: Pilares 01, 03, 05 -->
          <line x1="500" y1="325" x2="200" y2="120" stroke="#FF6F61" stroke-width="1.8" stroke-opacity="0.45" class="stitch-line" />
          <line x1="500" y1="325" x2="140" y2="325" stroke="#FF6F61" stroke-width="1.8" stroke-opacity="0.45" class="stitch-line" />
          <line x1="500" y1="325" x2="200" y2="530" stroke="#FF6F61" stroke-width="1.8" stroke-opacity="0.45" class="stitch-line" />
          <!-- Lado Direito: Pilares 02, 04, 06 -->
          <line x1="500" y1="325" x2="800" y2="120" stroke="#FF6F61" stroke-width="1.8" stroke-opacity="0.45" class="stitch-line" />
          <line x1="500" y1="325" x2="860" y2="325" stroke="#FF6F61" stroke-width="1.8" stroke-opacity="0.45" class="stitch-line" />
          <line x1="500" y1="325" x2="800" y2="530" stroke="#FF6F61" stroke-width="1.8" stroke-opacity="0.45" class="stitch-line" />
          <circle cx="500" cy="325" r="145" fill="none" stroke="#FFDAD5" stroke-width="1.2" stroke-dasharray="4 4" />
          <circle cx="500" cy="325" r="265" fill="none" stroke="#FFDAD5" stroke-width="1" stroke-dasharray="3 6" />
        </svg>

        <!-- Núcleo Central (Bastidor .alento. cravado exatamente no centro) -->
        <div class="absolute inset-0 flex items-center justify-center pointer-events-none z-20">
          <div onclick="openCentralManifesto()" class="animate-float pointer-events-auto w-56 h-56 rounded-full bg-alento-coral text-white flex flex-col items-center justify-center text-center p-5 shadow-soft shadow-glow cursor-pointer hover:scale-105 transition-transform border-4 border-white">
            <div class="w-48 h-48 rounded-full border border-white/60 flex flex-col items-center justify-center p-3">
              <span class="text-white/80 text-xs tracking-widest uppercase mb-1">✳ núcleo ✳</span>
              <h2 class="font-display font-semibold text-4xl tracking-tight leading-none">.alento.</h2>
              <p class="text-xs text-white/95 mt-1.5 font-normal">bordado feito à mão</p>
              <span class="mt-2.5 text-[11px] bg-white/20 px-2.5 py-0.5 rounded-full">Ver Essência</span>
            </div>
          </div>
        </div>

        <div id="radialNodesContainer" class="absolute inset-0 w-full h-full"></div>
      </div>

      <!-- Layout Mobile / Tablet -->
      <div class="lg:hidden space-y-4">
        <div onclick="openCentralManifesto()" class="bg-alento-coral text-white rounded-3xl p-6 text-center shadow-soft border-2 border-white cursor-pointer">
          <span class="text-xs uppercase tracking-widest text-white/80">✳ Núcleo da Marca ✳</span>
          <h2 class="font-display font-semibold text-4xl mt-1">.alento.</h2>
          <p class="text-sm text-white/90 mt-1">bordado feito à mão • Fôlego novo, ânimo e recomeço</p>
        </div>
        <div id="mobileNodesContainer" class="grid grid-cols-1 sm:grid-cols-2 gap-4"></div>
      </div>
    </section>

    <!-- VISÃO 2: QUADRO COMPLETO EM COLUNAS -->
    <section id="viewBoard" class="hidden space-y-6">
      <div class="flex flex-wrap items-center justify-between gap-3 bg-white border border-alento-border rounded-2xl p-4">
        <div>
          <h2 class="font-display font-semibold text-xl text-alento-dark">Estrutura Completa do Planejamento</h2>
          <p class="text-xs text-alento-muted">Todos os pilares e ideias organizadas lado a lado para consulta rápida.</p>
        </div>
        <div class="flex flex-wrap gap-1.5" id="boardFilterChips"></div>
      </div>
      <div id="boardCardsContainer" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5"></div>
    </section>

    <!-- VISÃO 3: PAINEL DE ENCOMENDAS EM CURSO + CALCULADORA -->
    <section id="viewOrders" class="hidden space-y-6">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
        <div class="bg-white border border-alento-border rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-alento-muted block">Em Andamento</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="statActiveCount" class="font-display font-semibold text-2xl sm:text-3xl text-alento-dark">0</span>
            <span class="text-xs text-alento-muted">peças na fila</span>
          </div>
        </div>
        <div class="bg-white border border-alento-border rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-alento-muted block">Total em Pedidos</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="statTotalValue" class="font-display font-semibold text-2xl sm:text-3xl text-alento-dark">R$ 0,00</span>
          </div>
        </div>
        <div class="bg-emerald-50/70 border border-emerald-200 rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-emerald-800 block">Sinal Recebido</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="statDepositPaid" class="font-display font-semibold text-2xl sm:text-3xl text-emerald-700">R$ 0,00</span>
          </div>
        </div>
        <div class="bg-alento-soft border border-alento-border rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-alento-deep block">A Receber na Entrega</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="statRemainingValue" class="font-display font-semibold text-2xl sm:text-3xl text-alento-deep">R$ 0,00</span>
          </div>
        </div>
      </div>

      <div class="flex flex-wrap items-center justify-between gap-3 bg-white border border-alento-border rounded-2xl p-4 shadow-card">
        <div>
          <h2 class="font-display font-semibold text-xl text-alento-dark">Bancada de Encomendas .alento.</h2>
          <p class="text-xs text-alento-muted">Acompanhe cada etapa, prazo, tamanho do bastidor e acerto financeiro.</p>
        </div>
        <div class="flex items-center gap-2.5 flex-wrap">
          <button onclick="toggleOrdersCalc()" class="inline-flex items-center gap-1.5 px-4 py-2.5 rounded-full bg-alento-soft hover:bg-alento-border/60 text-alento-deep border border-alento-border text-xs font-semibold transition-colors cursor-pointer">
            <span>🧮</span> <span id="btnToggleOrdersCalcText">Calculadora de Preço</span>
          </button>
          <button onclick="openOrderModal()" class="inline-flex items-center gap-1.5 px-4 py-2.5 rounded-full bg-alento-coral hover:bg-alento-deep text-white text-xs font-semibold transition-colors shadow-sm cursor-pointer">
            <span class="text-base leading-none">+</span> Nova Encomenda
          </button>
        </div>
      </div>

      <!-- Calculadora de Precificação -->
      <div id="ordersCalculatorPanel" class="bg-alento-soft/75 border-2 border-alento-coral/35 rounded-3xl p-5 shadow-card">
        <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
          <div class="flex items-center gap-2">
            <span class="w-8 h-8 rounded-full bg-alento-coral text-white flex items-center justify-center text-sm shadow-sm">🧮</span>
            <div>
              <h3 class="font-display font-semibold text-base text-alento-dark">Calculadora de Precificação</h3>
              <p class="text-[11px] text-alento-muted">Preço Final = (Materiais + Mão de Obra + Custo Fixo) × (1 + % Lucro)</p>
            </div>
          </div>
          <div class="flex items-center gap-3">
            <button onclick="resetPriceCalc()" class="text-[11px] font-semibold text-alento-deep hover:underline cursor-pointer">Limpar</button>
            <button onclick="toggleOrdersCalc()" class="text-xs text-alento-muted hover:text-alento-dark cursor-pointer">Ocultar ✕</button>
          </div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
          <div class="lg:col-span-7 grid grid-cols-2 sm:grid-cols-3 gap-3 text-xs">
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Materiais (R$)</label>
              <input id="calcMaterials" type="number" min="0" step="0.5" value="25" oninput="calculateAlentoPrice()" class="w-full rounded-xl border border-alento-border bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-alento-coral" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Custo Fixo / Rateio (R$)</label>
              <input id="calcFixed" type="number" min="0" step="0.5" value="10" oninput="calculateAlentoPrice()" class="w-full rounded-xl border border-alento-border bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-alento-coral" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Horas Bordadas</label>
              <input id="calcHours" type="number" min="0" step="0.5" value="4" oninput="calculateAlentoPrice()" class="w-full rounded-xl border border-alento-border bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-alento-coral" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Valor da Sua Hora (R$)</label>
              <input id="calcHourlyRate" type="number" min="0" step="1" value="25" oninput="calculateAlentoPrice()" class="w-full rounded-xl border border-alento-border bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-alento-coral" />
            </div>
            <div class="col-span-2">
              <div class="flex items-center justify-between mb-1">
                <label class="text-[11px] font-semibold text-alento-muted">Percentual de Lucro (%)</label>
                <span id="calcMarginBadge" class="text-[11px] font-bold text-alento-deep bg-white px-2 py-0.5 rounded-full border border-alento-border">30%</span>
              </div>
              <input id="calcMargin" type="range" min="0" max="150" step="5" value="30" oninput="calculateAlentoPrice()" class="w-full accent-[#FF6F61] cursor-pointer mt-1.5" />
            </div>
          </div>

          <div class="lg:col-span-5 bg-white rounded-2xl p-4 border border-alento-border flex flex-col justify-between gap-3">
            <div class="flex items-center justify-between text-xs text-alento-muted border-b border-alento-border/60 pb-2">
              <div>
                <span>Mão de Obra: <strong id="calcLaborTotal" class="text-alento-dark">R$ 100,00</strong></span>
                <span class="mx-1.5">•</span>
                <span>Base: <strong id="calcBaseCost" class="text-alento-dark">R$ 135,00</strong></span>
              </div>
              <span>Lucro: <strong id="calcProfitValue" class="text-emerald-700">+ R$ 40,50</strong></span>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-2">
              <div>
                <span class="text-[10px] uppercase tracking-wider font-semibold text-alento-muted block">Preço Final Sugerido</span>
                <span id="calcFinalPrice" class="font-display font-semibold text-2xl text-alento-coral">R$ 175,50</span>
              </div>
              <button onclick="createOrderFromCalc()" class="px-3.5 py-2 rounded-full bg-alento-coral hover:bg-alento-deep text-white text-xs font-semibold transition-colors shadow-sm cursor-pointer">
                + Criar Pedido com este Valor
              </button>
            </div>
          </div>
        </div>
      </div>

      <!-- Fluxo Kanban -->
      <div id="ordersKanbanBoard" class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-5 gap-4 items-start"></div>
    </section>

    <!-- VISÃO 4: PROJETO SATÉLITE -->
    <section id="viewSatellite" class="hidden space-y-6">
      <div class="bg-white border border-alento-border rounded-3xl p-5 sm:p-6 shadow-card flex flex-wrap items-center justify-between gap-4">
        <div class="max-w-2xl">
          <div class="flex items-center gap-2 mb-1.5">
            <span class="px-2.5 py-0.5 rounded-full bg-amber-100 text-amber-800 border border-amber-200 text-[11px] font-semibold">
              Frente Paralela • Giro Rápido & Rua
            </span>
            <span class="text-xs text-alento-muted">Separado do posicionamento principal da .alento.</span>
          </div>
          <h2 class="font-display font-semibold text-2xl text-alento-dark">Projeto Satélite — Miniaturas & Pronta Entrega</h2>
          <p class="text-xs sm:text-sm text-alento-muted mt-1 leading-relaxed">
            Espaço dedicado para girar seu estoque de bases pequenas (chaveiros de 5 cm e vidrinhos de 3 a 3,5 cm) em vendas rápidas na rua, gerando renda extra leve sem misturar com as peças autorais e sob encomenda da <strong>.alento.</strong>.
          </p>
        </div>

        <div class="flex items-center gap-2.5 flex-wrap">
          <button onclick="toggleSatCalc()" class="inline-flex items-center gap-1.5 px-4 py-2.5 rounded-full bg-amber-50 hover:bg-amber-100 text-amber-900 border border-amber-200 text-xs font-semibold transition-colors cursor-pointer">
            <span>🧮</span> <span id="btnToggleSatCalcText">Calculadora de Valor</span>
          </button>
          <button onclick="openSatelliteItemModal()" class="inline-flex items-center gap-1.5 px-4 py-2.5 rounded-full bg-alento-dark hover:bg-alento-deep text-white text-xs font-semibold transition-colors shadow-sm cursor-pointer">
            <span class="text-base leading-none">+</span> Novo Item de Lote
          </button>
        </div>
      </div>

      <!-- Calculadora de Valor Unitário -->
      <div id="satCalculatorPanel" class="bg-amber-50/70 border-2 border-amber-300/70 rounded-3xl p-5 shadow-card">
        <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
          <div class="flex items-center gap-2">
            <span class="w-8 h-8 rounded-full bg-amber-500 text-white flex items-center justify-center text-sm shadow-sm">🧮</span>
            <div>
              <h3 class="font-display font-semibold text-base text-alento-dark">Calculadora de Valor — Projeto Satélite</h3>
              <p class="text-[11px] text-alento-muted">Preço Unitário = (Materiais + Embalagem + Mão de Obra) × (1 + % Lucro)</p>
            </div>
          </div>
          <div class="flex items-center gap-3">
            <button onclick="resetSatCalc()" class="text-[11px] font-semibold text-amber-800 hover:underline cursor-pointer">Limpar</button>
            <button onclick="toggleSatCalc()" class="text-xs text-alento-muted hover:text-alento-dark cursor-pointer">Ocultar ✕</button>
          </div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
          <div class="lg:col-span-7 grid grid-cols-2 sm:grid-cols-3 gap-3 text-xs">
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Base + Linha (R$)</label>
              <input id="satCalcMaterials" type="number" min="0" step="0.5" value="6" oninput="calculateSatellitePrice()" class="w-full rounded-xl border border-amber-200 bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-amber-500" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Embalagem / Tag (R$)</label>
              <input id="satCalcFixed" type="number" min="0" step="0.5" value="2" oninput="calculateSatellitePrice()" class="w-full rounded-xl border border-amber-200 bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-amber-500" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Tempo por Peça (h)</label>
              <input id="satCalcHours" type="number" min="0" step="0.1" value="0.8" oninput="calculateSatellitePrice()" class="w-full rounded-xl border border-amber-200 bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-amber-500" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Valor da Hora (R$)</label>
              <input id="satCalcHourlyRate" type="number" min="0" step="1" value="20" oninput="calculateSatellitePrice()" class="w-full rounded-xl border border-amber-200 bg-white px-3 py-2 text-alento-dark font-medium focus:outline-none focus:border-amber-500" />
            </div>
            <div class="col-span-2">
              <div class="flex items-center justify-between mb-1">
                <label class="text-[11px] font-semibold text-alento-muted">Percentual de Lucro (%)</label>
                <span id="satCalcMarginBadge" class="text-[11px] font-bold text-amber-900 bg-white px-2 py-0.5 rounded-full border border-amber-200">45%</span>
              </div>
              <input id="satCalcMargin" type="range" min="0" max="150" step="5" value="45" oninput="calculateSatellitePrice()" class="w-full accent-amber-600 cursor-pointer mt-1.5" />
            </div>
          </div>

          <div class="lg:col-span-5 bg-white rounded-2xl p-4 border border-amber-200 flex flex-col justify-between gap-3">
            <div class="flex items-center justify-between text-xs text-alento-muted border-b border-amber-100 pb-2">
              <div>
                <span>Mão de Obra: <strong id="satCalcLaborTotal" class="text-alento-dark">R$ 16,00</strong></span>
                <span class="mx-1.5">•</span>
                <span>Custo: <strong id="satCalcBaseCost" class="text-alento-dark">R$ 24,00</strong></span>
              </div>
              <span>Lucro: <strong id="satCalcProfitValue" class="text-emerald-700">+ R$ 10,80</strong></span>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-2">
              <div>
                <span class="text-[10px] uppercase tracking-wider font-semibold text-alento-muted block">Preço Unitário Sugerido</span>
                <span id="satCalcFinalPrice" class="font-display font-semibold text-2xl text-amber-700">R$ 34,80</span>
              </div>
              <div class="flex items-center gap-1.5">
                <select id="satCalcTargetSelect" class="rounded-full border border-amber-200 bg-amber-50/60 px-2.5 py-2 text-[11px] text-alento-dark font-medium focus:outline-none">
                  <option value="chaveiro-5cm">Chaveiro 5cm</option>
                  <option value="vidrinho-3cm">Vidrinho 3–3,5cm</option>
                </select>
                <button onclick="applySatCalcToItem()" class="px-3 py-2 rounded-full bg-amber-600 hover:bg-amber-700 text-white text-xs font-semibold transition-colors shadow-sm cursor-pointer">
                  Aplicar Preço
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Resumo de Estoque e Vendas -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
        <div class="bg-white border border-alento-border rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-alento-muted block">Bases Virgens</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="satStatRaw" class="font-display font-semibold text-2xl sm:text-3xl text-alento-dark">97</span>
            <span class="text-xs text-alento-muted">para bordar</span>
          </div>
        </div>
        <div class="bg-amber-50/70 border border-amber-200 rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-amber-800 block">Prontas p/ Rua</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="satStatReady" class="font-display font-semibold text-2xl sm:text-3xl text-amber-800">0</span>
            <span class="text-xs text-amber-700">no estoque</span>
          </div>
        </div>
        <div class="bg-white border border-alento-border rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-alento-muted block">Unidades Vendidas</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="satStatSold" class="font-display font-semibold text-2xl sm:text-3xl text-alento-dark">0</span>
            <span class="text-xs text-alento-muted">na rua</span>
          </div>
        </div>
        <div class="bg-emerald-50/70 border border-emerald-200 rounded-2xl p-4 shadow-card">
          <span class="text-[11px] font-semibold uppercase tracking-wider text-emerald-800 block">Caixa Extra Gerado</span>
          <div class="flex items-baseline gap-2 mt-1">
            <span id="satStatRevenue" class="font-display font-semibold text-2xl sm:text-3xl text-emerald-700">R$ 0,00</span>
          </div>
        </div>
      </div>

      <!-- Cards de Estoque -->
      <div id="satelliteItemsContainer" class="grid grid-cols-1 md:grid-cols-2 gap-5"></div>

      <!-- Diretrizes & Brainstorm -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
        <div class="lg:col-span-5 bg-alento-soft/70 border border-alento-border rounded-3xl p-5 space-y-3">
          <h3 class="font-display font-semibold text-base text-alento-dark flex items-center gap-2">
            <span class="text-alento-coral">✳</span> Regras de Ouro do Projeto Satélite
          </h3>
          <ul class="space-y-2 text-xs text-alento-dark leading-relaxed">
            <li class="flex items-start gap-2">
              <span class="text-alento-coral font-bold">•</span>
              <span><strong>Sem contaminar a marca mãe:</strong> não misturar preços de rua no feed principal do <code>@alento.</code>; use tag simples de <em>feito à mão</em> ou expositor próprio.</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-alento-coral font-bold">•</span>
              <span><strong>Produção em lote leve:</strong> bordar nos intervalos livres usando sobras de meadas para maximizar a margem.</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-alento-coral font-bold">•</span>
              <span><strong>Reinvestimento inteligente:</strong> parte do lucro vai direto para financiar bastidores maiores, tecidos e embalagens da <strong>.alento.</strong>.</span>
            </li>
          </ul>
        </div>

        <div class="lg:col-span-7 bg-white border border-alento-border rounded-3xl p-5 shadow-card space-y-3">
          <h3 class="font-display font-semibold text-base text-alento-dark">Brainstorm & Pendências do Satélite</h3>
          <div id="satelliteNotesList" class="space-y-2"></div>
          <div class="flex gap-2 pt-1">
            <input id="satelliteNoteInput" type="text" placeholder="Ex: Contar vidrinhos na caixa, testar mini flores ou patinhas..." class="flex-1 text-xs rounded-xl border border-alento-border bg-alento-cream px-3 py-2.5 focus:outline-none focus:border-alento-coral" onkeydown="if(event.key==='Enter') addSatelliteNote()" />
            <button onclick="addSatelliteNote()" class="px-4 py-2.5 rounded-xl bg-alento-coral hover:bg-alento-deep text-white text-xs font-semibold transition-colors cursor-pointer">
              Salvar
            </button>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- Painel Lateral de Detalhes (Drawer) -->
  <div id="drawerOverlay" onclick="closeDrawer()" class="fixed inset-0 bg-alento-dark/35 backdrop-blur-xs z-40 hidden transition-opacity"></div>
  <aside id="detailDrawer" class="fixed top-0 right-0 h-full w-full max-w-lg bg-white border-l border-alento-border shadow-2xl z-50 transform translate-x-full transition-transform duration-300 flex flex-col">
    <div class="px-6 py-5 bg-alento-soft border-b border-alento-border flex items-start justify-between gap-4">
      <div>
        <div class="flex items-center gap-2">
          <span id="drawerBadge" class="text-[11px] font-semibold uppercase tracking-wider px-2.5 py-0.5 rounded-full bg-alento-coral text-white">Pilar</span>
          <span id="drawerSubtitle" class="text-xs text-alento-muted">Essência</span>
        </div>
        <h3 id="drawerTitle" class="font-display font-semibold text-2xl text-alento-dark mt-1.5 leading-snug">Título do Pilar</h3>
      </div>
      <button onclick="closeDrawer()" class="p-2 rounded-full bg-white hover:bg-alento-coral hover:text-white text-alento-dark border border-alento-border transition-colors cursor-pointer">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
        </svg>
      </button>
    </div>

    <div id="drawerBody" class="flex-1 overflow-y-auto p-6 space-y-6"></div>

    <div id="drawerFooter" class="p-4 bg-alento-cream border-t border-alento-border">
      <label class="block text-xs font-semibold text-alento-dark mb-1.5">Adicionar nova ideia ou anotação neste pilar:</label>
      <div class="flex gap-2">
        <input id="drawerNewNoteInput" type="text" placeholder="Ex: Ideia de embalagem, frase ou referência..." class="flex-1 text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral" onkeydown="if(event.key==='Enter') addNoteToCurrentNode()" />
        <button onclick="addNoteToCurrentNode()" class="px-4 py-2 rounded-xl bg-alento-coral hover:bg-alento-deep text-white text-sm font-medium transition-colors cursor-pointer">
          Salvar
        </button>
      </div>
    </div>
  </aside>

  <!-- Modal: Ideia Solta Rápida -->
  <div id="quickIdeaModal" class="fixed inset-0 bg-alento-dark/40 backdrop-blur-xs z-50 hidden items-center justify-center p-4">
    <div class="bg-white rounded-3xl border border-alento-border max-w-md w-full p-6 shadow-2xl">
      <div class="flex items-center justify-between mb-4">
        <div class="flex items-center gap-2">
          <span class="w-7 h-7 rounded-full bg-alento-soft text-alento-coral flex items-center justify-center font-bold">✳</span>
          <h3 class="font-display font-semibold text-xl text-alento-dark">Guardar Ideia Solta</h3>
        </div>
        <button onclick="closeQuickIdeaModal()" class="text-alento-muted hover:text-alento-dark cursor-pointer">✕</button>
      </div>
      <div class="space-y-4">
        <div>
          <label class="block text-xs font-semibold text-alento-dark mb-1">Em qual pilar essa ideia se encaixa?</label>
          <select id="quickIdeaNodeSelect" class="w-full text-sm rounded-xl border border-alento-border bg-alento-cream px-3 py-2.5 focus:outline-none focus:border-alento-coral"></select>
        </div>
        <div>
          <label class="block text-xs font-semibold text-alento-dark mb-1">Qual é a ideia?</label>
          <textarea id="quickIdeaText" rows="3" placeholder="Escreva livremente o que veio à mente..." class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2.5 focus:outline-none focus:border-alento-coral"></textarea>
        </div>
        <div class="flex justify-end gap-2 pt-2">
          <button onclick="closeQuickIdeaModal()" class="px-4 py-2 rounded-xl text-xs font-medium text-alento-muted hover:bg-alento-soft cursor-pointer">Cancelar</button>
          <button onclick="saveQuickIdea()" class="px-5 py-2 rounded-xl text-xs font-semibold bg-alento-coral hover:bg-alento-deep text-white shadow-sm cursor-pointer">Encaixar no Mapa</button>
        </div>
      </div>
    </div>
  </div>

  <!-- Modal: Nova / Editar Encomenda -->
  <div id="orderModal" class="fixed inset-0 bg-alento-dark/40 backdrop-blur-xs z-50 hidden items-center justify-center p-4">
    <div class="bg-white rounded-3xl border border-alento-border max-w-lg w-full p-6 shadow-2xl max-h-[92vh] overflow-y-auto">
      <div class="flex items-center justify-between mb-4">
        <div class="flex items-center gap-2">
          <span class="w-8 h-8 rounded-full bg-alento-soft text-alento-coral flex items-center justify-center font-bold">🪡</span>
          <h3 id="orderModalTitle" class="font-display font-semibold text-xl text-alento-dark">Nova Encomenda</h3>
        </div>
        <button onclick="closeOrderModal()" class="text-alento-muted hover:text-alento-dark cursor-pointer">✕</button>
      </div>

      <form onsubmit="saveOrderForm(event)" class="space-y-4 text-xs">
        <input type="hidden" id="orderIdInput" />
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Nome do Cliente *</label>
            <input id="orderClientInput" type="text" required placeholder="Ex: Marina & Theo" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral" />
          </div>
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Linha / Tipo de Peça *</label>
            <select id="orderCategoryInput" class="w-full text-sm rounded-xl border border-alento-border bg-alento-cream px-3 py-2 focus:outline-none focus:border-alento-coral">
              <option value="Pet / Retrato">Pet / Retrato</option>
              <option value="Releitura Afetiva">Releitura Afetiva</option>
              <option value="Bordado em Fotografia">Bordado em Fotografia</option>
              <option value="Coleção Autoral">Coleção Autoral</option>
            </select>
          </div>
        </div>

        <div>
          <label class="block font-semibold text-alento-dark mb-1">Tema / Descrição da História *</label>
          <input id="orderTitleInput" type="text" required placeholder="Ex: Retrato da cachorrinha Lola com flores silvestres" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral" />
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Tamanho Bastidor</label>
            <select id="orderHoopInput" class="w-full text-sm rounded-xl border border-alento-border bg-alento-cream px-3 py-2 focus:outline-none focus:border-alento-coral">
              <option value="12 cm">12 cm</option>
              <option value="14 cm">14 cm</option>
              <option value="16 cm" selected>16 cm</option>
              <option value="20 cm">20 cm</option>
              <option value="22 cm">22 cm</option>
              <option value="Outro">Outro</option>
            </select>
          </div>
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Prazo de Entrega *</label>
            <input id="orderDeadlineInput" type="date" required class="w-full text-sm rounded-xl border border-alento-border bg-white px-3 py-2 focus:outline-none focus:border-alento-coral" />
          </div>
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Etapa Atual</label>
            <select id="orderStageInput" class="w-full text-sm rounded-xl border border-alento-border bg-alento-cream px-3 py-2 focus:outline-none focus:border-alento-coral">
              <option value="orcamento">1. Orçamento/Aprovação</option>
              <option value="risco">2. Risco & Materiais</option>
              <option value="bordando">3. Bordando</option>
              <option value="acabamento">4. Acabamento & Embalagem</option>
              <option value="entregue">5. Entregue</option>
            </select>
          </div>
        </div>

        <div class="bg-alento-soft/70 border border-alento-border rounded-2xl p-3.5 space-y-3">
          <div class="flex items-center justify-between">
            <span class="font-semibold text-alento-dark">Controle Financeiro</span>
            <button type="button" onclick="setHalfDeposit()" class="text-[11px] font-semibold text-alento-deep hover:underline cursor-pointer">
              Calcular 50% de Sinal
            </button>
          </div>
          <div class="grid grid-cols-2 gap-3">
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Valor Total (R$) *</label>
              <input id="orderTotalInput" type="number" min="0" step="0.5" required placeholder="180.00" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3 py-2 font-semibold text-alento-dark focus:outline-none focus:border-alento-coral" />
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-alento-muted mb-1">Sinal Pago (R$)</label>
              <input id="orderDepositInput" type="number" min="0" step="0.5" placeholder="90.00" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3 py-2 font-semibold text-emerald-700 focus:outline-none focus:border-alento-coral" />
            </div>
          </div>
        </div>

        <div>
          <label class="block font-semibold text-alento-dark mb-1">Observações de Cores, Tecido ou Entrega</label>
          <textarea id="orderNotesInput" rows="2" placeholder="Ex: Algodão cru, paleta terrosa com Living Coral, envio via Correios..." class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral"></textarea>
        </div>

        <div class="flex items-center justify-between pt-2">
          <button type="button" id="btnDeleteOrder" onclick="deleteCurrentOrder()" class="hidden px-3.5 py-2 rounded-xl text-xs font-semibold text-red-600 hover:bg-red-50 cursor-pointer">
            Excluir Pedido
          </button>
          <div class="flex items-center gap-2 ml-auto">
            <button type="button" onclick="closeOrderModal()" class="px-4 py-2 rounded-xl text-xs font-medium text-alento-muted hover:bg-alento-soft cursor-pointer">Cancelar</button>
            <button type="submit" class="px-5 py-2.5 rounded-xl text-xs font-semibold bg-alento-coral hover:bg-alento-deep text-white shadow-sm cursor-pointer">Salvar Encomenda</button>
          </div>
        </div>
      </form>
    </div>
  </div>

  <!-- Modal: Editar / Novo Item do Projeto Satélite -->
  <div id="satelliteModal" class="fixed inset-0 bg-alento-dark/40 backdrop-blur-xs z-50 hidden items-center justify-center p-4">
    <div class="bg-white rounded-3xl border border-alento-border max-w-md w-full p-6 shadow-2xl">
      <div class="flex items-center justify-between mb-4">
        <div class="flex items-center gap-2">
          <span class="w-8 h-8 rounded-full bg-amber-100 text-amber-800 flex items-center justify-center font-bold">✦</span>
          <h3 id="satModalTitle" class="font-display font-semibold text-xl text-alento-dark">Item do Projeto Satélite</h3>
        </div>
        <button onclick="closeSatelliteModal()" class="text-alento-muted hover:text-alento-dark cursor-pointer">✕</button>
      </div>

      <form onsubmit="saveSatelliteItemForm(event)" class="space-y-3.5 text-xs">
        <input type="hidden" id="satIdInput" />
        <div>
          <label class="block font-semibold text-alento-dark mb-1">Nome da Base / Produto *</label>
          <input id="satNameInput" type="text" required placeholder="Ex: Chaveiro Bastidor Mini (5 cm)" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral" />
        </div>

        <div class="grid grid-cols-2 gap-3">
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Medida / Formato</label>
            <input id="satSizeInput" type="text" placeholder="Ex: 5 cm" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral" />
          </div>
          <div>
            <label class="block font-semibold text-alento-dark mb-1">Preço de Venda (R$)</label>
            <input id="satPriceInput" type="number" min="0" step="0.5" placeholder="35.00" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 font-semibold text-alento-dark focus:outline-none focus:border-alento-coral" />
          </div>
        </div>

        <div class="grid grid-cols-3 gap-2.5 bg-alento-soft/60 p-3 rounded-2xl border border-alento-border">
          <div>
            <label class="block text-[11px] font-semibold text-alento-muted mb-1">Bases Virgens</label>
            <input id="satRawInput" type="number" min="0" step="1" value="0" class="w-full text-sm rounded-xl border border-alento-border bg-white px-2.5 py-1.5 font-semibold text-alento-dark" />
          </div>
          <div>
            <label class="block text-[11px] font-semibold text-amber-800 mb-1">Prontas (Rua)</label>
            <input id="satReadyInput" type="number" min="0" step="1" value="0" class="w-full text-sm rounded-xl border border-alento-border bg-white px-2.5 py-1.5 font-semibold text-amber-800" />
          </div>
          <div>
            <label class="block text-[11px] font-semibold text-emerald-800 mb-1">Vendidas</label>
            <input id="satSoldInput" type="number" min="0" step="1" value="0" class="w-full text-sm rounded-xl border border-alento-border bg-white px-2.5 py-1.5 font-semibold text-emerald-700" />
          </div>
        </div>

        <div>
          <label class="block font-semibold text-alento-dark mb-1">Histórico / Observação de Estoque</label>
          <input id="satDescInput" type="text" placeholder="Ex: 100 comprados (1 presente + 2 testes próprios = 97 livres)" class="w-full text-sm rounded-xl border border-alento-border bg-white px-3.5 py-2 focus:outline-none focus:border-alento-coral" />
        </div>

        <div class="flex items-center justify-end gap-2 pt-2">
          <button type="button" onclick="closeSatelliteModal()" class="px-4 py-2 rounded-xl text-xs font-medium text-alento-muted hover:bg-alento-soft cursor-pointer">Cancelar</button>
          <button type="submit" class="px-5 py-2.5 rounded-xl text-xs font-semibold bg-alento-coral hover:bg-alento-deep text-white shadow-sm cursor-pointer">Salvar Item</button>
        </div>
      </form>
    </div>
  </div>

  <!-- Toast de Feedback -->
  <div id="toast" class="fixed bottom-5 left-1/2 -translate-x-1/2 z-50 bg-alento-dark text-white text-xs font-medium px-4 py-2.5 rounded-full shadow-lg opacity-0 pointer-events-none transition-opacity duration-300">
    Ideia salva no mapa!
  </div>

  <!-- Modal: Guia Rápido de Instalação no Celular -->
  <div id="appInstallModal" class="fixed inset-0 bg-alento-dark/40 backdrop-blur-xs z-50 hidden items-center justify-center p-4">
    <div class="bg-white rounded-3xl border border-alento-border max-w-md w-full p-6 shadow-2xl space-y-4">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-2.5">
          <div class="w-9 h-9 rounded-2xl bg-alento-coral text-white font-display font-semibold flex items-center justify-center text-base shadow-xs">.a.</div>
          <div>
            <h3 class="font-display font-semibold text-lg text-alento-dark leading-tight">Ter a .alento. no Celular</h3>
            <p class="text-[11px] text-alento-muted">Funciona como aplicativo em tela cheia</p>
          </div>
        </div>
        <button onclick="closeAppInstallGuide()" class="text-alento-muted hover:text-alento-dark cursor-pointer">✕</button>
      </div>

      <div class="space-y-3 text-xs text-alento-dark leading-relaxed">
        <div class="bg-alento-soft/80 border border-alento-border rounded-2xl p-3.5">
          <p class="font-semibold text-alento-deep mb-1">1. Colocar online (1 minuto e gratuito)</p>
          <p class="text-alento-muted">Baixe este arquivo <code>index.html</code> e arraste-o para dentro do site <strong>app.netlify.com/drop</strong> (ou GitHub Pages / Vercel). Ele gera o link do seu app na hora.</p>
        </div>

        <div class="bg-alento-cream border border-alento-border rounded-2xl p-3.5 space-y-2">
          <p class="font-semibold text-alento-dark">2. Instalar o ícone .a. na tela inicial</p>
          <p><strong>iPhone (Safari):</strong> Abra o link → toque em <em>Compartilhar</em> (quadrado com seta) → <em>Adicionar à Tela de Início</em>.</p>
          <p><strong>Android (Chrome):</strong> Abra o link → toque nos <em>3 pontinhos (⋮)</em> → <em>Adicionar à tela inicial</em> ou <em>Instalar aplicativo</em>.</p>
        </div>

        <div id="nativeInstallPromptBox" class="hidden pt-1">
          <button onclick="triggerNativeInstall()" class="w-full py-2.5 rounded-full bg-alento-coral hover:bg-alento-deep text-white font-semibold text-xs shadow-sm cursor-pointer">
            Instalar Agora neste Dispositivo
          </button>
        </div>
      </div>

      <div class="flex justify-end pt-1">
        <button onclick="closeAppInstallGuide()" class="px-5 py-2 rounded-full bg-alento-dark text-white text-xs font-semibold cursor-pointer">Entendi</button>
      </div>
    </div>
  </div>

  <script>
    const STORAGE_KEY = 'alento_brand_mindmap_v5_fix';
    const ORDERS_STORAGE_KEY = 'alento_orders_v1';
    const SATELLITE_STORAGE_KEY = 'alento_satellite_v1';

    const DEFAULT_DATA = {
      central: {
        name: '.alento.',
        tagline: 'bordado feito à mão',
        meaning: 'Fôlego novo, ânimo e recomeço. Aquilo que suaviza uma dor ou oferece um respiro em momentos difíceis — uma brisa suave e um abraço que acolhe e conforta o coração.',
        manifesto: 'O bordado é a pausa intencional onde o fio acompanha o tempo do sentir. Cada ponto é feito à mão, sem pressa, para eternizar memórias afetivas, homenagear laços verdadeiros e levar conforto a quem recebe.',
        resistanceQuote: '“Porque eu resisto. E toda a minha história existe.” — Enquanto estou criando, me faz sentir sentido.',
        palette: [
          { name: 'Living Coral (Principal)', hex: '#FF6F61', pantone: 'Pantone 16-1546' },
          { name: 'Coral Profundo (Acento)', hex: '#E2493B', pantone: 'Tom Secundário' },
          { name: 'Rosado Suave (Fundo)', hex: '#FFF3F1', pantone: 'Superfície' },
          { name: 'Café Acolhedor (Texto)', hex: '#3A2420', pantone: 'Tipografia' }
        ],
        typography: 'Fraunces SemiBold / Medium (logotipo e títulos afetivos) + Figtree Regular / Medium (textos e comunicação).'
      },
      nodes: [
        {
          id: 'essencia',
          number: '01',
          title: 'Essência, 5 Valores & Propósito',
          subtitle: 'Raízes, postura e identidade',
          position: { top: '8%', left: '2%' },
          summary: 'Os 5 valores oficiais da .alento., o propósito de resistência, a metáfora da brisa e do abraço e a herança afetiva do fazer manual.',
          sections: [
            {
              heading: 'Significado & Metáfora Central',
              items: [
                'Fôlego novo, ânimo e recomeço — conforto emocional e alívio que suavizam dores e trazem respiro.',
                'Duas imagens-guia: uma brisa suave e um abraço acolhedor (uma memória bonita que abraça).',
                'Raízes afetivas: herança familiar com a mãe tecendo na sala e trocas silenciosas com a irmã Eliane.'
              ]
            },
            {
              heading: 'Os 5 Valores Oficiais da .alento.',
              items: [
                'Memória Afetiva: bordados como recipientes de histórias, vínculos e lembranças.',
                'Presença: conexão verdadeira com o momento presente, sem aceleração.',
                'Ancestralidade: continuidade dos fazeres manuais transmitidos entre gerações.',
                'Tempo Desacelerado: recusa da lógica da urgência; não existe atalho, existe o próximo ponto.',
                'Acolhimento & Escuta: receber histórias e sentimentos sem julgamento e transformá-los em matéria visível.'
              ]
            },
            {
              heading: 'Propósito & Identidade',
              items: [
                '“Porque eu resisto. E toda a minha história existe.” — Existir e criar preservando sensibilidade, delicadeza e afeto.',
                'Slogan institucional: “bordado feito à mão” (sempre em caixa baixa).'
              ]
            }
          ],
          notes: []
        },
        {
          id: 'valor',
          number: '02',
          title: 'Proposta de Valor, Escuta & Preço',
          subtitle: 'Diferenciais e precificação',
          position: { top: '8%', left: '72%' },
          summary: 'A escuta ativa herdada da veterinária como diferencial real, as perguntas-bússola e a precificação de construção de negócio.',
          sections: [
            {
              heading: 'Diferencial Real: Escuta Ativa',
              items: [
                'Herança da veterinária: perceber vínculos familiares, afetos e o que está por trás do que é dito.',
                'O bordado é consequência da escuta — mesmo quando o presente é para um desconhecido, o vínculo nasce com quem encomenda.',
                'Acabamento minucioso, pintura com agulha e embalagens com aroma leve e carta manuscrita.'
              ]
            },
            {
              heading: 'Perguntas-Bússola de Pesquisa',
              items: [
                '“Se a pessoa não estivesse comprando um bordado, o que ela estaria comprando no lugar?”',
                '“O que essa pessoa recebeu além de um bordado?” (perguntar a cada entrega).'
              ]
            },
            {
              heading: 'Fórmula & Construção de Negócio',
              items: [
                'Preço Final = (Materiais + Mão de Obra + Custo Fixo) × (1 + % Lucro).',
                'Sair do preço de custo para o preço de construção de negócio (financiando aprendizado, insumos e crescimento).',
                'Sinal de 50% na aprovação do risco + 50% na entrega.'
              ]
            }
          ],
          notes: []
        },
        {
          id: 'catalogo',
          number: '03',
          title: 'Linhas, Calendário & Futuro',
          subtitle: 'Catálogo, ciclos e visão 2031',
          position: { top: '39%', left: '1%' },
          summary: 'As frentes de criação da marca, os quatro ciclos anuais e as sementes de futuro imaginadas na Carta de 2031.',
          sections: [
            {
              heading: 'Categorias de Oferta',
              items: [
                'Bordados Afetivos Personalizados: histórias, vínculos, amizade, família e releituras.',
                'Memórias de Pets: retratos e homenagens unindo vivência veterinária e pintura com agulha.',
                'Bordados Autorais & Fotografia: corações conectados, estudos botânicos e fotos bordadas.'
              ]
            },
            {
              heading: 'Calendário Anual (4 Ciclos)',
              items: [
                'Jan–Mar: Alento & Renovação (flores silvestres, frases de recomeço).',
                'Abr–Jun: Laços & Memória (Dia das Mães e Namorados).',
                'Jul–Set: Aconchego & Cotidiano (tons terrosos e botânica).',
                'Out–Dez: Afeto & Presentear (encomendas de Natal e homenagens).'
              ]
            },
            {
              heading: 'Sementes de Futuro (Carta 2031)',
              items: [
                'Experiências compartilhadas: oficinas presenciais, encontros em cafés e kits de bordado.',
                'Comunidade & Impacto: oficinas com vagas gratuitas e rede de apoio para homens trans.',
                'Projeto autoral: exposição de fotografias de infância bordadas.'
              ]
            }
          ],
          notes: []
        },
        {
          id: 'publico',
          number: '04',
          title: 'Persona & Público-Alvo',
          subtitle: 'Para quem bordamos',
          position: { top: '39%', left: '73%' },
          summary: 'Pessoas que valorizam o tempo do fazer manual, buscam presentes com alma e enxergam valor no afeto.',
          sections: [
            {
              heading: 'Perfil Demográfico & Comportamental',
              items: [
                'Principalmente mulheres e pessoas LGBTQIA+ de 25 a 48 anos, urbanas e conectadas à arte e decoração afetiva.',
                'Tutores apaixonados por seus animais de estimação.',
                'Primeiras clientes e apoiadores que acreditam na jornada e querem ver o projeto crescer.'
              ]
            },
            {
              heading: 'Dores, Desejos & Vínculos',
              items: [
                'Cansaço de presentes genéricos e industriais sem história.',
                'Desejo de celebrar amizades, vínculos entre cidades, família, pets e identidade.',
                'Necessidade de eternizar memórias que tragam conforto e abraço visual.'
              ]
            }
          ],
          notes: []
        },
        {
          id: 'jornada',
          number: '05',
          title: 'Jornada, Canais & Equilíbrio',
          subtitle: 'Experiência e rotina sustentável',
          position: { top: '70%', left: '2%' },
          summary: 'Do primeiro contato ao unboxing, a comunicação como continuação da criação e o equilíbrio entre trabalho e vida.',
          sections: [
            {
              heading: 'Fluxo de Atendimento (5 Passos)',
              items: [
                '1. Escuta Afetiva (WhatsApp/DM): entender a história e o sentimento por trás do pedido.',
                '2. Proposta & Sinal: definição de bastidor (12 a 22 cm) e pagamento de 50%.',
                '3. Risco & Paleta: envio do esboço para aprovação.',
                '4. Bastidores: registros do processo (stories e fotos do avesso limpo).',
                '5. Unboxing Sensorial: embalagem + cartão + guia de cuidados.'
              ]
            },
            {
              heading: 'Comunicação & Equilíbrio (2031)',
              items: [
                'Instagram @alento. e WhatsApp Business como canais principais.',
                'Comunicação como continuação da criação: contar a história por trás da peça, não só mostrar o ponto.',
                'Limite saudável: transição gradual da veterinária garantindo tempo para viver, descansar e criar.'
              ]
            }
          ],
          notes: []
        },
        {
          id: 'identidade',
          number: '06',
          title: 'Identidade Visual & Tom de Voz',
          subtitle: 'Manual da Marca',
          position: { top: '70%', left: '72%' },
          summary: 'Diretrizes visuais, verbalidade acolhedora e regras de aplicação do Manual de Identidade.',
          sections: [
            {
              heading: 'Sistema Visual',
              items: [
                'Logotipo “.alento.” entre pontos em Fraunces SemiBold + assinatura “bordado feito à mão”.',
                'Símbolo reduzido “.a.” para avatares, selos e lacres.',
                'Cor protagonista: Living Coral (#FF6F61) sobre fundos claros e respirados.'
              ]
            },
            {
              heading: 'Tom de Voz & Escrita',
              items: [
                'Calmo, próximo, poético sem ser rebuscado, acolhedor e humano.',
                'Palavras-chave: respiro, pausa, fio, afeto, memória, tempo, cuidado.'
              ]
            }
          ],
          notes: []
        }
      ]
    };

    const DEFAULT_ORDERS = [
      {
        id: 'ord-1',
        client: 'Camila & Pipoca',
        category: 'Pet / Retrato',
        title: 'Retrato realista da vira-lata Pipoca com ramo de lavanda',
        hoop: '16 cm',
        deadline: new Date(Date.now() + 8 * 86400000).toISOString().split('T')[0],
        stage: 'bordando',
        total: 185,
        deposit: 92.5,
        notes: 'Algodão cru, foco nas orelhinhas caídas e olhos caramelo.'
      },
      {
        id: 'ord-2',
        client: 'Lucas Martins',
        category: 'Releitura Afetiva',
        title: 'Casa da avó com frase “Onde o tempo anda devagar”',
        hoop: '20 cm',
        deadline: new Date(Date.now() + 15 * 86400000).toISOString().split('T')[0],
        stage: 'risco',
        total: 220,
        deposit: 110,
        notes: 'Presente de aniversário para a mãe.'
      }
    ];

    const DEFAULT_SATELLITE = {
      items: [
        {
          id: 'chaveiro-5cm',
          name: 'Chaveiro Bastidor Mini',
          size: '5 cm',
          price: 35,
          rawStock: 97,
          readyStock: 0,
          soldCount: 0,
          description: '100 bases compradas inicialmente (1 dado de presente + 2 testes próprios = 97 livres para bordar).'
        },
        {
          id: 'vidrinho-3cm',
          name: 'Pingente / Chaveiro Vidrinho',
          size: '3 a 3,5 cm',
          price: 30,
          rawStock: 0,
          readyStock: 0,
          soldCount: 0,
          description: 'Vidrinhos pequenos em estoque (pendente contagem exata na caixa para atualizar aqui).'
        }
      ],
      notes: [
        { id: 'sn-1', text: 'Contar exatamente quantos vidrinhos de 3 a 3,5 cm tem na caixa e atualizar o estoque acima.', done: false },
        { id: 'sn-2', text: 'Definir 4 ou 5 riscos rápidos de até 40 min para produção em lote (mini flores, corações, patinhas, iniciais).', done: false }
      ]
    };

    const ORDER_STAGES = [
      { id: 'orcamento', label: '1. Orçamento', badgeClass: 'bg-amber-100 text-amber-800 border-amber-200' },
      { id: 'risco', label: '2. Risco & Fios', badgeClass: 'bg-sky-100 text-sky-800 border-sky-200' },
      { id: 'bordando', label: '3. Bordando', badgeClass: 'bg-alento-soft text-alento-deep border-alento-border' },
      { id: 'acabamento', label: '4. Acabamento', badgeClass: 'bg-purple-100 text-purple-800 border-purple-200' },
      { id: 'entregue', label: '5. Entregue', badgeClass: 'bg-emerald-100 text-emerald-800 border-emerald-200' }
    ];

    let appData = loadData();
    let ordersData = loadOrders();
    let satelliteData = loadSatellite();
    let activeDrawerNodeId = null;
    let activeBoardFilter = 'all';

    function loadData() {
      try {
        const saved = localStorage.getItem(STORAGE_KEY);
        if (saved) return JSON.parse(saved);
      } catch (e) {}
      return JSON.parse(JSON.stringify(DEFAULT_DATA));
    }

    function saveData() {
      try {
        localStorage.setItem(STORAGE_KEY, JSON.stringify(appData));
      } catch (e) {}
    }

    function loadOrders() {
      try {
        const saved = localStorage.getItem(ORDERS_STORAGE_KEY);
        if (saved) return JSON.parse(saved);
      } catch (e) {}
      return JSON.parse(JSON.stringify(DEFAULT_ORDERS));
    }

    function saveOrders() {
      try {
        localStorage.setItem(ORDERS_STORAGE_KEY, JSON.stringify(ordersData));
      } catch (e) {}
      updateOrdersBadge();
    }

    function loadSatellite() {
      try {
        const saved = localStorage.getItem(SATELLITE_STORAGE_KEY);
        if (saved) return JSON.parse(saved);
      } catch (e) {}
      return JSON.parse(JSON.stringify(DEFAULT_SATELLITE));
    }

    function saveSatellite() {
      try {
        localStorage.setItem(SATELLITE_STORAGE_KEY, JSON.stringify(satelliteData));
      } catch (e) {}
    }

    function formatBRL(value) {
      return Number(value || 0).toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' });
    }

    function switchView(view) {
      const views = ['map', 'board', 'orders', 'satellite'];
      const viewEls = {
        map: document.getElementById('viewMap'),
        board: document.getElementById('viewBoard'),
        orders: document.getElementById('viewOrders'),
        satellite: document.getElementById('viewSatellite')
      };
      const btnEls = {
        map: document.getElementById('btnViewMap'),
        board: document.getElementById('btnViewBoard'),
        orders: document.getElementById('btnViewOrders'),
        satellite: document.getElementById('btnViewSatellite')
      };

      views.forEach((v) => {
        if (!viewEls[v] || !btnEls[v]) return;
        if (v === view) {
          viewEls[v].classList.remove('hidden');
          btnEls[v].className = 'px-3.5 py-1.5 rounded-full bg-alento-coral text-white shadow-sm transition-all cursor-pointer flex items-center gap-1.5';
        } else {
          viewEls[v].classList.add('hidden');
          btnEls[v].className = 'px-3.5 py-1.5 rounded-full text-alento-muted hover:text-alento-dark transition-all cursor-pointer flex items-center gap-1.5';
        }
      });

      if (view === 'map') renderMindmapNodes();
      if (view === 'board') renderBoard();
      if (view === 'orders') renderOrdersView();
      if (view === 'satellite') renderSatelliteView();
    }

    function renderMindmapNodes() {
      const radialContainer = document.getElementById('radialNodesContainer');
      const mobileContainer = document.getElementById('mobileNodesContainer');
      if (!radialContainer || !mobileContainer) return;

      radialContainer.innerHTML = '';
      mobileContainer.innerHTML = '';

      appData.nodes.forEach((node) => {
        const notesCount = node.notes ? node.notes.length : 0;

        const card = document.createElement('div');
        card.style.top = node.position.top;
        card.style.left = node.position.left;
        card.className = 'absolute w-[265px] bg-white/95 hover:bg-white rounded-2xl p-4 border border-alento-border hover:border-alento-coral shadow-card hover:shadow-soft transition-all cursor-pointer group z-10';
        card.onclick = () => openNodeDrawer(node.id);

        card.innerHTML = `
          <div class="flex items-center justify-between gap-2 mb-1.5">
            <span class="text-[11px] font-bold px-2 py-0.5 rounded-full bg-alento-soft text-alento-deep border border-alento-border">
              Pilar ${node.number}
            </span>
            <span class="text-[11px] text-alento-muted group-hover:text-alento-coral transition-colors font-medium">
              ${notesCount > 0 ? `+${notesCount} nota(s)` : 'Explorar →'}
            </span>
          </div>
          <h3 class="font-display font-semibold text-base text-alento-dark group-hover:text-alento-deep leading-snug">
            ${node.title}
          </h3>
          <p class="text-xs text-alento-muted mt-1 line-clamp-2 leading-relaxed">
            ${node.summary}
          </p>
        `;
        radialContainer.appendChild(card);

        const mCard = document.createElement('div');
        mCard.className = 'bg-white rounded-2xl p-4 border border-alento-border shadow-card cursor-pointer hover:border-alento-coral transition-all';
        mCard.onclick = () => openNodeDrawer(node.id);
        mCard.innerHTML = `
          <div class="flex items-center justify-between mb-1.5">
            <span class="text-[11px] font-bold px-2 py-0.5 rounded-full bg-alento-soft text-alento-deep">Pilar ${node.number}</span>
            <span class="text-[11px] text-alento-muted">${node.subtitle}</span>
          </div>
          <h3 class="font-display font-semibold text-base text-alento-dark">${node.title}</h3>
          <p class="text-xs text-alento-muted mt-1 leading-relaxed">${node.summary}</p>
        `;
        mobileContainer.appendChild(mCard);
      });
    }

    function renderBoard() {
      const chipsContainer = document.getElementById('boardFilterChips');
      const cardsContainer = document.getElementById('boardCardsContainer');
      if (!chipsContainer || !cardsContainer) return;

      chipsContainer.innerHTML = `
        <button onclick="setBoardFilter('all')" class="px-3 py-1 rounded-full text-xs font-medium cursor-pointer transition-colors ${activeBoardFilter === 'all' ? 'bg-alento-coral text-white' : 'bg-alento-soft text-alento-muted hover:text-alento-dark'}">
          Todos (6)
        </button>
      ` + appData.nodes.map((n) => `
        <button onclick="setBoardFilter('${n.id}')" class="px-3 py-1 rounded-full text-xs font-medium cursor-pointer transition-colors ${activeBoardFilter === n.id ? 'bg-alento-coral text-white' : 'bg-alento-soft text-alento-muted hover:text-alento-dark'}">
          ${n.number}. ${n.title.split('&')[0].trim()}
        </button>
      `).join('');

      const filtered = activeBoardFilter === 'all'
        ? appData.nodes
        : appData.nodes.filter((n) => n.id === activeBoardFilter);

      cardsContainer.innerHTML = filtered.map((node) => `
        <article class="bg-white rounded-3xl border border-alento-border p-5 shadow-card flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between gap-2 mb-2">
              <span class="text-xs font-bold px-2.5 py-0.5 rounded-full bg-alento-soft text-alento-deep border border-alento-border">
                Pilar ${node.number}
              </span>
              <span class="text-[11px] text-alento-muted">${node.subtitle}</span>
            </div>
            <h3 class="font-display font-semibold text-xl text-alento-dark mb-3">${node.title}</h3>
            <div class="space-y-3">
              ${node.sections.map((sec) => `
                <div class="bg-alento-cream rounded-2xl p-3 border border-alento-border/70">
                  <h4 class="text-xs font-semibold text-alento-deep mb-1.5">${sec.heading}</h4>
                  <ul class="space-y-1 text-xs text-alento-dark leading-relaxed">
                    ${sec.items.map((it) => `<li class="flex items-start gap-1.5"><span class="text-alento-coral font-bold">•</span><span>${it}</span></li>`).join('')}
                  </ul>
                </div>
              `).join('')}
            </div>
          </div>
          <div class="mt-4 pt-3 border-t border-alento-border flex items-center justify-between">
            <span class="text-[11px] text-alento-muted">${node.notes.length} anotação(ões)</span>
            <button onclick="openNodeDrawer('${node.id}')" class="text-xs font-semibold text-alento-coral hover:text-alento-deep cursor-pointer">
              Editar / Adicionar Nota →
            </button>
          </div>
        </article>
      `).join('');
    }

    function setBoardFilter(filterId) {
      activeBoardFilter = filterId;
      renderBoard();
    }

    function openCentralManifesto() {
      activeDrawerNodeId = 'central';
      document.getElementById('drawerBadge').textContent = 'Núcleo da Marca';
      document.getElementById('drawerSubtitle').textContent = appData.central.tagline;
      document.getElementById('drawerTitle').textContent = appData.central.name;
      document.getElementById('drawerFooter').classList.add('hidden');

      const body = document.getElementById('drawerBody');
      body.innerHTML = `
        <div class="bg-alento-coral text-white rounded-2xl p-5 shadow-soft">
          <span class="text-[11px] uppercase tracking-widest text-white/80">Significado de Alento</span>
          <p class="text-sm mt-1.5 leading-relaxed">${appData.central.meaning}</p>
        </div>

        <div class="bg-alento-soft rounded-2xl p-4 border border-alento-border">
          <h4 class="text-xs font-semibold uppercase tracking-wider text-alento-deep mb-1.5">Manifesto & Propósito</h4>
          <p class="text-sm text-alento-dark leading-relaxed">${appData.central.manifesto}</p>
          <p class="text-xs font-medium text-alento-deep mt-2.5 pt-2.5 border-t border-alento-border">${appData.central.resistanceQuote}</p>
        </div>

        <div>
          <h4 class="text-xs font-semibold uppercase tracking-wider text-alento-muted mb-2.5">Paleta Oficial (.alento.)</h4>
          <div class="grid grid-cols-2 gap-2.5">
            ${appData.central.palette.map((c) => `
              <div class="flex items-center gap-2.5 p-2.5 rounded-xl border border-alento-border bg-white">
                <span class="w-8 h-8 rounded-full shrink-0 border border-black/10" style="background:${c.hex}"></span>
                <div class="min-w-0">
                  <p class="text-xs font-semibold text-alento-dark truncate">${c.name}</p>
                  <p class="text-[11px] text-alento-muted">${c.hex} • ${c.pantone}</p>
                </div>
              </div>
            `).join('')}
          </div>
        </div>

        <div class="bg-alento-cream rounded-2xl p-4 border border-alento-border">
          <h4 class="text-xs font-semibold uppercase tracking-wider text-alento-muted mb-1">Tipografia Oficial</h4>
          <p class="text-xs text-alento-dark leading-relaxed">${appData.central.typography}</p>
        </div>
      `;

      openDrawerPanel();
    }

    function openNodeDrawer(nodeId) {
      const node = appData.nodes.find((n) => n.id === nodeId);
      if (!node) return;
      activeDrawerNodeId = nodeId;

      document.getElementById('drawerBadge').textContent = `Pilar ${node.number}`;
      document.getElementById('drawerSubtitle').textContent = node.subtitle;
      document.getElementById('drawerTitle').textContent = node.title;
      document.getElementById('drawerFooter').classList.remove('hidden');

      const body = document.getElementById('drawerBody');
      body.innerHTML = `
        <p class="text-sm text-alento-muted leading-relaxed">${node.summary}</p>
        <div class="space-y-4">
          ${node.sections.map((sec) => `
            <div class="bg-alento-cream rounded-2xl p-4 border border-alento-border">
              <h4 class="text-xs font-bold uppercase tracking-wider text-alento-deep mb-2">${sec.heading}</h4>
              <ul class="space-y-2 text-sm text-alento-dark leading-relaxed">
                ${sec.items.map((item) => `
                  <li class="flex items-start gap-2">
                    <span class="text-alento-coral font-bold mt-0.5">✳</span>
                    <span>${item}</span>
                  </li>
                `).join('')}
              </ul>
            </div>
          `).join('')}
        </div>

        <div>
          <h4 class="text-xs font-bold uppercase tracking-wider text-alento-muted mb-2">Suas Ideias & Anotações Extras</h4>
          ${node.notes.length === 0
            ? '<p class="text-xs text-alento-muted italic bg-alento-soft/50 rounded-xl p-3">Nenhuma anotação extra neste pilar ainda. Use o campo abaixo para registrar ideias.</p>'
            : `<ul class="space-y-2">
                ${node.notes.map((note, idx) => `
                  <li class="flex items-start justify-between gap-2 bg-alento-soft rounded-xl px-3.5 py-2.5 border border-alento-border text-sm text-alento-dark">
                    <span>${note}</span>
                    <button onclick="removeNoteFromNode('${node.id}', ${idx})" class="text-xs text-alento-muted hover:text-alento-deep cursor-pointer">✕</button>
                  </li>
                `).join('')}
              </ul>`
          }
        </div>
      `;

      openDrawerPanel();
    }

    function openDrawerPanel() {
      document.getElementById('drawerOverlay').classList.remove('hidden');
      document.getElementById('detailDrawer').classList.remove('translate-x-full');
    }

    function closeDrawer() {
      document.getElementById('drawerOverlay').classList.add('hidden');
      document.getElementById('detailDrawer').classList.add('translate-x-full');
      activeDrawerNodeId = null;
    }

    function addNoteToCurrentNode() {
      if (!activeDrawerNodeId || activeDrawerNodeId === 'central') return;
      const input = document.getElementById('drawerNewNoteInput');
      const text = input.value.trim();
      if (!text) return;

      const node = appData.nodes.find((n) => n.id === activeDrawerNodeId);
      if (node) {
        node.notes.push(text);
        saveData();
        input.value = '';
        openNodeDrawer(node.id);
        renderMindmapNodes();
        renderBoard();
        showToast('Anotação adicionada ao pilar!');
      }
    }

    function removeNoteFromNode(nodeId, idx) {
      const node = appData.nodes.find((n) => n.id === nodeId);
      if (!node) return;
      node.notes.splice(idx, 1);
      saveData();
      openNodeDrawer(nodeId);
      renderMindmapNodes();
      renderBoard();
      showToast('Anotação removida.');
    }

    function openQuickIdeaModal() {
      const select = document.getElementById('quickIdeaNodeSelect');
      select.innerHTML = appData.nodes.map((n) => `<option value="${n.id}">Pilar ${n.number} — ${n.title}</option>`).join('');
      document.getElementById('quickIdeaText').value = '';
      const modal = document.getElementById('quickIdeaModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeQuickIdeaModal() {
      const modal = document.getElementById('quickIdeaModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function saveQuickIdea() {
      const nodeId = document.getElementById('quickIdeaNodeSelect').value;
      const text = document.getElementById('quickIdeaText').value.trim();
      if (!text) return;

      const node = appData.nodes.find((n) => n.id === nodeId);
      if (node) {
        node.notes.push(text);
        saveData();
        closeQuickIdeaModal();
        renderMindmapNodes();
        renderBoard();
        showToast(`Ideia encaixada no Pilar ${node.number}!`);
      }
    }

    function resetDefaultData() {
      appData = JSON.parse(JSON.stringify(DEFAULT_DATA));
      saveData();
      renderMindmapNodes();
      renderBoard();
      showToast('Base restaurada com sucesso!');
    }

    function exportMarkdown() {
      let md = `# .alento. — Mapa Estratégico & Branding\n_${appData.central.tagline}_\n\n`;
      md += `## Essência\n${appData.central.meaning}\n\n${appData.central.manifesto}\n\n`;
      appData.nodes.forEach((n) => {
        md += `## Pilar ${n.number}: ${n.title}\n${n.summary}\n\n`;
        n.sections.forEach((s) => {
          md += `### ${s.heading}\n` + s.items.map((i) => `- ${i}`).join('\n') + '\n\n';
        });
        if (n.notes.length > 0) {
          md += `### Anotações Extras\n` + n.notes.map((i) => `- ${i}`).join('\n') + '\n\n';
        }
      });

      const blob = new Blob([md], { type: 'text/markdown;charset=utf-8' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'alento-planejamento.md';
      a.click();
      URL.revokeObjectURL(url);
      showToast('Planejamento exportado em Markdown!');
    }

    function toggleOrdersCalc() {
      const panel = document.getElementById('ordersCalculatorPanel');
      panel.classList.toggle('hidden');
    }

    function resetPriceCalc() {
      document.getElementById('calcMaterials').value = 25;
      document.getElementById('calcFixed').value = 10;
      document.getElementById('calcHours').value = 4;
      document.getElementById('calcHourlyRate').value = 25;
      document.getElementById('calcMargin').value = 30;
      calculateAlentoPrice();
    }

    function calculateAlentoPrice() {
      const mat = parseFloat(document.getElementById('calcMaterials')?.value) || 0;
      const fix = parseFloat(document.getElementById('calcFixed')?.value) || 0;
      const hrs = parseFloat(document.getElementById('calcHours')?.value) || 0;
      const rate = parseFloat(document.getElementById('calcHourlyRate')?.value) || 0;
      const margin = parseFloat(document.getElementById('calcMargin')?.value) || 0;

      const labor = hrs * rate;
      const base = mat + labor + fix;
      const profit = base * (margin / 100);
      const finalPrice = base + profit;

      document.getElementById('calcMarginBadge').textContent = `${margin}%`;
      document.getElementById('calcLaborTotal').textContent = formatBRL(labor);
      document.getElementById('calcBaseCost').textContent = formatBRL(base);
      document.getElementById('calcProfitValue').textContent = `+ ${formatBRL(profit)}`;
      document.getElementById('calcFinalPrice').textContent = formatBRL(finalPrice);

      return finalPrice;
    }

    function createOrderFromCalc() {
      const finalPrice = calculateAlentoPrice();
      openOrderModal();
      document.getElementById('orderTotalInput').value = finalPrice.toFixed(2);
      document.getElementById('orderDepositInput').value = (finalPrice / 2).toFixed(2);
    }

    function updateOrdersBadge() {
      const active = ordersData.filter((o) => o.stage !== 'entregue').length;
      const badge = document.getElementById('ordersNavBadge');
      if (badge) badge.textContent = active;
    }

    function renderOrdersView() {
      const activeOrders = ordersData.filter((o) => o.stage !== 'entregue');
      const totalValue = ordersData.reduce((acc, o) => acc + Number(o.total || 0), 0);
      const depositPaid = ordersData.reduce((acc, o) => acc + Number(o.deposit || 0), 0);
      const remaining = Math.max(0, totalValue - depositPaid);

      document.getElementById('statActiveCount').textContent = activeOrders.length;
      document.getElementById('statTotalValue').textContent = formatBRL(totalValue);
      document.getElementById('statDepositPaid').textContent = formatBRL(depositPaid);
      document.getElementById('statRemainingValue').textContent = formatBRL(remaining);

      const board = document.getElementById('ordersKanbanBoard');
      board.innerHTML = ORDER_STAGES.map((stage) => {
        const items = ordersData.filter((o) => o.stage === stage.id);
        return `
          <div class="bg-white/90 border border-alento-border rounded-2xl p-3.5 shadow-card space-y-3">
            <div class="flex items-center justify-between">
              <span class="text-[11px] font-bold px-2.5 py-0.5 rounded-full border ${stage.badgeClass}">
                ${stage.label}
              </span>
              <span class="text-xs font-semibold text-alento-muted">${items.length}</span>
            </div>
            <div class="space-y-2.5 min-h-[110px]">
              ${items.length === 0
                ? '<p class="text-[11px] text-alento-muted/70 text-center py-6 border border-dashed border-alento-border rounded-xl">Sem pedidos nesta etapa</p>'
                : items.map((o) => {
                    const rest = Math.max(0, Number(o.total || 0) - Number(o.deposit || 0));
                    return `
                      <div onclick="openOrderModal('${o.id}')" class="bg-alento-cream hover:bg-alento-soft/60 border border-alento-border rounded-xl p-3 cursor-pointer transition-colors space-y-1.5">
                        <div class="flex items-center justify-between gap-1">
                          <span class="text-[10px] font-semibold uppercase tracking-wide text-alento-deep">${o.category}</span>
                          <span class="text-[10px] font-medium px-1.5 py-0.5 rounded bg-white border border-alento-border text-alento-dark">${o.hoop}</span>
                        </div>
                        <p class="font-semibold text-xs text-alento-dark leading-snug">${o.client}</p>
                        <p class="text-[11px] text-alento-muted line-clamp-2">${o.title}</p>
                        <div class="pt-1.5 border-t border-alento-border/60 flex items-center justify-between text-[11px]">
                          <span class="text-alento-muted">📅 ${o.deadline ? o.deadline.split('-').reverse().slice(0, 2).join('/') : '--'}</span>
                          <span class="font-bold text-alento-dark">${formatBRL(o.total)}</span>
                        </div>
                        ${rest > 0
                          ? `<p class="text-[10px] text-alento-deep font-medium">Falta receber: ${formatBRL(rest)}</p>`
                          : `<p class="text-[10px] text-emerald-700 font-semibold">✓ Quitado</p>`}
                      </div>
                    `;
                  }).join('')}
            </div>
          </div>
        `;
      }).join('');
    }

    function openOrderModal(orderId = null) {
      const modal = document.getElementById('orderModal');
      const btnDelete = document.getElementById('btnDeleteOrder');

      if (orderId) {
        const order = ordersData.find((o) => o.id === orderId);
        if (!order) return;
        document.getElementById('orderModalTitle').textContent = 'Editar Encomenda';
        document.getElementById('orderIdInput').value = order.id;
        document.getElementById('orderClientInput').value = order.client;
        document.getElementById('orderCategoryInput').value = order.category;
        document.getElementById('orderTitleInput').value = order.title;
        document.getElementById('orderHoopInput').value = order.hoop;
        document.getElementById('orderDeadlineInput').value = order.deadline;
        document.getElementById('orderStageInput').value = order.stage;
        document.getElementById('orderTotalInput').value = order.total;
        document.getElementById('orderDepositInput').value = order.deposit;
        document.getElementById('orderNotesInput').value = order.notes || '';
        btnDelete.classList.remove('hidden');
      } else {
        document.getElementById('orderModalTitle').textContent = 'Nova Encomenda';
        document.getElementById('orderIdInput').value = '';
        document.getElementById('orderClientInput').value = '';
        document.getElementById('orderCategoryInput').value = 'Pet / Retrato';
        document.getElementById('orderTitleInput').value = '';
        document.getElementById('orderHoopInput').value = '16 cm';
        document.getElementById('orderDeadlineInput').value = new Date(Date.now() + 14 * 86400000).toISOString().split('T')[0];
        document.getElementById('orderStageInput').value = 'orcamento';
        document.getElementById('orderTotalInput').value = '';
        document.getElementById('orderDepositInput').value = '';
        document.getElementById('orderNotesInput').value = '';
        btnDelete.classList.add('hidden');
      }

      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeOrderModal() {
      const modal = document.getElementById('orderModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function setHalfDeposit() {
      const total = parseFloat(document.getElementById('orderTotalInput').value) || 0;
      document.getElementById('orderDepositInput').value = (total / 2).toFixed(2);
    }

    function saveOrderForm(e) {
      e.preventDefault();
      const id = document.getElementById('orderIdInput').value;
      const payload = {
        id: id || 'ord-' + Date.now(),
        client: document.getElementById('orderClientInput').value.trim(),
        category: document.getElementById('orderCategoryInput').value,
        title: document.getElementById('orderTitleInput').value.trim(),
        hoop: document.getElementById('orderHoopInput').value,
        deadline: document.getElementById('orderDeadlineInput').value,
        stage: document.getElementById('orderStageInput').value,
        total: parseFloat(document.getElementById('orderTotalInput').value) || 0,
        deposit: parseFloat(document.getElementById('orderDepositInput').value) || 0,
        notes: document.getElementById('orderNotesInput').value.trim()
      };

      if (id) {
        const idx = ordersData.findIndex((o) => o.id === id);
        if (idx >= 0) ordersData[idx] = payload;
      } else {
        ordersData.unshift(payload);
      }

      saveOrders();
      closeOrderModal();
      renderOrdersView();
      showToast('Encomenda salva na bancada!');
    }

    function deleteCurrentOrder() {
      const id = document.getElementById('orderIdInput').value;
      if (!id) return;
      ordersData = ordersData.filter((o) => o.id !== id);
      saveOrders();
      closeOrderModal();
      renderOrdersView();
      showToast('Encomenda removida.');
    }

    function toggleSatCalc() {
      document.getElementById('satCalculatorPanel').classList.toggle('hidden');
    }

    function resetSatCalc() {
      document.getElementById('satCalcMaterials').value = 6;
      document.getElementById('satCalcFixed').value = 2;
      document.getElementById('satCalcHours').value = 0.8;
      document.getElementById('satCalcHourlyRate').value = 20;
      document.getElementById('satCalcMargin').value = 45;
      calculateSatellitePrice();
    }

    function calculateSatellitePrice() {
      const mat = parseFloat(document.getElementById('satCalcMaterials')?.value) || 0;
      const fix = parseFloat(document.getElementById('satCalcFixed')?.value) || 0;
      const hrs = parseFloat(document.getElementById('satCalcHours')?.value) || 0;
      const rate = parseFloat(document.getElementById('satCalcHourlyRate')?.value) || 0;
      const margin = parseFloat(document.getElementById('satCalcMargin')?.value) || 0;

      const labor = hrs * rate;
      const base = mat + fix + labor;
      const profit = base * (margin / 100);
      const finalPrice = base + profit;

      document.getElementById('satCalcMarginBadge').textContent = `${margin}%`;
      document.getElementById('satCalcLaborTotal').textContent = formatBRL(labor);
      document.getElementById('satCalcBaseCost').textContent = formatBRL(base);
      document.getElementById('satCalcProfitValue').textContent = `+ ${formatBRL(profit)}`;
      document.getElementById('satCalcFinalPrice').textContent = formatBRL(finalPrice);

      return finalPrice;
    }

    function applySatCalcToItem() {
      const finalPrice = calculateSatellitePrice();
      const targetId = document.getElementById('satCalcTargetSelect').value;
      const item = satelliteData.items.find((i) => i.id === targetId);
      if (item) {
        item.price = Number(finalPrice.toFixed(2));
        saveSatellite();
        renderSatelliteView();
        showToast(`Preço atualizado para ${formatBRL(item.price)} em ${item.name}!`);
      }
    }

    function renderSatelliteView() {
      const totalRaw = satelliteData.items.reduce((acc, i) => acc + Number(i.rawStock || 0), 0);
      const totalReady = satelliteData.items.reduce((acc, i) => acc + Number(i.readyStock || 0), 0);
      const totalSold = satelliteData.items.reduce((acc, i) => acc + Number(i.soldCount || 0), 0);
      const totalRev = satelliteData.items.reduce((acc, i) => acc + (Number(i.soldCount || 0) * Number(i.price || 0)), 0);

      document.getElementById('satStatRaw').textContent = totalRaw;
      document.getElementById('satStatReady').textContent = totalReady;
      document.getElementById('satStatSold').textContent = totalSold;
      document.getElementById('satStatRevenue').textContent = formatBRL(totalRev);

      const targetSelect = document.getElementById('satCalcTargetSelect');
      if (targetSelect) {
        targetSelect.innerHTML = satelliteData.items.map((i) => `<option value="${i.id}">${i.name} (${i.size})</option>`).join('');
      }

      const container = document.getElementById('satelliteItemsContainer');
      container.innerHTML = satelliteData.items.map((item) => `
        <div class="bg-white border border-alento-border rounded-3xl p-5 shadow-card space-y-4">
          <div class="flex items-start justify-between gap-3">
            <div>
              <span class="text-[11px] font-semibold px-2.5 py-0.5 rounded-full bg-amber-100 text-amber-800 border border-amber-200">
                Medida: ${item.size}
              </span>
              <h3 class="font-display font-semibold text-xl text-alento-dark mt-1.5">${item.name}</h3>
              <p class="text-xs text-alento-muted mt-0.5">${item.description || ''}</p>
            </div>
            <div class="text-right">
              <span class="text-[10px] uppercase tracking-wider text-alento-muted block">Preço Unitário</span>
              <span class="font-display font-semibold text-xl text-alento-coral">${formatBRL(item.price)}</span>
              <button onclick="openSatelliteItemModal('${item.id}')" class="block ml-auto mt-1 text-[11px] font-semibold text-alento-deep hover:underline cursor-pointer">
                Editar
              </button>
            </div>
          </div>

          <div class="grid grid-cols-3 gap-2.5 text-center">
            <div class="bg-alento-cream border border-alento-border rounded-2xl p-3">
              <span class="text-[10px] font-semibold uppercase text-alento-muted block">Bases Virgens</span>
              <span class="font-display font-semibold text-2xl text-alento-dark block my-1">${item.rawStock}</span>
              <div class="flex justify-center gap-1.5">
                <button onclick="adjustSatStock('${item.id}', 'rawStock', -1)" class="w-6 h-6 rounded-full bg-white border border-alento-border text-xs font-bold hover:bg-alento-soft cursor-pointer">-</button>
                <button onclick="adjustSatStock('${item.id}', 'rawStock', 1)" class="w-6 h-6 rounded-full bg-white border border-alento-border text-xs font-bold hover:bg-alento-soft cursor-pointer">+</button>
              </div>
            </div>

            <div class="bg-amber-50/70 border border-amber-200 rounded-2xl p-3">
              <span class="text-[10px] font-semibold uppercase text-amber-800 block">Prontas (Rua)</span>
              <span class="font-display font-semibold text-2xl text-amber-800 block my-1">${item.readyStock}</span>
              <button onclick="produceSatUnit('${item.id}')" class="px-2.5 py-1 rounded-full bg-amber-600 hover:bg-amber-700 text-white text-[10px] font-semibold cursor-pointer">
                +1 Bordada
              </button>
            </div>

            <div class="bg-emerald-50/70 border border-emerald-200 rounded-2xl p-3">
              <span class="text-[10px] font-semibold uppercase text-emerald-800 block">Vendidas</span>
              <span class="font-display font-semibold text-2xl text-emerald-700 block my-1">${item.soldCount}</span>
              <button onclick="sellSatUnit('${item.id}')" class="px-2.5 py-1 rounded-full bg-emerald-600 hover:bg-emerald-700 text-white text-[10px] font-semibold cursor-pointer">
                +1 Venda
              </button>
            </div>
          </div>
        </div>
      `).join('');

      const notesList = document.getElementById('satelliteNotesList');
      notesList.innerHTML = satelliteData.notes.map((n) => `
        <div class="flex items-center justify-between gap-2 bg-alento-cream border border-alento-border rounded-xl px-3.5 py-2 text-xs">
          <label class="flex items-center gap-2 cursor-pointer flex-1">
            <input type="checkbox" ${n.done ? 'checked' : ''} onchange="toggleSatelliteNote('${n.id}')" class="accent-[#FF6F61]" />
            <span class="${n.done ? 'line-through text-alento-muted' : 'text-alento-dark'}">${n.text}</span>
          </label>
          <button onclick="deleteSatelliteNote('${n.id}')" class="text-alento-muted hover:text-alento-deep cursor-pointer">✕</button>
        </div>
      `).join('');
    }

    function adjustSatStock(id, field, delta) {
      const item = satelliteData.items.find((i) => i.id === id);
      if (!item) return;
      item[field] = Math.max(0, Number(item[field] || 0) + delta);
      saveSatellite();
      renderSatelliteView();
    }

    function produceSatUnit(id) {
      const item = satelliteData.items.find((i) => i.id === id);
      if (!item) return;
      if (item.rawStock > 0) item.rawStock -= 1;
      item.readyStock = Number(item.readyStock || 0) + 1;
      saveSatellite();
      renderSatelliteView();
      showToast('Peça pronta adicionada ao estoque de rua!');
    }

    function sellSatUnit(id) {
      const item = satelliteData.items.find((i) => i.id === id);
      if (!item) return;
      if (item.readyStock > 0) item.readyStock -= 1;
      item.soldCount = Number(item.soldCount || 0) + 1;
      saveSatellite();
      renderSatelliteView();
      showToast(`Venda registrada (+ ${formatBRL(item.price)})!`);
    }

    function openSatelliteItemModal(itemId = null) {
      const modal = document.getElementById('satelliteModal');
      if (itemId) {
        const item = satelliteData.items.find((i) => i.id === itemId);
        if (!item) return;
        document.getElementById('satModalTitle').textContent = 'Editar Item do Satélite';
        document.getElementById('satIdInput').value = item.id;
        document.getElementById('satNameInput').value = item.name;
        document.getElementById('satSizeInput').value = item.size;
        document.getElementById('satPriceInput').value = item.price;
        document.getElementById('satRawInput').value = item.rawStock;
        document.getElementById('satReadyInput').value = item.readyStock;
        document.getElementById('satSoldInput').value = item.soldCount;
        document.getElementById('satDescInput').value = item.description || '';
      } else {
        document.getElementById('satModalTitle').textContent = 'Novo Item do Satélite';
        document.getElementById('satIdInput').value = '';
        document.getElementById('satNameInput').value = '';
        document.getElementById('satSizeInput').value = '';
        document.getElementById('satPriceInput').value = 30;
        document.getElementById('satRawInput').value = 0;
        document.getElementById('satReadyInput').value = 0;
        document.getElementById('satSoldInput').value = 0;
        document.getElementById('satDescInput').value = '';
      }
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeSatelliteModal() {
      const modal = document.getElementById('satelliteModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function saveSatelliteItemForm(e) {
      e.preventDefault();
      const id = document.getElementById('satIdInput').value;
      const payload = {
        id: id || 'sat-' + Date.now(),
        name: document.getElementById('satNameInput').value.trim(),
        size: document.getElementById('satSizeInput').value.trim(),
        price: parseFloat(document.getElementById('satPriceInput').value) || 0,
        rawStock: parseInt(document.getElementById('satRawInput').value, 10) || 0,
        readyStock: parseInt(document.getElementById('satReadyInput').value, 10) || 0,
        soldCount: parseInt(document.getElementById('satSoldInput').value, 10) || 0,
        description: document.getElementById('satDescInput').value.trim()
      };

      if (id) {
        const idx = satelliteData.items.findIndex((i) => i.id === id);
        if (idx >= 0) satelliteData.items[idx] = payload;
      } else {
        satelliteData.items.push(payload);
      }

      saveSatellite();
      closeSatelliteModal();
      renderSatelliteView();
      showToast('Item do Projeto Satélite salvo!');
    }

    function addSatelliteNote() {
      const input = document.getElementById('satelliteNoteInput');
      const text = input.value.trim();
      if (!text) return;
      satelliteData.notes.push({ id: 'sn-' + Date.now(), text, done: false });
      saveSatellite();
      input.value = '';
      renderSatelliteView();
    }

    function toggleSatelliteNote(id) {
      const note = satelliteData.notes.find((n) => n.id === id);
      if (!note) return;
      note.done = !note.done;
      saveSatellite();
      renderSatelliteView();
    }

    function deleteSatelliteNote(id) {
      satelliteData.notes = satelliteData.notes.filter((n) => n.id !== id);
      saveSatellite();
      renderSatelliteView();
    }

    function showToast(msg) {
      const toast = document.getElementById('toast');
      toast.textContent = msg;
      toast.classList.remove('opacity-0');
      setTimeout(() => toast.classList.add('opacity-0'), 2600);
    }

    let deferredInstallPrompt = null;

    function initPwaManifest() {
      const iconSvg = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><rect width="512" height="512" rx="112" fill="#FF6F61"/><circle cx="256" cy="256" r="208" fill="none" stroke="#FFFFFF" stroke-opacity="0.45" stroke-width="6" stroke-dasharray="12 10"/><text x="256" y="305" font-family="Georgia, serif" font-weight="bold" font-size="210" fill="#FFFFFF" text-anchor="middle">.a.</text></svg>`;
      const iconUrl = 'data:image/svg+xml;charset=utf-8,' + encodeURIComponent(iconSvg);

      const manifest = {
        name: '.alento. — bordado feito à mão',
        short_name: '.alento.',
        description: 'Painel estratégico, encomendas e projeto satélite da .alento.',
        start_url: '.',
        display: 'standalone',
        background_color: '#FFFDFC',
        theme_color: '#FF6F61',
        icons: [
          { src: iconUrl, sizes: '192x192', type: 'image/svg+xml' },
          { src: iconUrl, sizes: '512x512', type: 'image/svg+xml' }
        ]
      };

      try {
        const blob = new Blob([JSON.stringify(manifest)], { type: 'application/manifest+json' });
        const manifestUrl = URL.createObjectURL(blob);
        const link = document.createElement('link');
        link.rel = 'manifest';
        link.href = manifestUrl;
        document.head.appendChild(link);
      } catch (e) {}
    }

    window.addEventListener('beforeinstallprompt', (e) => {
      e.preventDefault();
      deferredInstallPrompt = e;
      const box = document.getElementById('nativeInstallPromptBox');
      if (box) box.classList.remove('hidden');
    });

    function triggerNativeInstall() {
      if (!deferredInstallPrompt) return;
      deferredInstallPrompt.prompt();
      deferredInstallPrompt.userChoice.then(() => {
        deferredInstallPrompt = null;
        closeAppInstallGuide();
      });
    }

    function openAppInstallGuide() {
      const modal = document.getElementById('appInstallModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeAppInstallGuide() {
      const modal = document.getElementById('appInstallModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    document.addEventListener('DOMContentLoaded', () => {
      initPwaManifest();
      renderMindmapNodes();
      updateOrdersBadge();
      calculateAlentoPrice();
      calculateSatellitePrice();
    });
  </script>
</body>
</html>pa_mental_estrat_gico_alento.html…]()
