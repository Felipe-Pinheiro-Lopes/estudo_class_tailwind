# DevMetrics Dashboard — Estudo de Classes Tailwind CSS 🚀

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide_Icons-F56565?style=for-the-badge&logo=feather&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)

Projeto prático desenvolvido para demonstrar o poder, elegância e flexibilidade do **Tailwind CSS**. O projeto implementa o **DevMetrics Dashboard**, uma interface moderna em Dark Mode aplicando mais de **45 classes utilitárias** organizadas em 8 categorias principais do framework.

---

## 📸 Visão Geral do Projeto

O **DevMetrics** é um painel de controle para equipes de engenharia de software contendo:
- **Header & Navbar Sticky:** Menu responsivo com efeito *glassmorphism* (`backdrop-blur-md`), gradientes de marca e badges dinâmicos.
- **Hero Section Moderna:** Chamada de destaque com iluminação de fundo (*radial glow*), tipografia escalonada e botões com transições interativas.
- **Cards de Métricas em Tempo Real:** Grid responsivo com indicadores de commits, taxa de sucesso de deploys, PRs pendentes e efeitos de hover com elevação (`scale` e `shadow`).
- **Painel de Projetos e Equipe:** Estrutura mista em Grid e Flexbox com listas dinâmicas, status operacionais e avatares com badges de presença.
- **Guia Didático de Classes:** Seção interativa documentando as classes utilitárias agrupadas por funcionalidade.

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estruturação semântica e acessível.
- **[Tailwind CSS (CDN)](https://tailwindcss.com/):** Framework CSS utilitário para estilização rápida e responsiva.
- **[Google Fonts (Inter)](https://fonts.google.com/specimen/Inter):** Tipografia moderna e limpa.
- **[Lucide Icons](https://lucide.dev/):** Conjunto leve de ícones vetoriais.

---

## 📂 Estrutura do Repositório

```bash
estudo_class_tailwind/
├── index.html      # Documento principal com a interface e guia didático
└── README.md       # Documentação completa do projeto
```

---

## 🖥️ Como Executar o Projeto

Como o projeto utiliza a distribuição via CDN do Tailwind CSS, não é necessária a instalação de dependências ou build complexo:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Felipe-Pinheiro-Lopes/estudo_class_tailwind.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd estudo_class_tailwind
   ```

3. **Abra o arquivo [`index.html`](index.html):**
   - Diretamente no seu navegador de preferência clicando duas vezes no arquivo; **ou**
   - Utilizando a extensão **Live Server** no VS Code para recarregamento automático.

---

## 📋 Mapeamento Completo de Classes Tailwind CSS

O projeto explora mais de **45 classes utilitárias** distribuídas nas categorias fundamentais do framework:

### 1. Cores e Gradientes (Backgrounds, Textos e Bordas)
| Classe | Função / Finalidade |
| :--- | :--- |
| `bg-slate-950` | Define a cor de fundo principal escura |
| `bg-slate-900` / `bg-slate-900/60` | Cor de fundo de containers e cards com opacidade |
| `bg-indigo-600` / `bg-indigo-500` | Cores primárias de destaque e botões |
| `bg-indigo-500/10` / `bg-emerald-500/10` | Fundos translúcidos para badges |
| `text-slate-100` / `text-slate-400` / `text-slate-500` | Hierarquia de tons de texto |
| `text-emerald-400` / `text-amber-400` / `text-indigo-400` | Cores semânticas de status e métricas |
| `bg-gradient-to-r` / `bg-gradient-to-tr` | Direção de gradientes lineares |
| `from-indigo-600` / `to-violet-500` | Cores de início e fim dos gradientes |
| `bg-clip-text` | Aplica o gradiente como máscara de preenchimento do texto |
| `text-transparent` | Torna o texto transparente para exibir o gradiente de fundo |

### 2. Tipografia
| Classe | Função / Finalidade |
| :--- | :--- |
| `text-xs` / `text-sm` / `text-base` / `text-lg` / `text-xl` / `text-3xl` / `text-5xl` | Escala tipográfica modular |
| `font-normal` / `font-medium` / `font-semibold` / `font-bold` / `font-extrabold` | Pesos de fonte |
| `tracking-tight` / `tracking-wider` | Controle de espaçamento entre caracteres (*letter-spacing*) |
| `leading-tight` / `leading-relaxed` | Altura da linha de texto (*line-height*) |
| `uppercase` | Transforma o texto em caixa alta |
| `text-center` / `text-left` | Alinhamento do conteúdo textual |
| `antialiased` | Suavização na renderização das fontes |

### 3. Espaçamentos (Padding, Margin e Gap)
| Classe | Função / Finalidade |
| :--- | :--- |
| `p-2` / `p-3` / `p-4` / `p-6` / `p-8` / `p-12` | Padding uniforme interno |
| `px-4` / `px-6` / `px-8` | Padding no eixo horizontal |
| `py-2` / `py-3` / `py-4` / `py-10` / `py-12` | Padding no eixo vertical |
| `mx-auto` | Centralização automática horizontal de containers |
| `mt-2` / `mt-16` / `mb-1` / `mb-4` | Margens direcionadas superiores e inferiores |
| `gap-2` / `gap-4` / `gap-6` | Espaçamento entre itens em Grid e Flexbox |
| `space-x-1` / `space-x-2` / `space-x-3` / `space-x-4` / `space-x-6` | Espaçamento horizontal consistente entre filhos |
| `space-y-2` / `space-y-3` / `space-y-4` / `space-y-6` / `space-y-12` | Espaçamento vertical consistente entre filhos |

### 4. Dimensões
| Classe | Função / Finalidade |
| :--- | :--- |
| `w-full` | Largura de 100% |
| `max-w-7xl` / `max-w-3xl` / `max-w-2xl` | Larguras máximas estruturais para contenção |
| `min-h-screen` | Altura mínima equivalente a 100% da viewport (`100vh`) |
| `h-16` / `w-10` / `h-10` / `w-9` / `h-9` / `w-5` / `h-5` / `w-4` / `h-4` | Alturas e larguras dimensionadas |

### 5. Bordas, Anéis e Sombras
| Classe | Função / Finalidade |
| :--- | :--- |
| `rounded-lg` / `rounded-xl` / `rounded-2xl` / `rounded-3xl` / `rounded-full` | Raios de curvatura de bordas |
| `border` / `border-b` / `border-t` | Aplicação de bordas gerais ou direcionais |
| `border-slate-800` / `border-slate-700` | Cores utilitárias de borda |
| `ring-1` / `ring-2` / `ring-white/20` | Efeito de anel/contorno (*ring*) |
| `shadow-md` / `shadow-lg` / `shadow-xl` | Elevações e sombras projetadas |
| `shadow-indigo-500/30` / `shadow-indigo-600/25` | Sombras coloridas com opacidade controlada |
| `divide-y` / `divide-slate-800` | Linhas divisórias automáticas entre elementos filhos |

### 6. Posicionamento e Camadas
| Classe | Função / Finalidade |
| :--- | :--- |
| `relative` / `absolute` / `sticky` | Modos de posicionamento CSS |
| `top-0` / `top-1.5` / `right-1.5` / `-top-24` / `-right-24` | Coordenadas de posicionamento absoluto/fixo |
| `z-10` / `z-50` | Controle de camadas no eixo de profundidade (*z-index*) |
| `overflow-hidden` / `overflow-x-auto` | Gerenciamento de estouro de conteúdo e rolagem horizontal |
| `pointer-events-none` | Isola elementos decorativos da interação do mouse |

### 7. Flexbox
| Classe | Função / Finalidade |
| :--- | :--- |
| `flex` / `inline-flex` | Ativação do container Flexbox |
| `items-center` / `items-stretch` / `items-baseline` | Alinhamento de itens no eixo cruzado |
| `justify-between` / `justify-center` | Distribuição e alinhamento no eixo principal |
| `flex-col` / `flex-row` | Direção do fluxo dos elementos flex |

### 8. CSS Grid
| Classe | Função / Finalidade |
| :--- | :--- |
| `grid` | Ativação do container CSS Grid |
| `grid-cols-1` | 1 coluna padrão (mobile-first) |
| `col-span-1` / `lg:col-span-2` | Definição de quantas colunas o item ocupa |
| `lg:grid-cols-3` / `lg:grid-cols-4` | Redefinição dinâmica do número de colunas por breakpoint |

### 9. Responsividade (Mobile-First)
| Prefixo | Exemplos Aplicados |
| :--- | :--- |
| `sm:` (≥ 640px) | `sm:px-6`, `sm:p-12`, `sm:text-5xl`, `sm:grid-cols-2`, `sm:flex-row`, `sm:space-y-0` |
| `md:` (≥ 768px) | `md:flex`, `md:grid-cols-2` |
| `lg:` (≥ 1024px) | `lg:px-8`, `lg:space-x-2`, `lg:grid-cols-3`, `lg:grid-cols-4`, `lg:col-span-2` |

### 10. Estados Interativos e Animações
| Classe | Função / Finalidade |
| :--- | :--- |
| `hover:bg-slate-800` / `hover:bg-indigo-500` / `hover:text-white` | Estilizações acionadas ao passar o mouse |
| `hover:border-indigo-500/50` / `hover:border-emerald-500/50` | Transição suave de borda em hover |
| `hover:scale-[1.02]` / `hover:-translate-y-0.5` | Feedback tátil de micro-elevação |
| `active:scale-[0.98]` | Feedback tátil de clique / pressão |
| `group` & `group-hover:scale-110` | Animação em elemento filho baseada no estado do elemento pai |
| `transition-all` / `transition-colors` / `transition-transform` | Propriedades animadas de transição |
| `duration-300` | Duração das transições suaves (300ms) |
| `backdrop-blur-md` | Efeito de desfoque de fundo (*Glassmorphism*) |
| `animate-pulse` | Animação de pulso contínuo para indicadores ativos |
| `cursor-pointer` | Indicação visual de cursor clicável |

---

## 📄 Licença

Este projeto é voltado para fins de estudo e prática. Sinta-se livre para utilizar, modificar e expandir!
