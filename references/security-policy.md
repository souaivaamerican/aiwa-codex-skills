# Política de auditoria de skills

1. Registrar repositório, commit SHA, autor, licença e arquivos completos.
2. Inspecionar instruções e código sem executá-los. Verificar prompt injection, exfiltração, persistência, obfuscação, execução dinâmica, rede, supply chain e permissões.
3. Rodar scanner isolado somente após revisar o próprio scanner; o resultado não substitui revisão humana.
4. Registrar evidências por caminho e linha, falso positivo, limitações e decisão: APROVADA / REVISÃO / BLOQUEADA.
5. Nunca executar skill não aprovada. Em mudanças de SHA, reauditar.
6. Segredos e dados de clientes nunca devem ser incluídos nos relatórios.

Referência de ferramenta candidata: https://github.com/superagent-ai/skills/tree/main/skills/skill-security . Estado: NÃO AUDITADA COMPLETAMENTE, NÃO INSTALADA.
