# sistema-eleicao-votacao-quarkus
Um sistema de eleição e votação utilizando Quarkus.

1. Quarkus: Utilizado como o framework principal para o desenvolvimento do sistema de eleição. Quarkus é conhecido por sua eficiência e capacidade de criar aplicativos Java nativos da nuvem, o que é ideal para aplicativos que precisam de alta escalabilidade e baixo consumo de recursos.
2. Docker: Usado para criar contêineres para cada componente do sistema, incluindo o election-management, result-app e voting-app. Isso facilita a implantação e o gerenciamento do sistema, garantindo que ele seja executado de forma consistente em diferentes ambientes.
3. MariaDB: Utilizado como o banco de dados principal para armazenar informações sobre candidatos, eleições e resultados. MariaDB é uma escolha popular para aplicativos devido à sua confiabilidade e compatibilidade com o MySQL.
4. Traefik: Usado como um proxy reverso para rotear o tráfego para os diferentes componentes do sistema. Traefik facilita o balanceamento de carga e o roteamento de tráfego, garantindo que o sistema seja escalável e resiliente.
5. Redis: Utilizado como um cache para armazenar temporariamente informações frequentemente acessadas, como resultados de eleições anteriores e estatísticas de votação. Isso ajuda a melhorar o desempenho do sistema, reduzindo a carga no banco de dados principal.
6. Graylog: Usado para coletar e analisar logs de diferentes componentes do sistema, permitindo que os desenvolvedores monitorem o desempenho e identifiquem possíveis problemas.
7. OpenSearch: Utilizado para realizar pesquisas avançadas nos dados do sistema, como resultados de eleições anteriores e informações sobre candidatos. OpenSearch fornece recursos poderosos de pesquisa e análise de dados.
8. MongoDB: Usado para armazenar dados não relacionais, como registros de votos individuais e preferências do eleitor.
9. Jaeger Tracing: Usado para rastrear e monitorar o desempenho do sistema, identificando gargalos e otimizando a performance.
10. JDK: Essencial para o desenvolvimento em Java, fornecendo as ferramentas necessárias para compilar, depurar e executar o código Java.
11. JUnit: Utilizado para escrever testes unitários para garantir a qualidade do código e a funcionalidade correta do sistema de eleição.
12. Test Containers: Usado para criar contêineres Docker para os testes unitários, garantindo um ambiente consistente para testes automatizados.
13. Hibernate: Utilizado como o ORM para mapear objetos Java para o banco de dados MariaDB, simplificando o acesso e a manipulação dos dados.
14. Flyway: Usado para gerenciar as migrações de banco de dados, garantindo que o esquema do banco de dados seja atualizado de forma consistente com as mudanças no código-fonte da aplicação.
