# Image-Magick---GUI
🖼️ ImageMagick GUI - Conversor Multiformato
<div align="center"> <img src="assets/icon.ico" alt="Logo" width="128" height="128"> <br> <h3>O poder do ImageMagick em uma interface simples e intuitiva!</h3> <p> <strong>⭐ 100% Funcional</strong> · <strong>⚡ Conversão em Lote</strong> · <strong>🎨 7 Abas de Ferramentas</strong> · <strong>📦 Portátil</strong> </p> </div>
📋 Sobre o Programa
O ImageMagick GUI é uma aplicação desktop que transforma o poderoso ImageMagick em uma ferramenta acessível para todos. Com uma interface moderna e organizada, você pode realizar conversões e edições de arquivos sem precisar de conhecimentos técnicos.

⚠️ IMPORTANTE: Como Distribuir
❌ NÃO FUNCIONA:
text
Apenas o arquivo .exe sozinho ❌
O .exe precisa dos arquivos da pasta src e assets para funcionar!

✅ FUNCIONA:
text
Baixar a pasta COMPLETA do projeto ✅
📦 Como Baixar e Instalar
Método 1: Baixar o ZIP completo (RECOMENDADO)
Passo 1: Baixe o ZIP completo do projeto

text
ImageMagick Project - 2.0.zip
Passo 2: Extraia a pasta para qualquer lugar

text
Exemplo: C:\Programas\ImageMagick GUI\
Passo 3: Execute o programa

text
Dê duplo clique em: ImageMagickProject+.exe
Passo 4: Se aparecer erro, execute como Administrador

text
Clique com botão direito → "Executar como administrador"
📁 Estrutura que você DEVE ter:
text
ImageMagick Project - 2.0/           ← PASTA PRINCIPAL (NÃO PODE FALTAR!)
│
├── 📁 assets/                       ← NECESSÁRIO (ícones)
│   └── icon.ico
│
├── 📁 src/                          ← NECESSÁRIO (código do programa)
│   ├── 📁 converters/               ← Código de conversão
│   ├── 📁 gui/                      ← Interface gráfica
│   ├── 📁 utils/                    ← Utilitários
│   └── main.py
│
├── 📄 ImageMagickProject+.exe       ← EXECUTÁVEL PRINCIPAL
├── 📄 run.py                        ← Alternativa (para rodar com Python)
├── 📄 requirements.txt              ← Dependências
└── 📄 README.md                     ← Este arquivo
⚠️ O .exe SÓ FUNCIONA se a pasta src e assets estiverem no mesmo local!

🚀 Como Executar
Opção 1: Executável (.exe) - RECOMENDADO
text
1. Extraia a pasta completa do ZIP
2. Entre na pasta "ImageMagick Project - 2.0"
3. Dê duplo clique em "ImageMagickProject+.exe"
4. ✅ Programa aberto!
Opção 2: Via Python (se tiver Python instalado)
bash
# Entre na pasta do projeto
cd "ImageMagick Project - 2.0"

# Instale as dependências
pip install -r requirements.txt

# Execute
python run.py
Opção 3: Via Batch
bash
# Entre na pasta do projeto
cd "ImageMagick Project - 2.0"

# Execute
run_gui.bat
📋 Pré-requisitos
Para usuários finais (necessário INSTALAR):
Item	Obrigatório?	Como instalar
Windows 7/8/10/11	✅	Já deve ter
ImageMagick	✅✅✅	winget install ImageMagick.ImageMagick
Python	❌	Não precisa! (o .exe já tem)
⚠️ ATENÇÃO: INSTALAR O IMAGEMAGICK!
O programa NÃO FUNCIONA sem o ImageMagick!

powershell
# Instale o ImageMagick (Windows 10/11):
winget install ImageMagick.ImageMagick

# OU baixe manualmente:
https://imagemagick.org/script/download.php

# ⚠️ DURANTE A INSTALAÇÃO, MARQUE:
☑️ "Install legacy utilities (e.g. convert)"
✨ Funcionalidades Completas
📁 Aba 1: Conversão
Formato	Extensão	Suporte
PNG	.png	✅ Transparência
JPG/JPEG	.jpg .jpeg	✅ Compressão ajustável
GIF	.gif	✅ Animação
BMP	.bmp	✅ Sem compressão
TIFF	.tiff	✅ Alta qualidade
WEBP	.webp	✅ Moderno
ICO	.ico	✅ Ícones
HEIC	.heic	✅ Apple
PDF	.pdf	✅ Documentos
SVG	.svg	✅ Vetor
EPS	.eps	✅ PostScript
PSD	.psd	✅ Photoshop
AVIF	.avif	✅ Última geração
📐 Aba 2: Redimensionar
Largura e altura personalizáveis

Manter proporção automaticamente

Presets prontos: Ícone (256x256), Médio (800x600), HD (1920x1080), 4K (3840x2160), Instagram (1080x1080)

Redimensionamento em lote

🎨 Aba 3: Ajustes de Cor
Brilho (-100% a +100%)

Contraste (-100% a +100%)

Saturação (-100% a +100%)

Preto e Branco com 1 clique

Efeito Sépia com 1 clique

Níveis automáticos

✨ Aba 4: Filtros e Efeitos
Efeito	Descrição
Negativo	Inverte as cores
Carvão	Efeito de desenho
Óleo	Efeito de pintura
Bordas	Detecção de bordas
Embossar	Efeito 3D em relevo
Pixelizar	Efeito pixel art
Desfoque	Ajuste de 0 a 20
Nitidez	Ajuste de 0 a 20
✂️ Aba 5: Recortar/Girar
Recortar com coordenadas X, Y, Largura, Altura

Girar em 0°, 90°, 180°, 270°

Espelhar Horizontal (flip)

Espelhar Vertical (flop)

⚙️ Aba 6: Avançado
Preservar transparência (PNG/GIF/WEBP)

Auto-orientar imagens

Remover metadados

Cor de fundo personalizável

📚 Aba 7: Múltiplos Arquivos
Juntar PDFs selecionados

Criar GIF animado com delay ajustável

Loop infinito ou quantidade definida

Combinar imagens em overlay

🎯 Como Usar - Guia Rápido
1️⃣ Selecione os arquivos
text
Clique em "📁 Selecionar Arquivos" ou "📂 Selecionar Pasta"
2️⃣ Escolha o formato de saída
text
Vá para a aba "📁 Conversão" → Clique no formato desejado
3️⃣ Configure opções adicionais (opcional)
text
Redimensionar (Aba 2) | Cores (Aba 3) | Efeitos (Aba 4) | Recortar (Aba 5) | Avançado (Aba 6)
4️⃣ Escolha a pasta de saída
text
Clique em "📂 Selecionar" ao lado de "Pasta de Saída"
5️⃣ Converta!
text
Clique em "▶ CONVERTER" → Acompanhe a barra de progresso
6️⃣ Abra a pasta (opcional)
text
Clique em "📂 Abrir Pasta" para ver os arquivos convertidos
💡 Exemplos Práticos
Exemplo 1: Converter uma imagem para PDF
text
1. Selecione a imagem (ex: foto.jpg)
2. Clique em "PDF" na aba Conversão
3. Selecione a pasta de saída
4. Clique em CONVERTER
5. ✅ foto.pdf criado!
Exemplo 2: Juntar vários PDFs
text
1. Selecione 2 ou mais PDFs (ex: doc1.pdf, doc2.pdf)
2. Vá para a aba "📚 Múltiplos"
3. Clique em "📄 JUNTAR PDFs SELECIONADOS"
4. ✅ PDFs_Unidos.pdf criado!
Exemplo 3: Criar um GIF animado
text
1. Selecione várias imagens (ex: frame1.png, frame2.png, frame3.png)
2. Vá para a aba "📚 Múltiplos"
3. Ajuste o delay (ex: 100ms)
4. Clique em "🎬 CRIAR GIF"
5. ✅ animacao.gif criado!
🛠️ Solução de Problemas
❌ "ImageMagick não encontrado!"
powershell
# Instale o ImageMagick:
winget install ImageMagick.ImageMagick

# ⚠️ IMPORTANTE: Marque a opção:
# ☑️ "Install legacy utilities (e.g. convert)"
❌ "Erro: no decode delegate"
text
O arquivo pode estar corrompido ou o formato não é suportado.
Verifique a tabela de formatos suportados acima.
❌ "Erro: Ghostscript não encontrado!"
powershell
# Para converter PDFs, instale o Ghostscript:
# Baixe em: https://www.ghostscript.com/download/gsdnld.html
# Instale e reinicie o computador
❌ "O programa não abre!"
text
1. Verifique se a pasta src está no mesmo local do .exe
2. Execute como Administrador
3. Desative o antivírus temporariamente (pode estar bloqueando)
❌ "Erro: pastas faltando!"
text
A estrutura DEVE ser:
ImageMagick Project - 2.0/
├── src/           ← NÃO PODE FALTAR
├── assets/         ← NÃO PODE FALTAR
└── ImageMagickProject+.exe
📦 Como Distribuir seu Programa
Para enviar para outras pessoas:
Opção 1: ZIP completo

text
1. Compacte a pasta inteira em .zip
2. Envie o arquivo .zip
3. A pessoa extrai e executa o .exe
Opção 2: Pasta compartilhada

text
1. Copie a pasta inteira para um pendrive
2. Ou compartilhe via OneDrive/Google Drive
3. A pessoa baixa a pasta completa
⚠️ O que NÃO pode faltar:
text
✅ src/           (código do programa)
✅ assets/        (ícones)
✅ ImageMagickProject+.exe
📊 Tecnologias Utilizadas
Tecnologia	Versão	Finalidade
Python	3.8+	Linguagem de programação
CustomTkinter	5.2.0	Interface gráfica moderna
Pillow	10.1.0	Manipulação de imagens
PyInstaller	6.3.0	Criação do executável
ImageMagick	7.x	Engine de conversão
📝 Licença
Este projeto é open-source sob a licença MIT. Sinta-se livre para:

✅ Usar comercialmente

✅ Modificar e adaptar

✅ Distribuir

✅ Sub-licenciar

Atribuição é apreciada, mas não obrigatória.

👨‍💻 Desenvolvedor
Autor: Vitor Corrêa
Projeto: ImageMagick GUI
Versão: 2.0
Status: ✅ Estável e funcional
Tecnologias: Python, CustomTkinter, ImageMagick

🙏 Agradecimentos
ImageMagick - Pela poderosa engine de conversão

CustomTkinter - Pela interface moderna e bonita

PyInstaller - Pela criação do executável portátil

<div align="center"> <h3>🖼️ ImageMagick GUI</h3> <p> <strong>Transforme seus arquivos com apenas alguns cliques!</strong> </p> <br> <p> 📸 <strong>Formatos:</strong> PNG, JPG, PDF, GIF, WEBP, ICO, HEIC, AVIF, SVG, EPS, PSD, TIFF </p> <p> 🎯 <strong>Recursos:</strong> Conversão, Redimensionamento, Efeitos, Filtros, Recortar, Girar, Juntar PDFs, Criar GIFs </p> <br> <sub>Feito com ❤️ usando Python</sub> </div> ```
