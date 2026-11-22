# Universidade Federal de Goiás - Instituto de Informática (UFG - INF)

## Especialização em Inteligência Artificial Generativa - AKCIT

Este repositório contém todos os artefatos produzidos durante a concepção e o desenvolvimento do Trabalho de Conclusão (TCC) da Especialização em Inteligência Artificial Generativa da AKCIT (Centro de Competência EMBRAPII em Tecnologias Imersivas).

## Resumo

A conversão de processos descritos em linguagem natural em modelos BPMN 2.0 é morosa e dificulta a documentação contínua. A automação com Grandes Modelos de Linguagem (LLMs) é promissora, mas, em testes preliminares, a instrução geral não produziu estruturas válidas e consistentes. A pesquisa investiga se a Inteligência Artificial Generativa gera diagramas BPMN 2.0 de forma automatizada e consistente a partir de texto, com aplicação na Secretaria de Gestão de Projetos da Universidade Federal do Rio Grande do Norte (SGP/UFRN). O objetivo foi desenvolver um protótipo utilizando Inteligência Artificial Generativa para geração de processos BPMN a partir de descrições em linguagem natural. O protótipo adota arquitetura híbrida: o Qwen2.5-Coder-7B-Instruct, ajustado com LoRA, converte a descrição em JSON intermediário, tratado e validado; um módulo em Python (lxml) transforma o JSON em BPMN 2.0, aberto no Bizagi Modeler e no Camunda Modeler; e a interface em Gradio, no Google Colab, dispensa o manuseio do código. A pesquisa é de desenvolvimento experimental, de abordagem qualitativa. Construiu-se uma base de 23 exemplos com processos modelados pela SGP/UFRN, reservando outros processos para teste. Comparou-se, em setembro de 2026, Qwen, Mistral e Gemma com instrução geral, engenharia de prompt e fine-tuning. Com instrução geral, nenhum modelo gera estruturas satisfatórias; com engenharia de prompt, só o Qwen produz JSON válido; após o fine-tuning, o Qwen tem o melhor desempenho, e a lógica do fluxo falha em Mistral e Gemma. Em seis processos, ChatGPT e Gemini atribuem nota média de 8,32 em 10, sem validação humana nem métricas quantitativas. A SGP/UFRN utiliza o protótipo desde 15/10/2026, com retorno informal positivo. O desempenho do Qwen aponta viabilidade preliminar, sem confirmar a hipótese de superioridade sobre modelos não especializados. A tecnologia apoia a documentação de processos em instituições federais de ensino superior, sob revisão humana.

### Palavras-chave
Inteligência Artificial Generativa. Modelos de Linguagem de Grande Escala. Processamento de Linguagem Natural. Fluxo de Trabalho. Modelos Organizacionais.

## Discentes

- Alex Ferreira de Almeida (almeida_alex@discente.ufg.br / alexferreiradealmeida@gmail.com) 
- Anderson Costa Lima (andersonlimac90@gmail.com) 
- Carlos Henrique Souza dos Santos (carlosheenrique.on@gmail.com) 

## Professores Avaliadores
- Dr. Sérgio Teixeira de Carvalho
- Dr. Sandrerley Ramos Pires
- Dra. Nádia Félix Felipe da Silva

## License

This repository is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
