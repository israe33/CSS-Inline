🧠 O que estou aprendendo

Neste exemplo, estou praticando o uso de CSS Inline, uma das formas de aplicar estilos em elementos HTML. Embora seja uma técnica válida, ela não é a mais recomendada para projetos maiores.

Exemplo com CSS Inline:

<h2 style="background-color: aquamarine;">Um subtítulo</h2>
<p style="color: blueviolet;">Texto com estilo inline</p>

❌ Por que não é recomendado usar CSS Inline?

🔸 Mistura conteúdo e estilo: o HTML deve ser responsável apenas pela estrutura do conteúdo, e o CSS deve cuidar da aparência.

🔸 Difícil manutenção: quando você precisa mudar a cor de vários elementos, tem que fazer isso um por um.

🔸 Poluição visual: o código HTML fica “poluído”, confuso e mais difícil de ler.

🔸 Falta de reaproveitamento: não é possível reaproveitar estilos como faríamos com classes em um arquivo CSS separado.

✅ Boa prática

O ideal é usar CSS externo ou interno (dentro da tag <style> no <head>). Isso torna o código mais limpo, organizado e fácil de manter.

HTML:

<h2 class="subtitulo">Um subtítulo</h2>
<p class="paragrafo">Texto com estilo aplicado via classe CSS</p>

CSS (em um arquivo separado ou dentro da tag <style>):

.subtitulo {
    background-color: aquamarine;
}

.paragrafo {
    color: blueviolet;
}

📘 Conclusão

Mesmo que o CSS inline funcione e seja útil em casos pontuais, ele não é indicado para projetos maiores. Ao separar o CSS do HTML, ganhamos:

📌 Mais organização

📌 Facilidade de manutenção

📌 Reaproveitamento de estilos

📌 Um código mais limpo e profissional


