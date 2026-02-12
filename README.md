# Landing Page com Tailwind CSS – Alura Newsletter

## Visão Geral

Este projeto apresenta uma **landing page moderna** utilizando **Tailwind CSS**, totalmente responsiva e interativa. Ele simula uma página de inscrição para uma newsletter da Alura, com elementos visuais animados e um design limpo e profissional.

Principais componentes:

- Fundo em gradiente
- Área central com formulário de inscrição
- Ícones e animações interativas
- Uso avançado do Tailwind CSS (cores personalizadas, fontes, keyframes)

---

## Estrutura do Layout

### Body

- Aplica **gradiente de fundo** (`from-purple-400 to-blue-600`)  
- Centraliza todo o conteúdo na tela

### Main Container

- Fundo branco, parcialmente translúcido (`opacity-50`) na primeira versão
- Layout flexível (`flex flex-col lg:flex-row`) para responsividade
- Sombreamento 3D (`shadow-2xl`)
- Margens e padding para espaçamento adequado

### Elementos Internos

- **Imagens de logo**: distribuídas nas laterais do título  
- **Título central**: grande, negrito (`text-4xl lg:text-6xl font-black`)  
- Layout adaptável para dispositivos grandes (`lg:w-1/5`) e pequenos (`w-2/5`)

---

## Landing Page Alura Newsletter (Segunda Parte)

### Layout Responsivo

- Container principal (`main`) dividido em **duas seções**:
  1. **Seção esquerda** (`.bg-azul-escuro`)  
     - Apenas visível em telas grandes (`hidden lg:block`)  
     - Contém **imagem decorativa** (ícone de mergulhador)
  2. **Seção direita** (`.bg-white`)  
     - Contém **título**, **subtítulo**, **formulário**  
     - Bordas arredondadas e sombra para destaque (`rounded-lg`, `drop-shadow-2xl`)

### Tipografia e Cores Personalizadas

- Configuração Tailwind extendida:
  - Cores personalizadas (`azul: claro, escuro, hover`)
  - Fonte personalizada (`Inter`)
  - Keyframes customizados para animações (`sino_kf`)

### Animações

1. **Sino animado**
   - Elemento SVG que balança quando hover
   - Definido por keyframe `sino_kf`  
   - Classe `animate-sino` aplicada ao hover do grupo

2. **Ping decorativo**
   - SVG adicional que pisca (`animate-ping`) quando hover

### Formulário de Inscrição

- Campo de email estilizado:
  - Bordas arredondadas
  - Shadow interno
  - Hover e focus com cores personalizadas
- Botão de inscrição:
  - Fundo escuro, hover com cor mais clara
  - Bordas arredondadas, sombra (`shadow-2xl`)
  - Texto branco e em negrito

---

## Responsividade e Interatividade

- Uso de **Flexbox** (`flex`, `justify-center`, `items-center`)  
- Ajuste de layout com `lg:flex-row` e `lg:w-1/2` para telas grandes  
- Ocultação de elementos decorativos em telas pequenas (`hidden lg:block`)  
- Animações e transições suaves para hover (`duration-150`)  

---

## Pontos Fortes do Projeto

✔ Design moderno e responsivo  
✔ Uso avançado de Tailwind CSS (cores, fontes, keyframes)  
✔ Animações interativas com SVGs  
✔ Formulário funcional visualmente  
✔ Layout limpo, legível e atraente  

---

## Possíveis Melhorias

- Implementar validação real do email e submissão a backend  
- Adicionar feedback visual após inscrição  
- Tornar animações mais acessíveis para dispositivos móveis  
- Inserir efeitos adicionais no fundo ou SVGs para maior dinamismo  

---

## Conclusão

O projeto demonstra **uma landing page profissional** com Tailwind CSS, combinando:

- Design responsivo
- Experiência do usuário aprimorada
- Interatividade com animações customizadas

É um ótimo exemplo de uso de Tailwind para criar interfaces modernas e elegantes sem depender de frameworks adicionais.

<img width="1109" height="567" alt="Image" src="https://github.com/user-attachments/assets/669b0590-f844-45f4-9a2d-972f1fea6aca" />
