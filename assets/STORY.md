# Mapa narrativo: quarto tech (README)

Ordem de leitura visual e o que cada cena representa:

1. **hero.svg** — Entrada no quarto: teto, lâmpada, janela para a cidade, mesa com setup completo (mesma identidade do perfil).
2. **about-scene.svg** — Parede de trabalho: monitores com temas arquitetura / cloud / dados (contexto antes da lista "Sobre mim").
3. **stack-scene.svg** — Bancada de engenharia: racks e etiquetas LANG / API / INFRA (prelúdio da grade de skillicons).
4. **stats-section.svg** — Rack de telemetria na parede (dados antes dos cards SVG).
5. **trophies-scene.svg** — Vitrine arcade / troféus (prelúdio dos trophies remotos).
6. **snake-frame.svg** — Trilho de dados animado (metáfora do cabo de energia antes da cobrinha).
7. **footer.svg** — Luz baixa, horizonte e encerramento da sessão.

Paleta fixa: `#0d1117` `#1a1f3a` `#282a36` `#44475a` `#ff79c6` `#8be9fd` `#bd93f9` `#50fa7b` `#f1fa8c` `#6272a4`.

Acessibilidade: cada SVG tem `<title>` e `<desc>`. Animações são SMIL (GitHub renderiza); `prefers-reduced-motion` no `hero.svg` cobre classes CSS listadas lá — outros ficheiros mantêm animação nativa (limitação comum em README estático).
