# Requisitos Não Funcionais

| ID    | Tipo | Requisito | Prioridade |
| :---: | :--- | :-------- | :--------: |
| RNF01 | Usabilidade | A interface do sistema deve ser intuitiva e fácil de usar para pequenos produtores rurais. | Alta |
| RNF02 | Desempenho | O tempo de carregamento das análises e do dashboard não deve exceder 5 segundos em condições normais de uso. | Alta |
| RNF03 | Disponibilidade | O sistema deve estar disponível 24/7 com no máximo 1% de inatividade anual. | Alta |
| RNF04 | Escalabilidade | A arquitetura deve suportar crescimento de usuários e volume de dados sem degradação perceptível (ex: +5x usuários ativos). | Alta |
| RNF05 | Segurança | Dados pessoais, financeiros e de commodities devem ser protegidos com criptografia em trânsito (TLS) e em repouso. | Alta |
| RNF06 | Compatibilidade | Compatível com navegadores modernos (Chrome, Firefox, Edge, Safari) e responsivo em dispositivos móveis. | Alta |
| RNF07 | Confiabilidade | Dados de preços e mercado devem ser atualizados em tempo quase real (baixa latência) ou nos intervalos definidos pelas fontes. | Alta |
| RNF08 | Manutenibilidade | Código organizado e documentado (padrões de estilo, README técnico, >80% módulos com comentários significativos). | Média |
| RNF09 | Suporte | Resposta a solicitações de suporte em até 24 horas úteis. | Média |
| RNF10 | Recuperabilidade | Procedimentos de backup e restauração para evitar perda de dados (RPO ≤ 24h / RTO ≤ 4h). | Alta |
| RNF11 | Acessibilidade | Conformidade com diretrizes WCAG (nível AA quando aplicável). | Média |
| RNF12 | Conformidade | Atendimento à LGPD quanto a consentimento, armazenamento e tratamento de dados pessoais. | Alta |