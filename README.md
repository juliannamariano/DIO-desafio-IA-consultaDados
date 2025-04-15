# 🔍 Projeto: Pesquisa Cognitiva com Azure AI Search

Este repositório contém o aprendizado obtido com a ferramenta **Azure AI Search**, parte da trilha educacional da DIO. Aqui você encontra um passo a passo de como configurar uma pesquisa cognitiva, além dos principais insights e possibilidades de aplicação da tecnologia no mercado.


## 🧠 O que é o Azure AI Search?

O Azure AI Search é um serviço de **busca inteligente hospedado na nuvem**, capaz de realizar **pesquisas complexas** com uso de **inteligência artificial**, **extração de texto**, **reconhecimento de entidades**, **tradução automática**, entre outros.


## ⚙️ Passo a Passo de Configuração

1. **Criar um Recurso no Azure**
   - Acesse o portal do Azure.
   - Vá em "Criar um recurso" > Pesquise por "Azure AI Search".
   - Preencha com:
     - Nome do serviço
     - Grupo de recursos
     - Região
     - Plano de tarifa (Free F tier se disponível)

2. **Criar um Indexador de Pesquisa**
   - Selecione “Importar dados”.
   - Fonte de dados: Blob Storage ou SQL.
   - Selecione o container desejado.
   - Configure um indexador para processar e enriquecer os dados.

3. **Configurar um Index**
   - O index define os campos que podem ser pesquisados (nome, descrição, etc).
   - Marque as propriedades `searchable`, `filterable`, `sortable` conforme a necessidade.

4. **Aplicar Habilidades Cognitivas (Opcional)**
   - Adicione habilidades como:
     - OCR (reconhecimento de texto em imagens)
     - Reconhecimento de entidade
     - Detecção de idioma
     - Tradução
     - Extração de palavras-chave

5. **Visualizar Resultados**
   - Após a indexação, vá para “Search Explorer” e realize buscas simples como:
     ```
     search=hotel OR beach
     ```
   - Você verá a resposta JSON com os documentos relevantes.

## 💡 Insights e Possibilidades

- **Ferramentas que se beneficiam do Azure AI Search:**
  - E-commerce com busca inteligente
  - Portais de documentos com OCR
  - Bibliotecas digitais
  - Sistemas de RH com análise semântica de currículos
  - Chatbots que consultam bases de conhecimento
  - Aplicações multilíngues com tradução automática

- **Aprendizados:**
  - Integração prática com recursos cognitivos da Azure.
  - Entendimento do ciclo de indexação e enriquecimento de dados.
  - Importância de um schema de index bem planejado.
  - Valor de uma busca semântica em dados não estruturados.


## 🧑‍💻 Autora

**Julianna Mariano**  
Estudante de Sistemas de Informação na FIAP  
Apaixonada por inovação, tecnologia e IA 🤖✨  




