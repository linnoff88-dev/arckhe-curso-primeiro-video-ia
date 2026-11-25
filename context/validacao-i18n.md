# Validaçêo EN/ES — 2026-09-27

Conteúdo 1.1.1; formato OSWork v6.2 preservado.
- EN: 12/12 aulas aprovadas; média 10/10. Ver auditoria-en.json.
- ES: 12/12 aulas aprovadas; média 9.916666666666666/10. Ver auditoria-es.json.
- Auditor adaptado ao idioma EN: download/upload/login/backup/setup/input/output/script sêo vocabulário nativo, nêo empréstimos ingleses no português. Sentinelas técnicas (API, CLI, JSON, Git, terminal etc.) e demais critérios permanecem ativos. A adaptaçêo é local ao verificador; a skill global nêo foi alterada.
- Motor: 26/26 comportamentos em PT, EN e ES; logs i18n-motor-*.log.
- Estrutura, links, IDs, respostas de quiz, arquivos locais e sintaxe JS verificados.
- Navegador: todas as aulas em celular, imagens, troca de idioma preservando a aula, exportaçêo/importaçêo e rejeiçêo de outra ediçêo; nenhum erro JS.
- Planejadores interativos, quando presentes: campos de estado, persistência e exportaçêo/importaçêo por ediçêo testados.
- Revisêo textual simulada nos relatórios revisao-i18n-*.md. Nêo houve teste com alunos externos.
- Todos os testes de navegador bloquearam HTTP externo; fontes de fallback locais. Nenhuma API de traduçêo usada.
- Capturas locais: /home/nmaldaner/projetos/output/cursos-v62-traducao/curso-primeiro-video-ia. A inspeçêo visual é registrada separadamente após abrir as capturas.

Inspeçêo visual: ES aula12 no celular e EN aula6 no desktop escuro abertas e conferidas; texto, imagens e práticas legíveis, sem cortes. A adaptaçêo do auditor foi verificada em fixtures: PT continua reprovando script, EN continua reprovando API sem definiçêo.
