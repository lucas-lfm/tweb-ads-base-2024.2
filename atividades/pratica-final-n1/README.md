# Prática Final da N1: HTML e CSS básicos

> Nesta atividade vamos trabalhar os conceitos de:
> - ***Tags HTML básicas, imagens e tabelas***
> - ***Conceitos básicos de CSS*** — Níveis de definição, seletores, tipografia, cores e backgrounds
> - ***Elementos em Bloco e em Linha (block e inline)***
> - ***Box Model CSS*** — propriedades `margin`, `padding`, `border`, `width` e `height`
> - ***HTML semântico***

> Esta atividade se baseia na [atividade 03](./../atv03/) (podem pegar o código da atividade 03 como base). O código corrigido (base) para a atividade 03, está disponível na pasta [codigo-base](./codigo-base/).

[Acesse aqui](./../../materiais/slides/) o material de estudos da disciplina para revisar/estudar os conceitos que serão abordados nesta prática.

<a id="inst"></a>
## Instruções para Realização da Atividade

- Esta atividade tem o objetivo de exercitar todo o conteúdo trabalhado na etapa N1, bem como trabalhar na prática com cores e conceitos importantes para a definição de layouts, como: modos de exibição de elmentos (block e inline), Box Model CSS e HTML semântico.

- A atividade consiste em replicar o resultado apresentado na imagem abaixo, que traz um exemplo de página pessoal para organização dos estudos.

<div align="center">
    <img src="./img-instrucoes/resultados.png">
</div>

- Você deve usar tags semânticas para a definição dos elementos de layout (`header`, `nav`, `main`, `section` e `footer`, pelo menos);
    - Acesse [aqui](./../../materiais/slides/tweb-04-avancando-html.pdf) o material sobre HTML semântico

- Define adequadamente os espaçamentos e tamanho dos elementos, usando as propriedades do Box Model CSS
    - Acesse [aqui](./../../materiais/slides/tweb-05-css_box-model_posicionamento.pdf) o material sobre esse assunto
    - Postei um vídeo lá no TikTok sobre esse assunto: [link para o vídeo](https://www.tiktok.com/@prof_lucasmendes/video/7445768369220963589?is_from_webapp=1&sender_device=pc&web_id=7440856054412248631)

- Use a tag `section` para separar de forma lógica o conteúdo. Por exemplo, defina uma `section` para cada parte (seção) do conteúdo da página (Apresentação, Disciplinas, etc);

- Use a tag `header` para definir o cabeçalho da página, com o banner (disponível [aqui](./img-instrucoes/banner.png)) e o menu de navegação;

- Para o menu de navegação, utilize a tag `nav`;

- Para a última seção da página (rodapé), utilize a tag `footer`;

- Para a definição das cores, utilize a notação hexadecimal (exemplo: `background-color: #242424`);
    - As cores podem ser definidas usando o sistema `RGB (Red, Green, Blue)`
    - Para cada cor pode ser definido um nível de intensidade, de 0 a 255 (em decimal), ou de 00 a FF (em hexadecimal)
    - Para inidicar um código hexadecimal, use o `#` antes do código numérico da cor
    - Veja o material sobre cores para mais detalhes (acesse [aqui](./../../materiais/slides/tweb-06-css_cores_background.pdf))

- ***Obsevações Importantes***
    - Utilize CSS externo (arquivo `.css` separado)
    - Todas as definições de aparência visual devem ser especificadas no CSS
        - Exemplo: no lugar de usar a tag `<b>` para deixar um texto em negrito, use a propriedade `font-weight: bold` (com valor bold).
