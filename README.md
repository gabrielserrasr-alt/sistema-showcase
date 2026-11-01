# Sistema

App de treino e dieta inspirado em Solo Leveling: você vira um "caçador", cumpre as missões do dia e sobe de nível e de rank na vida real. Funciona no navegador do celular e pode ser instalado na tela inicial (PWA).

O código é privado. Este repositório apresenta o produto. As telas usam dados de demonstração.

<table>
  <tr>
    <td><img src="media/inicio.png" alt="Tela inicial com rank e metas do dia" width="260"></td>
    <td><img src="media/missoes.png" alt="Missões diárias concluídas com XP e atributos" width="260"></td>
    <td><img src="media/dieta.png" alt="Plano de nutrição com calorias e macros" width="260"></td>
  </tr>
  <tr>
    <td><img src="media/corrida.png" alt="Corrida com tempo, ritmo e calorias" width="260"></td>
    <td><img src="media/ligas.png" alt="Liga semanal com classificação" width="260"></td>
    <td><img src="media/trofeus.png" alt="Sala de troféus com conquistas em cinco níveis" width="260"></td>
  </tr>
</table>

## O que ele faz

- **Missões diárias:** o treino do dia vira missões, com XP, atributos e sequência de dias.
- **Progressão semanal:** a meta sobe 10% por semana. Com o botão "Não consegui", passa a subir de 1 em 1. Faltar um dia só zera a sequência.
- **Treinos:** biblioteca de treinos prontos e opção de montar o próprio.
- **Câmera:** conta as repetições pelo movimento do corpo, de frente ou de lado.
- **Corrida:** GPS com distância, tempo, ritmo e calorias.
- **Dieta:** calorias, proteína, carbo, gordura e água, com busca de alimentos, código de barras e foto do prato com IA.
- **Ligas e troféus:** ranking semanal com subida e descida de liga, além de conquistas em 5 níveis.
- **Card de treino:** imagem pronta para salvar ou compartilhar quando termina o dia.
- **Lembretes:** notificação diária se as missões não estiverem completas.

## Status

O app está no ar, com uma exceção: o **Premium** ainda não tem pagamento. A tela e os planos existem, mas o botão de assinar só mostra um aviso, e a liberação é manual pelo painel admin.

## Stack

React, TypeScript e Vite no app. Supabase no banco, login e funções. MediaPipe na contagem por câmera. Publicado no Netlify.

## Licença

Todos os direitos reservados © Gabriel Serra da Rosa.
