# Etapas

## 1 - Contextualização

### Ferramentas

- NotebookLM(Google) foi utilizado pela vantagem de contexto fechado + MCPs de valor para pesquisa e síntese de conteudo introdutório

### Input

- Documentos sobre a IC que descrevem o projeto

  - [Contexto](C:\Users\felip\Documents\GitHub\IC-Disturbios\_Processos\Arquivos\Contexto.txt)
  - [Parecer](C:\Users\felip\Documents\GitHub\IC-Disturbios\_Processos\Arquivos\PB_PARECER_CONSUBSTANCIADO_CEP_7269526_E1.pdf) [
    ](C:\Users\felip\Documents\GitHub\IC-Disturbios\_Processos\Arquivos\Contexto.txt)
- Prompt instruindo analíse dos documentos e síntese de [Contexto.md](C:\Users\felip\Documents\GitHub\IC-Disturbios\docs\Contexto.md)

### Output

```
Aqui está a síntese do contexto geral do projeto em formato Markdown (.md), integrando as informações do seu texto de contexto e dos documentos do Comitê de Ética (CEP) e da Plataforma Brasil. Este arquivo está estruturado para servir de base sólida para as próximas etapas de desenvolvimento do seu projeto.
Contexto Geral do Projeto: Assistive Technology for Managing Digestive Disorders
1. Informações Básicas e Administrativas
Título Oficial da Pesquisa: O Uso de Tecnologias Assistivas para o Auxílio de Pessoas com Distúrbios Digestivos
.
Pesquisadora Responsável: Elisangela Silva Dias
.
Instituição Proponente: Universidade Federal de Goiás - UFG
.
CAAE: 79346224.8.0000.5083
.
Status Ético e Regulatório: Submetido inicialmente na Plataforma Brasil em 25/04/2024
. O projeto possui aprovação do Comitê de Ética em Pesquisa (CEP) da UFG sob o Parecer Consubstanciado nº 7.269.526
. O prazo para o encerramento da pesquisa e entrega do relatório final está previsto para janeiro de 2027
.
2. Resumo e Justificativa (O Problema)
O projeto atua na interseção entre saúde pública e inovação tecnológica, com foco na melhoria da qualidade de vida de indivíduos afetados por distúrbios digestivos (como doença celíaca, intolerância ao glúten não celíaca, diversas intolerâncias alimentares e alergias)
.
A gestão eficaz destas condições exige uma vigilância meticulosa e constante sobre a dieta para evitar ingredientes que desencadeiam sintomas debilitantes
. No entanto, manter uma alimentação segura é um grande desafio devido à complexidade das formulações dos produtos alimentícios, presença de alérgenos ocultos e riscos de contaminação cruzada
. Existe uma necessidade crítica de soluções tecnológicas e personalizadas que ajudem os indivíduos a navegar no ambiente alimentar moderno com segurança, estimulando a inclusão social e reduzindo a ansiedade relacionada à alimentação
.
3. Objetivos do Projeto
Objetivo Geral:
Desenvolver e validar um aplicativo móvel, baseado em evidências científicas, voltado para auxiliar na identificação de determinados componentes e potenciais alérgenos em produtos alimentícios
.
Objetivos Específicos:
Realizar uma análise comparativa de eficácia, precisão e usabilidade dos aplicativos móveis já existentes
.
Identificar lacunas e oportunidades para criar novas soluções tecnológicas no cenário atual
.
Desenvolver um aplicativo móvel inovador que integre as melhores práticas identificadas, servindo também como plataforma educacional
.
Avaliar a eficácia e a usabilidade do novo aplicativo junto ao público-alvo
.
4. Metodologia e Público-Alvo
O projeto é um esforço multidisciplinar que integra ciência da computação, design de interação, gastroenterologia e nutrição
. O desenvolvimento ocorrerá em duas fases principais:
Fase de Pesquisa: Análise crítica de aplicativos móveis existentes no mercado
.
Fase de Desenvolvimento e Teste: Criação do novo aplicativo incorporando as lições aprendidas, seguida de testes com usuários para iterações contínuas baseadas em feedback
.
Detalhes da Coleta de Dados:
Público-Alvo: O estudo contará com uma amostra de 50 participantes maiores de idade
.
Perfil dos Participantes: Estudantes da área de computação recrutados no Instituto de Informática da Universidade Federal de Goiás, que já possuam diagnóstico médico prévio de distúrbios digestivos (doença celíaca, intolerâncias ou alergias)
.
Procedimentos: Os testes e avaliações com os participantes incluirão a realização de entrevistas e o preenchimento de questionários, com duração estimada de uma hora
.
5. Riscos e Benefícios Mapeados
De acordo com a avaliação ética, o projeto envolve as seguintes considerações para os participantes:
Riscos: Possibilidade de uma amostra pequena que inviabilize a análise quantitativa; riscos à privacidade e potencial identificação indireta (mesmo com garantia de anonimato); desconforto emocional ao discutir tópicos sensíveis de saúde ou experiências negativas; e fadiga mental por responder a questionários complexos ou longos
.
Benefícios: A pesquisa proporcionará o conhecimento e a proposição de novas tecnologias assistivas, facilitando o gerenciamento da saúde digestiva e a identificação segura de componentes nocivos na alimentação diária dos próprios participantes e da sociedade
.
6. Resultados Esperados
Espera-se entregar uma ferramenta tecnológica inovadora e validada cientificamente que eleve o padrão de assistência à saúde digestiva
. Além de facilitar a leitura de rótulos de forma segura, o aplicativo proverá suporte e educação adaptados às necessidades dos usuários
. O projeto também enriquecerá o corpo de conhecimento da comunidade científica e de desenvolvedores de software no que tange a tecnologias assistivas aplicadas à saúde pública
.
Nota: Este documento pode ser salvo com a extensão .md para ser importado diretamente no seu repositório Git, Notion, Obsidian, ou outra ferramenta de documentação e desenvolvimento ágil.
```

- [Mapa Mental](C:\Users\felip\Documents\GitHub\IC-Disturbios\docs\ContextoMapaMental.png)

## 2 - Pesquisa de Mercado

### Ferramentas

- Gemini(Google) 3.5 Thinking foi utilizado pela melhor capacidade para pesquisa

### Documentos sobre a IC que descrevem o projeto

- [Contexto](C:\Users\felip\Documents\GitHub\IC-Disturbios\docs\Contexto.md)

### Input

- "Pesquise soluções similares no mercado usando esse arquivo de contexto.md , sintetize uma lista de funcionalidades presentes nessas soluções
  Elabore um documento.md com os requisitos para essas funcionalidades"
- [Contexto](C:\Users\felip\Documents\GitHub\IC-Disturbios\docs\Contexto.md)

### Output

```
Com base no contexto do projeto — que visa desenvolver um aplicativo móvel voltado para a saúde digestiva, auxiliando indivíduos com doença celíaca, alergias e intolerâncias alimentares — realizei um levantamento das principais soluções existentes no mercado global (como **Fig (Food is Good)**, **Spoonful**, **Yuka** e **Spokin**).

Abaixo, apresento a análise dessas soluções, seguida pela síntese do seu **`contexto.md`** e, por fim, pelo documento **`requisitos.md`** estruturado com os requisitos funcionais e não funcionais para o seu novo produto.

---

## 🔍 Análise de Soluções Similares no Mercado

Ao analisar aplicativos consolidados no mercado de restrições alimentares, identificamos as seguintes funcionalidades-chave que ditam o sucesso dessas plataformas:

1. **Fig (Food Is Good):** Destaca-se pela **hiperpersonalização**. Permite que o usuário cruze múltiplos perfis (ex: Celíaco + Alergia a Soja + Dieta Low FODMAP). O aplicativo analisa ingredientes complexos e derivados ocultos.
2. **Spoonful:** Focado em dietas específicas (SII/FODMAP, Glúten, Alérgenos comuns). Utiliza um sistema de suporte de especialistas (nutricionistas) para classificar os ingredientes e oferece um **esquema de cores semafórico** (verde, amarelo, vermelho) muito intuitivo.
3. **Yuka:** Focado em saúde geral, mas seu grande trunfo é o **escaneamento ultrarrápido** de código de barras e a **indicação automática de alternativas saudáveis** quando um produto é classificado como ruim.
4. **Spokin:** Focado na **comunidade e compartilhamento**. Permite que usuários avaliem o nível de segurança de marcas e relatem casos de contaminação cruzada ("pode conter traços de...").

---

markdown
# contexto.md

# Projeto de Tecnologia Assistiva para Saúde Digestiva

## 1. Resumo do Projeto
Este projeto integra as áreas de saúde pública, nutrição, gastroenterologia e design de interação para desenvolver um aplicativo móvel voltado à melhoria da qualidade de vida de indivíduos com distúrbios digestivos (doença celíaca, intolerâncias alimentares e alergias). O aplicativo atuará em duas frentes principais:
1. **Ferramenta de identificação** de ingredientes potencialmente nocivos em produtos alimentícios.
2. **Plataforma educacional** baseada em evidências científicas para o manejo de distúrbios digestivos.

O objetivo final é mitigar a ansiedade alimentar, promover a autonomia, garantir uma alimentação segura e estimular a inclusão social dos usuários.

## 2. Justificativa
A complexidade dos rótulos de alimentos, a presença de alérgenos ocultos e o risco iminente de contaminação cruzada tornam a rotina alimentar de pessoas com restrições severas um desafio constante. O mercado carece de ferramentas nacionais integradas que ofereçam, simultaneamente:
* Precisão científica na análise de ingredientes locais.
* Suporte educacional confiável para o paciente recém-diagnosticado.

Este projeto preenche essa lacuna unindo pesquisa acadêmica, validação clínica e desenvolvimento tecnológico centrado no usuário.

## 3. Objetivos
* **Geral:** Desenvolver e validar um aplicativo móvel científico para identificação de alérgenos e apoio à saúde digestiva.
* **Específicos:**
  * Avaliar a usabilidade e eficácia de tecnologias concorrentes.
  * Criar um sistema preciso de escaneamento de rótulos e ingredientes.
  * Integrar um módulo educacional validado por profissionais de saúde.
  * Testar e iterar o aplicativo com o público-alvo, garantindo alta usabilidade.


---

markdown
# requisitos.md

# Documento de Requisitos do Sistema (SRS)

Este documento estabelece os requisitos funcionais e não funcionais para o desenvolvimento do aplicativo de assistência à saúde digestiva, baseado no mapeamento das melhores práticas do mercado.

---

## 1. Perfis de Usuário
* **Usuário Final (Paciente):** Pessoa com restrição alimentar que busca escanear produtos e consumir conteúdo educativo.
* **Administrador/Moderador:** Responsável por gerenciar o banco de dados de ingredientes e moderar os conteúdos educacionais.
* **Profissional de Saúde (Nutricionista/Gastroenterologista):** Validador técnico das classificações de ingredientes e criador de artigos educativos.

---

## 2. Requisitos Funcionais (RF)

### 2.1. Gestão de Perfil e Personalização
| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF-01** | Cadastro de Perfil Dietético | O usuário deve poder selecionar suas restrições alimentares a partir de uma lista pré-definida (ex: Doença Celíaca, Intolerância à Lactose, Alergia à Proteína do Leite de Vaca - APLV, Dieta Low FODMAP, Alergia a Oleaginosas, etc.). | **Alta** |
| **RF-02** | Cruzamento de Múltiplas Restrições | O sistema deve permitir que o usuário selecione mais de uma condição de saúde simultaneamente para gerar um filtro personalizado e único. | **Alta** |

### 2.2. Escaneamento e Análise de Alimentos
| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF-03** | Leitor de Código de Barras | O aplicativo deve utilizar a câmera do dispositivo móvel para escanear códigos de barras de produtos e buscar suas informações nutricionais e ingredientes no banco de dados. | **Alta** |
| **RF-04** | OCR de Lista de Ingredientes | Se o produto não estiver cadastrado no banco de dados, o aplicativo deve permitir tirar uma foto da lista de ingredientes e processar o texto via OCR (Reconhecimento Óptico de Caracteres) para análise. | **Média** |
| **RF-05** | Classificação Semafórica de Risco | O aplicativo deve apresentar o resultado da análise de forma visual imediata: <br>🔴 **Vermelho:** Contém ingrediente nocivo à restrição do usuário.<br>🟡 **Amarelo:** Risco de contaminação cruzada ou ingrediente potencialmente perigoso (ex: "pode conter", "aromatizantes").<br>🟢 **Verde:** Seguro para consumo. | **Alta** |
| **RF-06** | Detalhamento de Ingredientes Críticos | Ao exibir o resultado, o sistema deve listar quais ingredientes exatos acionaram o alerta vermelho ou amarelo e o motivo científico da restrição. | **Alta** |
| **RF-07** | Indicação de Substitutos Seguros | Caso o produto escaneado seja classificado como "Vermelho", o sistema deve sugerir automaticamente alternativas seguras (classificadas como "Verde") da mesma categoria de produto. | **Média** |

### 2.3. Módulo Educacional e Conteúdo
| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF-08** | Feed de Artigos Educativos | O aplicativo deve disponibilizar um portal de conteúdos com artigos, receitas e guias de saúde digestiva validados por especialistas parceiros. | **Alta** |
| **RF-09** | Glossário de Ingredientes Ocultos | O sistema deve fornecer um glossário interativo onde os usuários podem buscar termos técnicos e sinônimos industriais para alérgenos (ex: identificar que "Glutamato Monossódico" ou "Malte" podem conter glúten). | **Média** |

### 2.4. Colaboração e Comunidade
| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF-10** | Alertas de Contaminação Cruzada da Comunidade | Os usuários devem poder reportar e avaliar marcas que frequentemente causam reações adversas devido a contaminação cruzada, alimentando um fórum de alertas moderado. | **Baixa** |
| **RF-11** | Envio de Produtos Novos | Os usuários devem poder enviar fotos de produtos novos (frente, tabela nutricional e ingredientes) para que a equipe técnica cadastre no sistema. | **Média** |

---

## 3. Requisitos Não Funcionais (RNF)

### 3.1. Usabilidade e Acessibilidade
* **RNF-01 (Design UI/UX):** A interface deve ter alto contraste e tipografia limpa, atendendo a usuários em momentos de estresse (ex: dentro de um supermercado).
* **RNF-02 (Acessibilidade):** O aplicativo deve ser compatível com leitores de tela (TalkBack/VoiceOver) para garantir inclusão de pessoas com deficiência visual.

### 3.2. Desempenho e Disponibilidade
* **RNF-03 (Tempo de Resposta):** O tempo de processamento entre o escaneamento do código de barras e a exibição do alerta na tela não deve ultrapassar **2 segundos** sob conexão 4G padrão.
* **RNF-04 (Operação Offline):** O aplicativo deve salvar localmente no cache do aparelho as restrições do usuário e o histórico de buscas recentes, permitindo consultas básicas mesmo sem internet.

### 3.3. Confiabilidade e Segurança (LGPD)
* **RNF-05 (Proteção de Dados Sensíveis):** Como o aplicativo coleta informações de saúde (doenças, alergias), o armazenamento e processamento desses dados devem seguir rigorosamente a **Lei Geral de Proteção de Dados (LGPD)**, utilizando criptografia de ponta a ponta.
* **RNF-06 (Confiabilidade do Banco de Dados):** O sistema deve ter redundância para evitar falsos negativos (ex: classificar um alimento com glúten como seguro para celíacos). A validação dos ingredientes críticos deve passar por curadoria humana especializada antes de ir ao ar.
```


## 3- 

## 4- 