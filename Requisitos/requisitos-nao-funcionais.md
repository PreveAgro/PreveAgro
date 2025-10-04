# Requisitos Não Funcionais

| ID    | Requisito | Prioridade |
| :---: | :-------- | :--------: |
| RNF01 | O painel principal (dashboard) deve carregar todos os seus componentes visuais e dados em no máximo 5 segundos em uma conexão de internet móvel (4G). | Alta |
| RNF02 | Todas as senhas de usuário devem ser armazenadas no banco de dados de forma criptografada (utilizando hashing como bcrypt) para impedir o acesso não autorizado. | Alta |
| RNF03 | Um novo usuário deve conseguir realizar o cadastro, adicionar sua primeira commodity e visualizar a análise preditiva em menos de 5 minutos, sem a necessidade de um tutorial. | Alta |
| RNF04 | O sistema deve ter uma disponibilidade de 99,5% do tempo, com janelas de manutenção planejadas e comunicadas previamente aos usuários. | Alta |
| RNF05 | A aplicação web deve ser totalmente funcional e visualmente consistente nas duas últimas versões dos navegadores Google Chrome, Mozilla Firefox e Microsoft Edge. | Média |
| RNF06 | A interface deve se adaptar para uma visualização e uso adequados em três tamanhos de tela: desktop (acima de 1200px), tablet (em torno de 768px) e smartphone (em torno de 480px). | Alta |
| RNF07 | Os dados de cotações e tendências devem ser atualizados a partir de fontes de mercado confiáveis pelo menos uma vez a cada 24 horas para garantir a precisão das análises. | Alta |
| RNF08 | O código-fonte deve ser documentado e modularizado, permitindo que um novo desenvolvedor consiga entender e corrigir um bug de baixa complexidade em menos de 4 horas. | Média |
| RNF09 | A aplicação deve seguir as diretrizes do WCAG 2.1 (nível AA), garantindo que elementos como contraste de cores e navegação por teclado sejam acessíveis. | Média |
| RNF10 | A arquitetura do sistema deve suportar um aumento de 50% no número de usuários ativos simultaneamente sem degradação perceptível no desempenho. | Média |