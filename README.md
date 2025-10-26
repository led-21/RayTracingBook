# RayTracingBook

Este projeto é uma implementação prática baseada no livro clássico de Ray Tracing ("Ray Tracing in One Weekend" e seus volumes seguintes). Seguindo o passo a passo apresentado no livro, o objetivo é construir do zero um renderizador de imagens utilizando técnicas de ray tracing, aprimorando conceitos de computação gráfica e programação.

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar](#como-executar)
- [Referências](#referências)

## Sobre o Projeto

O projeto foi desenvolvido acompanhando o passo a passo do livro, implementando cada conceito e funcionalidade de forma incremental. Entre os principais tópicos abordados estão:

- Geração de imagens simples com ray tracing.
- Modelagem de cenas 3D com diferentes objetos geométricos.
- Implementação de materiais (difusos, metálicos, dielétricos).
- Adição de iluminação e técnicas de antialiasing.
- Aperfeiçoamento do desempenho e recursos avançados.

## Estrutura do Projeto

A estrutura segue a evolução proposta pelo livro, com cada capítulo representando uma etapa ou funcionalidade nova no código. Exemplos de diretórios e arquivos:

```
├── src/
│   ├── main.cpp
│   ├── ray.h
│   ├── vec3.h
│   ├── hittable.h
│   ├── sphere.h
│   ├── camera.h
│   └── ... (outros arquivos conforme evolução)
├── images/
│   └── (resultados das renderizações)
├── README.md
```

## Tecnologias Utilizadas

- **C++** (padrão C++11 ou superior): Linguagem principal para implementação dos algoritmos.
- **Compilador GCC/Clang**: Para construção dos binários.
- **Ferramentas de linha de comando**: Para execução e visualização dos resultados.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/led-21/RayTracingBook.git
   cd RayTracingBook
   ```

2. Compile o projeto:
   ```bash
   cd src
   g++ main.cpp -o raytracer -std=c++11
   ```

3. Execute o renderizador:
   ```bash
   ./raytracer
   ```

4. Os resultados serão salvos na pasta `images/` ou exibidos diretamente no terminal em formato PPM.

## Referências

- [Ray Tracing in One Weekend (Peter Shirley)](https://raytracing.github.io/)
- [Repositório Oficial dos Livros](https://github.com/RayTracing/raytracing.github.io)
- Documentação C++: https://en.cppreference.com/

---

Este projeto é ideal para quem deseja aprender os fundamentos de Ray Tracing, Computação Gráfica e aprimorar habilidades em C++.
