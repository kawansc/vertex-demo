# VERTEX
## Duas línguas, uma conexão.

Site oficial: https://overtex.com.br

---

## 1. Sobre o projeto

O VERTEX é um projeto estudantil de tecnologia e acessibilidade que busca aproximar pessoas surdas e ouvintes por meio de soluções digitais voltadas à comunicação entre a Língua Brasileira de Sinais (Libras) e a língua portuguesa.

A proposta é oferecer uma experiência de comunicação de mão dupla: permitir que sinais realizados em Libras sejam analisados e apresentados em português, além de possibilitar que mensagens digitadas ou faladas sejam convertidas em Libras por meio de um avatar.

O projeto nasceu da ideia de utilizar a tecnologia como instrumento de inclusão, reduzindo barreiras de comunicação e tornando a interação entre diferentes formas de expressão mais acessível.

## 2. Objetivo

Desenvolver uma plataforma que facilite a comunicação entre pessoas surdas e ouvintes, utilizando recursos de visão computacional, inteligência artificial, reconhecimento de movimentos, voz e representação visual de sinais.

O VERTEX busca evoluir continuamente, ampliar os recursos disponíveis e oferecer uma experiência acessível em diferentes dispositivos.

## 3. Missão, visão e valores

### Missão
Promover a inclusão por meio da tecnologia e tornar a comunicação entre pessoas surdas e ouvintes mais acessível e eficiente.

### Visão
Ser uma referência em tecnologia para acessibilidade, desenvolvendo soluções inovadoras que contribuam para eliminar barreiras de comunicação.

### Valores
- Inclusão;
- Acessibilidade;
- Inovação;
- Ética;
- Empatia;
- Excelência;
- Compromisso com o impacto social.

## 4. Como funciona

O VERTEX apresenta dois caminhos principais de comunicação.

### 4.1. Libras para português

1. A pessoa permite o acesso à câmera do dispositivo.
2. O sistema acompanha os movimentos das mãos e identifica pontos utilizados na análise do sinal.
3. Os dados numéricos do movimento são analisados pelo sistema de reconhecimento.
4. O resultado é apresentado em português, podendo ser exibido como texto ou reproduzido por voz.
5. A pessoa pode confirmar ou corrigir o resultado para contribuir com a personalização do reconhecimento no próprio navegador.

O reconhecimento depende das condições de captura, do enquadramento e dos sinais disponíveis no modelo.

### 4.2. Português para Libras

1. A pessoa digita uma mensagem ou utiliza o recurso de voz do navegador.
2. O texto é encaminhado ao processo de tradução para Libras.
3. O avatar apresenta os sinais correspondentes.
4. Quando disponível, a pessoa pode repetir a animação e consultar o catálogo de sinais.

O VERTEX utiliza o avatar oficial do VLibras para representar os sinais. Algumas frases de demonstração possuem sequências locais confirmadas, enquanto outras dependem do serviço de tradução integrado.

## 5. Funcionalidades

Entre os recursos disponíveis na plataforma estão:

- Tradução de sinais capturados pela câmera para português;
- Exibição do resultado em texto;
- Reprodução do resultado em voz;
- Entrada de mensagens por texto;
- Entrada de mensagens por voz, conforme suporte do navegador;
- Apresentação de sinais em Libras por meio do avatar VLibras;
- Consulta e pesquisa no catálogo de sinais;
- Gravação de exemplos personalizados para ensinar sinais ao reconhecimento;
- Confirmação e correção dos resultados apresentados;
- Tutorial interativo para orientar novos usuários;
- Instalação da plataforma pela função de aplicativo web progressivo (PWA), quando compatível;
- Recursos de acessibilidade e suporte ao usuário.

A disponibilidade de cada recurso pode variar conforme o dispositivo, o navegador e os serviços integrados.

## 6. Tecnologias e recursos utilizados

### Desenvolvimento web
- HTML5: estrutura das páginas e dos componentes da plataforma.
- CSS3: estilização, identidade visual e adaptação da interface a diferentes tamanhos de tela.
- JavaScript: lógica da aplicação, interações e integração entre os recursos.

### Visão computacional e reconhecimento
- MediaPipe: acompanhamento dos pontos das mãos diretamente no dispositivo.
- TensorFlow.js: alternativa de processamento e leitura de movimentos no dispositivo.
- VERTEX-MINDS: modelo utilizado no processo de reconhecimento de sinais.
- Câmera e APIs de mídia do navegador: captura autorizada de vídeo para análise.

### Libras e avatar
- VLibras: recurso integrado para apresentação de conteúdos em Libras por meio de avatar.
- Catálogo de sinais: conjunto de glosas e variantes utilizado para consulta e apresentação.
- Referências de movimento: dados utilizados como apoio ao reconhecimento pela câmera.

### Voz e experiência web
- Web Speech API e recursos de voz do navegador: suporte à entrada e à reprodução de voz, conforme compatibilidade.
- Progressive Web App (PWA): permite instalar a plataforma pela interface do navegador em dispositivos compatíveis.
- Armazenamento local do navegador: utilizado para preferências e exemplos personalizados.

## 7. Catálogo de sinais

A plataforma apresenta um catálogo com 22.498 entradas, incluindo glosas e variantes disponibilizadas pelo ecossistema do avatar VLibras.

É importante diferenciar o catálogo de consulta do vocabulário efetivamente reconhecido pela câmera. Nem todas as entradas do catálogo possuem referências adequadas para reconhecimento automático.

As referências sintéticas de movimento não equivalem, por si só, à validação de um sinal com pessoas fluentes em Libras. Por isso, a confirmação e a correção dos resultados são partes importantes da experiência.

## 8. Privacidade e tratamento de dados

O VERTEX foi projetado para reduzir a quantidade de informações necessárias ao funcionamento da plataforma.

De acordo com a política de privacidade do projeto:

- A câmera só é ativada após a ação e a autorização da pessoa usuária.
- O vídeo da câmera é processado no dispositivo e não é enviado ao servidor do VERTEX.
- Para a análise, podem ser enviados pontos numéricos das mãos e, quando disponíveis, medidas de postura, cabeça e expressão.
- O microfone depende de autorização e do suporte do navegador ou sistema operacional.
- Exemplos personalizados e preferências podem ser armazenados localmente no navegador.
- Para apresentar mensagens em Libras, o texto pode ser encaminhado ao serviço público VLibras.
- O projeto declara não vender dados pessoais nem utilizar publicidade direcionada.

Consulte a política completa em:
https://overtex.com.br/privacidade

## 9. Limitações e uso responsável

O VERTEX é uma plataforma em desenvolvimento. O reconhecimento automático pode apresentar erros e depende de fatores como iluminação, enquadramento, velocidade dos movimentos, posição das mãos, variações regionais e limitações do modelo.

A tradução automática não substitui intérpretes profissionais, especialmente em situações médicas, jurídicas, emergenciais ou em outros contextos de alto impacto.

O projeto busca apresentar seus recursos e limitações com transparência, incentivando a confirmação dos resultados e a evolução contínua da tecnologia.

Termos de uso:
https://overtex.com.br/termos

## 10. Acesso à plataforma

Acesse o VERTEX pelo site oficial:

https://overtex.com.br

A plataforma pode ser utilizada pelo navegador. A instalação como aplicativo web depende da compatibilidade do dispositivo e do navegador. Aplicativos nativos para lojas de aplicativos possuem processos próprios de publicação e aprovação.

## 11. Desenvolvimento e participação

O VERTEX foi desenvolvido em grupo. A participação individual do responsável por este repositório demonstrativo envolveu o desenvolvimento da interface e da aplicação web utilizando HTML, CSS e JavaScript.

O projeto foi apresentado em outubro de 2026 e continua sendo desenvolvido com o objetivo de aprimorar a experiência, a acessibilidade e os recursos de comunicação.

## 12. Repositório demonstrativo

Este repositório tem finalidade demonstrativa e não deve ser interpretado como a publicação integral de todo o código-fonte, modelos, dados, serviços ou componentes internos utilizados na plataforma oficial.

A implementação pública de demonstração pode conter apenas partes selecionadas do projeto. Recursos proprietários, modelos, bases de dados, integrações e componentes internos podem não estar disponíveis neste repositório.

Para conhecer e experimentar a plataforma, acesse:
https://overtex.com.br

## 13. Contato e canais oficiais

- Site: https://overtex.com.br
- Instagram: https://www.instagram.com/overtex_ofc/
- E-mail: vertex.kava@gmail.com

---

VERTEX — Duas línguas, uma conexão.
Tecnologia a serviço da expressão e da inclusão.
