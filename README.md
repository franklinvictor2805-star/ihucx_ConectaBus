# ConectaBus — Protótipo de Baixa Fidelidade


---

# 📱 Sobre o Projeto

O ConectaBus é um aplicativo de mobilidade urbana criado para unificar os principais meios de transporte da cidade em uma única plataforma.

O sistema permite que o usuário:
- Planeje rotas rapidamente.
- Visualize a lotação dos veículos em tempo real.
- Utilize bilhete digital via QR Code.
- Receba alertas de incidentes.
- Acione um botão de segurança em emergências.

O protótipo foi desenvolvido utilizando conceitos de IHC (Interação Humano-Computador) e UX Design.

---

# 🎯 Contexto de Uso

O aplicativo foi pensado para pessoas em movimento, principalmente usuários que:
- Estão correndo para não perder ônibus ou metrô.
- Utilizam transporte público diariamente.
- Precisam tomar decisões rápidas.
- Estão em ambientes movimentados ou lotados.
- Precisam usar o celular com apenas uma mão.

O foco principal foi reduzir a carga cognitiva e facilitar a navegação rápida.

---

# 🧠 Decisões de UX

## Prioridade das Informações
As informações mais importantes aparecem em destaque:
- Tempo de chegada do transporte.
- Status de lotação.
- Melhor rota disponível.

O tempo de chegada foi priorizado acima do número da linha, pois influencia diretamente a tomada de decisão do usuário.

---

## Botões Grandes
Os botões possuem tamanho maior para:
- Facilitar cliques rápidos.
- Evitar erros de toque.
- Melhorar uso com apenas um polegar.

---

## Navegação Simples
O fluxo do aplicativo foi reduzido ao mínimo necessário:
Busca → Rotas → Mapa → Pagamento → Acompanhamento.

Isso reduz confusão e acelera ações.

---

## Cores e Status Visuais
A lotação dos veículos utiliza cores intuitivas:
- 🟢 Verde → Vazio
- 🟡 Amarelo → Moderado
- 🔴 Vermelho → Lotado

Isso facilita decisões rápidas sem necessidade de leitura extensa.

---

# ♿ Acessibilidade

O protótipo foi desenvolvido pensando em acessibilidade e praticidade.

## Recursos utilizados:
- Botões grandes.
- Alto contraste.
- Pouca quantidade de texto.
- Navegação simplificada.
- Ícones intuitivos.
- Informações organizadas por prioridade.
- Compatibilidade com uso em movimento.

---

## Informações de acessibilidade nos veículos
Os veículos exibem:
- ♿ Rampas de acesso.
- 🪑 Espaço para cadeirantes.
- ❄️ Ar-condicionado.

---

# 🚨 Prevenção de Erros

Em sistemas de mobilidade, um erro pode fazer o usuário perder o transporte ou seguir para o local errado.

Para reduzir esses problemas:
- O destino é confirmado antes da navegação.
- As rotas possuem categorias:
  - Mais rápido
  - Mais barato
  - Menos caminhada
- O usuário visualiza o trajeto antes de iniciar.
- O QR Code possui validação visual.
- Alertas importantes aparecem em destaque.

---

# 📲 Telas Desenvolvidas

## 1. Tela de Busca
Permite pesquisar destinos e acessar locais frequentes.

## 2. Resultado de Rotas
Mostra diferentes opções de trajeto.

## 3. Mapa do Percurso
Exibe o caminho em tempo real.

## 4. Carteira Digital (Wallet)
Mostra saldo e QR Code para pagamento.

## 5. Detalhes do Veículo
Apresenta:
- Tempo de chegada.
- Lotação.
- Recursos de acessibilidade.

## 6. Alertas de Incidentes
Notificações sobre:
- Greves.
- Linhas interrompidas.
- Atrasos.

## 7. Botão de Segurança
Permite reportar:
- Assédio.
- Furto.
- Situações de perigo.

---

# 🌙 Desafio Extra

## Modo Noturno
Foi pensado um modo escuro para:
- Reduzir brilho.
- Evitar ofuscamento.
- Melhorar uso noturno.

---

## Modo Offline
Caso o usuário perca conexão:
- A última rota permanece disponível.
- O QR Code continua acessível.
- O app informa ausência de sinal.

---

# 🔄 Fluxo de Navegação

```txt
Busca de Rota
      ↓
Resultado de Rotas
      ↓
Mapa do Percurso
      ↓
Carteira Digital
      ↓
Detalhes do Veículo
